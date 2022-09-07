# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
### Step1: 
Start
### Step2:
Create a class and declare two variable with string datatype
### Step3:
Loop over the entire string and reverse it
### Step4:
Use if condition to check whether the string and the reversed string is equal or not
### Step5:
print palindrome if it's equal else print not a palindrome.
### Step6:
stop

## Program:
```
using System;
namespace chetan
{
    class Program
    {
        static void Main(string[] args)
        {
            string s, revs = "";
            Console.WriteLine(" Enter string");
            s = Console.ReadLine();
            for (int i = s.Length - 1; i >= 0; i--)
            {
                revs += s[i].ToString();
            }
            if (revs == s)
            {
                Console.WriteLine("String is Palindrome");
            }
            else
            {
                Console.WriteLine("String is not Palindrome");
            }
        }
    }
}
```

## Output:
![image](https://user-images.githubusercontent.com/75260837/188787001-47b4a2b0-c967-47f9-9f3f-44ca59adc36d.png)
![image](https://user-images.githubusercontent.com/75260837/188787136-ced06744-4f8c-49d3-9e41-1c1262a03273.png)


## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
