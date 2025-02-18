![image](https://github.com/user-attachments/assets/8e85dbbf-f81e-46d1-ae14-eee3c6050e04)
---

The name itself suggests it has something to do with bases. Thus decoding the given cipher with base64 we get the contents of the flag!

```
echo 'bDNhcm5fdGgzX3IwcDM1' | base64 -d
```

![image](https://github.com/user-attachments/assets/ca211b07-5816-4648-965f-e7d6f35b70ff)


Flag:
```
picoCTF{l3arn_th3_r0p35}
```
