On connecting with nc we receive the following:

**'picoCTF{gl17ch_m3_n07_' + chr(0x61) + chr(0x34) + chr(0x33) + chr(0x39) + chr(0x32) + chr(0x64) + chr(0x32) + chr(0x65) + '}'**

We can now convert these glitched characters to string with python which will give us our flag:

![image](https://github.com/user-attachments/assets/ecf982a9-9fd0-4ac7-bdaa-d54827132d59)

Flag:

```
picoCTF{gl17ch_m3_n07_a4392d2e}
```
