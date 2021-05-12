Omkar Chaudhari
===================
## 200122042
___
## Coding Week Schedule


Event Name | Event Date | Gone through the Resources
--- | --- | ---
Open Source | 10/05/2021 | **YES**
Competitive Coding | 11/05/2021 |	NO
Design | 12/05/2021 |	NO
Game Development | 13/05/2021 |	NO
Web Development |	14/05/2021 | NO
Machine Learning | 15/05/2021 | **YES**
App Development | 16/05/2021 | NO
___
## Code to calculate sum of ASCII values of my full name
```C++
#include <iostream>
using namespace std;

void main() 
{
    int i;
    string name = "Omkar Ganesh Chaudhari";
    int sumofASCII=0;

    cout << "Full Name: " << name;

    for(i=0; i<name.length(); i++)
    {
      if(name[i]==' ')
      {
        continue;       //Spaces get ignored
      }else
      {
        sumofASCII = sumofASCII + int(name[i]);     //type casting, every character has a assigned ASCII value
      }
    }

    cout << "\nSum of ASCII Value of characters of my name(Case Sensitive) of " << name << " is: " << sumofASCII;
}
```
___
![Coding Week](https://github.com/codingiitg/open_source_submission/blob/main/Group%2095.png)
___
## Coding Club Logo


![Coding Club Logo](https://github.com/codingiitg/open_source_submission/blob/main/coding-club%20logo.png)
___

## Interests

ML
