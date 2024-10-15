# ansible 執行playbook的時候 如果是第一次登入不需確認 (Are you sure you want to continue connecting (yes/no/[fingerprint])?)


![image](https://hackmd.io/_uploads/rJZoFqiykg.png)


```
 -e 'ansible_ssh_common_args="-o StrictHostKeyChecking=no"'
```

```
sample
 ansible redis-ms -m shell -a 'pwd' -i inventory.instance.create.yml -e 'ansible_ssh_common_args="-o StrictHostKeyChecking=no"'
```