We download the file and look inside it using text-editor 'nano':

![image](https://github.com/user-attachments/assets/f5cc1761-a0fd-49fa-9c96-30948fcd11db)

Through the final 2 '=' signs it's easy to predict it to be base64 encoded.

dcoding base64 encoding through terminal
```
echo YidkM0JxZGtwQlRYdHFhR3g2YUhsZmF6TnFlVGwzWVROclh6YzRNalV3YUcxcWZRPT0nCg== | base64 -d
```

We get another base64 encoded cipher with some extra characters:
![image](https://github.com/user-attachments/assets/415542f1-7926-43fa-806d-f03e49151cdf)

again decoding base64 encoing
```
echo d3BqdkpBTXtqaGx6aHlfazNqeTl3YTNrXzc4MjUwaG1qfQ== | base64 -d
```

we get the flag but its necoded in another form(Most probably ceaser or rotation cipher.)

**********wpjvJAM{jhlzhy_k3jy9wa3k_78250hmj}**********

dcoding it through 'ROT' cipher we get our final flag:

*****picoCTF{caesar_d3cr9pt3d_78250afc}*****
