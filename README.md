# Project Title

Project Title: Loan Analyzer Application

This project allows the user to enter a list of loans in .csv format ( using this format for column headers "Lender","Max Loan Amount","Max LTV","Max DTI","Min Credit Score","Interest Rate" and each row representing a specific loan offered by a financial institution) the program then goes to ask the user to input his Credit Score, Monthly Debt, Monthly Income, Desired Loan, and Home Value. Once the user has inputted this information it calculates the Debt-to-Income and Loan-to-Value ratios prints it and filters thru the list of of loans to determine which are fit based on the inputs and the ratios calculated, it prints the number of

Just after the title, introduce your project by describing attractively what the project is about and what is the main problem that inspires you to create this project or what is the main contribution for the potential user of your project.

---

## Technologies


* Python � Version 3.9.7
* Fire � Version 0.3.1
* Questionary � Version 1.5.2
* Path (from pathlib)
* csv (adds classes to read/write tabular data)
* sys


## Installation Guide

1. Install Python 3.9.7

For installing Python 3.9.7 you can find the Installation Files for both Windows/Mac OS in the following link: 
https://www.python.org/downloads/release/python-397/

If you require assistance installing it, you can follow the following videos for guidance:
https://www.youtube.com/watch?v=uSVl7gRXP80 (Windows OS)
https://www.youtube.com/watch?v=r6bBaj797t8 (Mac OS)

2. Installing Required Libraries (Fire and Questionary)

a. Installing Fire

![image](https://user-images.githubusercontent.com/94983278/148540562-7ba2de97-046a-48f8-919d-127144e24e67.png)

To install Fire 0.3.1 use the following command in your GitBash/Terminal application �pip install fire==0.3.1�

If you require additional assistance installing Fire or would like to expand your knowledge of the library, here is a good resource from the developers: https://google.github.io/python-fire/guide/


b. Installing Questionary

![image](https://user-images.githubusercontent.com/94983278/148540628-f5b83a86-f3c6-4a98-bb41-cc04392ac398.png)

To install Questionary 1.5.2 use the following command in your GitBash/Terminal application �pip install questionary==1.5.2�

If you require additional assistance installing Fire or would like to expand your knowledge of the library, here is a good resource from the developers: https://pypi.org/project/questionary/


3. Installing the Loan Qualifier Application

Navigate to your desired location where you would like to save the documents for this application. You can do this by using the �cd� command followed by a space and the file path inside quotations ��. In my example I have gone to Desktop.


![image](https://user-images.githubusercontent.com/94983278/148540695-296033f1-3363-40ba-a874-c23b6044be5a.png)

Clone this projects repository from GitHub using the following command 
```git@github.com:epocaterrasus/CU-Assignment2-Loan_Analyzer_Improved.git```

---

## Usage

This section should include screenshots, code blocks, or animations explaining how to use your project.

---

## Contributors

Edgar Pocaterra � epocaterra@protonmail.ch / +1 806 283 5455

---

## License

MIT License

Copyright (c) 2022 epocaterrasus

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
