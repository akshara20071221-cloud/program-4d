# program-4d
# 🧪 C Programming Lab
## 📘 Experiment No: 4d
### 🔹
**Date:** 20/3/2026  
**Name:** AKshara.k 
**Register No:** 25003090 

---

## 🎯 AIM
To write a C program to count the number of punctuation characters in a given string.
---

## 🧠 ALGORITHM
1.Get a string as a input from the user.
2.Count the number of punctuation characters using for loop and if else statements.
3.Print the result using printf() function.
---

## 💻 PROGRAM

```
#include<stdio.h>
#include<ctype.h>
#include<string.h>
int main()
{
    char str[100];
    fgets(str,sizeof(str),stdin);
    int count=0;
    for(int i=0;str[i]!='\0';i++)
    {
        if(str[i]==','||str[i]=='.'||str[i]=='!')
        count++;
    }
    printf("%d",count);
}

```

## 🖼️ OUTPUT SCREENSHOT

<img width="684" height="177" alt="image" src="https://github.com/user-attachments/assets/afaff6da-bc22-4c02-9a6f-3074cfd4cfd1" />

---

## ✅ RESULT
:Thus the C program to count the number of punctuation characters is executed successfully.
