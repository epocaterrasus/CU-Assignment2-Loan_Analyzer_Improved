# Loan Analyzer Application (Improved)


This project allows the user to enter a list of loans in .csv format ( using this format for column headers "Lender","Max Loan Amount","Max LTV","Max DTI","Min Credit Score","Interest Rate" and each row representing a specific loan offered by a financial institution) the program then goes to ask the user to input his Credit Score, Monthly Debt, Monthly Income, Desired Loan, and Home Value. Once the user has inputted this information it calculates the Debt-to-Income and Loan-to-Value ratios prints those values and then filters thru the list of of loans to determine which are fit based on the inputs and the ratios calculated, it prints the number of qualifying loans and then gives the user the possibility of saving the capability of saving these in a custom or default path.

User Stories:

* As a user of the application I want to be able to upload customized loan information so that I have the most up to date data that meets my specific requirements.
* As a user of the application I want to be able to input my credit conditions and prospective home purchase information so that the program can filter the loans that meet my conditions.
* As a user of the application I want to be able to save the output qualifying loans so that I can review them and revisit them in the future.


---

## Technologies

The following technologies were used to build and deploy this application:

* Python - Version 3.9.7
* Fire - Version 0.3.1
* Questionary - Version 1.5.2
* Path (from pathlib)
* csv (adds classes to read/write tabular data)
* sys


## Installation Guide

### 1. Install Python 3.9.7

For installing Python 3.9.7 you can find the Installation Files for both Windows/Mac OS in the following link
 * [Python Installation Guide](https://www.python.org/downloads/release/python-397/ "Python Installation Guide")


If you require assistance installing it, you can follow the following videos for guidance
* [Youtube Video Python Installation Guide - Windows](https://www.youtube.com/watch?v=uSVl7gRXP80 "Python Installation Video - Windows") 
* [Youtube Video Python Installation Guide - Mac](https://www.youtube.com/watch?v=r6bBaj797t8 "Python Installation Video - Mac") 

### 2. Installing Required Libraries (Fire and Questionary)

#### a. Installing Fire

![image](https://user-images.githubusercontent.com/94983278/148540562-7ba2de97-046a-48f8-919d-127144e24e67.png)

To install Fire 0.3.1 use the following command in your GitBash/Terminal application 

```pip install fire==0.3.1```

If you require additional assistance installing Fire or would like to expand your knowledge of the library, here is a good resource from the developers 
* [Fire Python Guide](https://google.github.io/python-fire/guide/ "Fire Python Guide")


#### b. Installing Questionary

![image](https://user-images.githubusercontent.com/94983278/148540628-f5b83a86-f3c6-4a98-bb41-cc04392ac398.png)

To install Questionary 1.5.2 use the following command in your GitBash/Terminal application 

```pip install questionary==1.5.2```

If you require additional assistance installing Questionary or would like to expand your knowledge of the library, here is a good resource from the developers
 * [Questionary Python Guide](https://pypi.org/project/questionary/ "Questionary Python Guide")


### 3. Installing the Loan Qualifier Application

Navigate to your desired location where you would like to save the documents for this application. You can do this by using the ```cd``` command followed by a space and the file path inside quotations ```" file path "```. In my example I have gone to Desktop.


![image](https://user-images.githubusercontent.com/94983278/148540695-296033f1-3363-40ba-a874-c23b6044be5a.png)

Clone this project's repository from GitHub using the following command 

```git@github.com:epocaterrasus/CU-Assignment2-Loan_Analyzer_Improved.git```

---

## Usage

### 1. Verify

The first step is to be in the correct folder in which you have downloaded the repository in Step 3. You can confirm that you have all the correct documents/folders by using the command ```ls```, the following files and folders should appear:

* data
* qualifier
* app.py
* LICENSE
* README.md

![image](https://user-images.githubusercontent.com/94983278/148553378-3f98e7ee-ea22-4f70-9d9b-b95b4c6eddce.png)

If you don't see these files please make sure you navigate to the right folder using the ```cd``` command and make sure that you have downloaded the files as explained in the steps above.

Once you are ready, lets continue!

### 2. Run the Program

Enter the command ``` winpy python app.py``` and press enter.

![image](https://user-images.githubusercontent.com/94983278/148553751-3a2a6896-2c34-4270-83ee-8924e9abe327.png)

### 2. Enter the file path to your data

This program allows you to import your own bank loan data or to use the default data that comes with the program, in both cases you will need to provide the program with the Path to your data. For this example we will use the programs default data bank.

Enter ```./data/daily_rate_sheet.csv``` and hit enter.

![image](https://user-images.githubusercontent.com/94983278/148554257-d8fe130e-1562-4fb7-83fd-c8f3b9483f66.png)

### 3. Enter your inputs

The program will now prompt you to enter your:

* Credit Score
* Current Amount of Monthly Debt
* Current Monthly Income
* Desired Loan Amount
* Home Value

Enter these using your keypad and press enter after each which will prompt you to the next question! After entering all your inputs the application will give you your Debt-to-Income ratio and your Loan-to-Value ratio, two important parameters banks take into account when considering clients. Lastly it tells you the amount of loans you are applicable to.

![image](https://user-images.githubusercontent.com/94983278/148555874-610528b3-d354-4c05-90ac-7874f41d0257.png)


### 4. Decide if you would like to save your output

Now that you have inputted all your information, the program knows which loans are applicable for you, now it is time to decide whether to save them or not!

![image](https://user-images.githubusercontent.com/94983278/148555874-610528b3-d354-4c05-90ac-7874f41d0257.png)

If you would like to save your qualifying loans press ```y``` in your keyboard, if you don't want to press ```n``` and the program will automatically shut down.

### 5. Select Saving Path

![image](https://user-images.githubusercontent.com/94983278/148556267-f3fa0dc8-888b-441a-902d-62634fb26834.png)

This program has two options:

* Save to the default folder : Just press enter and the file will be saved inside the ```data``` folder of the program under the name ```qualifying_loans.csv```.

* Save to a custom folder: Locate the folder where you would like to save your file, right click and select Properties and copy the file path as shown below. You can now copy this filepath in the program and add a filename and extension. For example ```C:\Users\EdgarPocaterra-Susma\Desktop\mycustomfiles.csv```

![image](https://user-images.githubusercontent.com/94983278/148556783-b7a25c5f-40b3-4108-85a5-6746fb29fd57.png)

---

## Contributors

Edgar Pocaterra - epocaterra@protonmail.ch / +1 806 283 5455

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
