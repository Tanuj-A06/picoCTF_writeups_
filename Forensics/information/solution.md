**Description**

**Files can always be changed in a secret way. Can you find the flag?**

Use exiftool to get extra information, we get:
![image](https://github.com/user-attachments/assets/ccca8386-81a7-4086-a6b8-2d23faa0b0a9)

The *License* looks intresting.

Its base64 encoding. Decoding it:
```
echo 'cGljb0NURnt0aGVfbTN0YWRhdGFfMXNfbW9kaWZpZWR9' | base64 -d
```
This spits out the flag
```
picoCTF{the_m3tadata_1s_modified}
```
