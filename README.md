# RegEx Application

In this document, I solve [hackerrank challenges in several RegEx applications](https://www.hackerrank.com/domains/regex/re-introduction)

1. Detect HTML links > `var regex=/<a.*?href="(.*?)".*?>(.*?)<\/a>/ig;`
2. Detect HTML Tags
3. Find A Substring
4. Alien Username
5. IP Address Validation
6. Find a Word
7. Detect the Email Addresses
8. Detect the Domain Name
9. Building a Smart IDE: Identifying comments
10. Detecting Valid Latitude and Longitude Pairs
11. Password that must contain 8 or more characters that are of at least one number, and one uppercase and lowercase letter : `(?=.*\d)(?=.*[a-z])(?=.*[A-Z]).{8,}`
12. [Canadian Postal Code](https://en.wikipedia.org/wiki/Postal_codes_in_Canada): > `^[ABCEGHJKLMNPRSTVXY]\d[ABCEGHJKLMNPRSTVWXYZ]( )?\d[ABCEGHJKLMNPRSTVWXYZ]\d$`
13. [US Postal Code](https://en.wikipedia.org/wiki/ZIP_Code): > `^\d{5}(-\d{4})?$`

and more!
