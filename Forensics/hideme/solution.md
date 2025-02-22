Download the file, it seems a normal image file, no clues or hints from exiftool.

Ran strings on the file and found something intresting:

![image](https://github.com/user-attachments/assets/bce48366-43ce-49df-9d74-372a13de96f8)

Looks like there is a hidden folder inside the image.

Extracting the hidden folders through binwalk:

`binwalk -e flag.png`

![Screenshot 2025-02-22 210650](https://github.com/user-attachments/assets/3dde9f75-0e6d-4732-9a32-73ce4fcb7300)

Bingo!! We get the flag hiding inside a directory named 'secret':
![image](https://github.com/user-attachments/assets/4e2ba698-3afa-4f16-b39b-8010f1ab1e57)
