We are provided with a pcap file with more than 900 packets.

![image](https://github.com/user-attachments/assets/a13b736a-6cf2-4dbc-b72c-8845d694fd5c)

Analysing the files in specific TCP streams we find the encoded flag in tcp stream 5.
![image](https://github.com/user-attachments/assets/c74e7059-4245-46ab-8bc3-6d6d19c1ce46)

![image](https://github.com/user-attachments/assets/ab2c787a-d5e7-4c83-8e56-790be40a8fe0)


The encoding is done in ROT-13 cipher.

Decoding it we get the flag:

![image](https://github.com/user-attachments/assets/b221b122-9a1d-4e2c-9152-9fd0c1f37495)
