# cmsc240-mod-8
Module #8 - Totally Not a [[SCAM]]

### Instructions

Write a C++ program that uses regular expressions to determine whether the user has input a valid text for each item specified and prints back their responses. Have the system repeat the question until the user provides a correct response.

**Use [regexr.com](regexr.com) to help figure out patterns!**

(Note: if you have difficulties opening the programs, try running `chmod +x not_a_scam`)

### Requirements

CODE

| Points                  | Task                                                                                                             | Example                                         |
|-------------------------|------------------------------------------------------------------------------------------------------------------|-------------------------------------------------|
|     Full Name [1pt]     | Only allow letters, apostrophes, and hyphens and require at least one space                                      | John Smith                                      |
|       A City [1pt]      | Only letters, followed by a comma then a space and 2 letter capital state                                        | Richmond, VA                                    |
|     A Username [1pt]    | Any character that starts with “xXx” and ends with “xXx” exactly                                                 | xXxjsmith2xXx                                   |
|     A Website [1pt]     | Must start with “www.”, “http://”, or “https://” and end with period and at least 2 lowercase letters            | www.google.com                                  |
|   A Double vowel [1pt]  | Anything that has at least 2 vowels in a row (does not have to be the same)                                      | soup                                            |
| Hexadecimal Value [1pt] | Matches the format “#xxxxxx” where x is a hexadecimal value (0-9,a,b,c,d,e,f)                                    | #f0aec4                                         |
|      Birthday [1pt]     | Matches the format “MM/DD/YYYY”, where MM is between 01-12, DD is between 01-31, and YYYY is more than 1900      | 12/31/1984                                      |
|   Error Message [1pt]   | Each question prints an error message when given an invalid answer and shows the required format with an example | WRONG: Format must be XXXXXX (example: XXXXXX)  |

*Subtotal: 8pts*

README.md

| Points | Description                        |
|--------|------------------------------------|
| 1pt    | Name, Date, Program Description    |
| 1pt    | How to compile and run the program |
| 2pt    | Example usage of the program       |

*Subtotal: 4pts*

**TOTAL: 12pts**

**10 pts total**
