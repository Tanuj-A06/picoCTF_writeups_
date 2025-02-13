I downloaded the file via 'wget' and used 'exiftool' to see if there were any hints given.

![image](https://github.com/user-attachments/assets/a1c743c5-05b0-4f4c-bd27-e1fa117f9273)

Didnt find anythin useful here.

Using strings:

```
strings warm | grep -in picoCTF{
```

we get the flag:
![image](https://github.com/user-attachments/assets/6a292262-a2c6-445b-97c7-a191836c7d44)


Flag:
```
picoCTF{b1scu1ts_4nd_gr4vy_d6969390}
```
