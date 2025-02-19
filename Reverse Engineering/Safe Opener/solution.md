We are provided with a java code, running it we get 3 attempts to get the passkey.:

![image](https://github.com/user-attachments/assets/da1ef046-4ec4-4c5c-8408-d36bce95010f)

Viewing the source code we see an encoded string:

![image](https://github.com/user-attachments/assets/65ae1f82-a912-4c73-b54e-2044d8285d0f)


Decoding it with base 64:
```
echo 'cGwzYXMzX2wzdF9tM18xbnQwX3RoM19zYWYz' | base64 -d
```

We receive the contents of the flag:

![image](https://github.com/user-attachments/assets/d60996e9-1d1c-43ec-bcab-6b50d6f07ee1)

Flag:

`picoCTF{pl3as3_l3t_m3_1nt0_th3_saf3}`
