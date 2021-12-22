# rsschool-cv

# Golub Anton

## Contacts
* **Location:** Israel, Ashdod
* **Phone:** +972 058-627-8355
* **Email:** jukonda23@gmail.com
* **GitHub:** Dominick7771

## About me
I have good interpersonal skills, am an excellent team worker and very willing to learn and develop new skills.
I am reliable and dependable and often seek new responsibilities within a wide range of employment areas.

## Skills
* HTML
* CSS/SASS
* JavaScript
* React
* Java
* C
* Git

## Code Example
```
#include <stdio.h>
#include <cs50.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>
#include <ctype.h>

int main(int argc, string argv[])
{
if (argc != 2)
{
printf("Usage ./caesar key\n");
return 1;
}
string check = argv[1];
for (int i = 0; i < strlen(check); i++)
{
if (isdigit(check[i]) == 0)
{
printf("Usage ./caesar key\n");
return 1;
}
}

    string plaintext = get_string("Enter your text: \n");
    int chipher = atoi(argv[1]);
    if (chipher > 26)
    {
        chipher = chipher % 26;
    }
    string chiphertext = plaintext;
    for (int i = 0; i < strlen(plaintext); i++)
    {
        if ((plaintext[i] >= 65 && plaintext[i] <= 90) || (plaintext[i] >= 97 && plaintext[i] <= 122))
        {
            if (isupper(plaintext[i]) != 0) //convert upper letters
            {
                if (plaintext[i] + chipher > 90)
                {
                    chiphertext[i] = (plaintext[i] + chipher) - 26;
                }
                else
                {
                    chiphertext[i] = (plaintext[i] + chipher);
                }
            }
            else if (islower(plaintext[i]) != 0)
            {
                if (plaintext[i] + chipher > 122)
                {
                    chiphertext[i] = (plaintext[i] + chipher) - 26;
                }
                else
                {
                    chiphertext[i] = (plaintext[i] + chipher);
                }
            }
        }
    }
    printf("ciphertext: %s\n", plaintext);
}
```

## Experience

* **System Administrator** - work experience 4 years
* **technical support** - work experience 1 years

## Education

* Ural Federal University named after the First President of Russia B. N. Yeltsin. Specialty "Business Informatics"
* Courses:
    * [rs.school](адрес "https://rs.school/")
    * [CS50 lectures](адрес "https://cs50.me/cs50x")
    * [HTML Academy](адрес "https://htmlacademy.ru/")
    * [Udemy](адрес "https://www.udemy.com/")

## English

**A2** (I am currently studying English using courses)
********* 
