Downloadind the file we get an image, Exiftool yeilds out nothing intresting, trying to extract hidden information using steghide:

```
steghide --extract -sf atbash.jpg -xf flag.txt
```

Now the extracted text is saved to flag.txt:

![image](https://github.com/user-attachments/assets/f9f5c888-30cb-4cf3-8728-87705296e122)

Dcoding the encrypted text through 'atbash' cipher we get the flag:

![image](https://github.com/user-attachments/assets/0dd8fab3-4993-4ff1-af71-7b7e5c447ec8)
