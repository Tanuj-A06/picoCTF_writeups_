We are given a .svg file:
![image](https://github.com/user-attachments/assets/80a1369b-54ee-4fe3-8efb-f2a592f007b8)

Usual methods like steghide, binwalk yield no results.

I 'accidentally' used cat on the file and found something intresting:

![image](https://github.com/user-attachments/assets/83f884f2-06ef-49b4-9187-8dd1c8602b29)

The last line looks like a flag format:

Now greping for '</tspan':

![image](https://github.com/user-attachments/assets/485abea8-e89b-4ed4-b578-7c89c4d8a427)

Yep we are close,
now removing the '<tspan' tags:
![image](https://github.com/user-attachments/assets/969c258a-e425-4d09-9f57-bc024ea5e969)

Now tidying it up to get the flag:

![image](https://github.com/user-attachments/assets/82673959-3acd-4105-a31b-b689279bd606)
