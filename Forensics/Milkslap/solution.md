Visiting the website we are greeted with an 'gif' which proceeds with the movement of our mouse from right to left.

![image](https://github.com/user-attachments/assets/1405b677-d184-4ed1-9428-7eb1ba195eb8)


Visiting the source code and looking around we find the name of this file is 'concat_v.png', this is an stack image.

Downloading it and running 'zsteg' on it: (NOTE: use `steghide` for ``.jpg`` and `zsteg` for ``.png``)

It throws an error!!!!
![image](https://github.com/user-attachments/assets/501c717b-a727-428e-8c45-004729c5631e)

Debugging:

Finding an closed thread on github helping to solve this perticular issue: (Direct link: https://github.com/zed-0xff/zsteg/issues/30)
![image](https://github.com/user-attachments/assets/51977289-dc5f-4cb5-b4cb-22b045899299)


Using the given aid, we are able to get the flag:
![image](https://github.com/user-attachments/assets/5da1d3bc-d93a-48d9-8f67-74ab2019cd33)

