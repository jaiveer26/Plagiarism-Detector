# ***DÉJÀ-VU***
( A project under **INNODEV ( ELECTROMANIA- 2020 )** )

TEAM NAME - "LA CASA DEL CODIGO"
TEAM DETAILS-
1.SATYAM RAJ (LEADER) 20195067 - ECE (2ND YEAR)


2.JAIVEER SINGH 20193088-MECH(2ND YEAR)


3.AYUSH KANODIA 20195078 - ECE (2ND YEAR)


4.NAMAN GUPTA 20196036 - PIE (2ND YEAR)


## **PROBLEM STATEMENT**

Nikhil's startup has just finished their first round of hiring. He has been
informed that the invigilation was not up to the mark. The test contained both
subjective and coding questions. Help him build a plagiarism detector that can
detect both text and source code plagiarism.

## **TECH STACK**

1. HTML , CSS , Bootstrap and JS (for frontend)

2. DJANGO WEB-FRAMEWORK(for backend)

## **PROPOSED FEATURES(According to given Problem Statement)-**

- Show plagiarism score.
- Login/ Signup for user 
- Allow multiple file formats in the user interface.
- Give an option for plagiarism check from a specific source. Ex:-
      medium, GFG etc.
- Download and share options for generated reports. 
- Give a detailed report about percentage similarities and reference.      
  
## **ADDITIONAL FEATURES FOR FUTURE PROSPECTS.**
- Provide APIs for platform integrations.
- Option for recent tab to show user's past action.


## ***ABOUT DEJA-VU-***

A basic python API developed on django platform for calculating similarity percentage/plagiarism percentage between original and reference code in which the user needs to either *enter the reference code manually*, *upload the reference code file* or can *upload the link of the reference code from some of the online sites* like **GFG, Medium, etc.**  

## ***VARIOUS FEATURES PROVIDED-***
- Login, Logout, and Profile Update features provided to user.
- Login using Social Authentication via Google and Facebook.
- Downloading the Final Result/Report in the form of PDF.
- Report will consist of the plagiarism percentage along with the highlighted text showing the common text from both the input text and the reference text.


## ***Various Libraries, Modules and Technologies Used-:***

- **For uploading various file formats-**
  1. doc2txt
  2. PyPDF2
  3. Pdf mining
  
- **For Featuring Reference Code Links from the Online Sites-**
  1. Beautiful Soup
  2. Web Scrapping
  3. Requests

- **For Matching Both the Codes Sequentially-**  
  1. NLTK 
  
- **For Social Authentication on LogIn Page(Using Google and FB)-**
  1. django allauth
  2. social_django
  
- **To generate final results and reports-**
  1. ReportLab
  2. Reportlab Canvas
  3. PDFmetrics
  

 ***To run the project on your system-:***

- Clone the repo on to your system.
- Add all the requirements to your system as like the modules and all the libraries.
- You can use a virtual environment if you want to keep your development environment seperate.

Change directory to inno and run the following command.
>python manage.py runserver

Now, paste `http://127.0.0.1:8000` on web browser and enjoy our app.
This link, by default, will take the user to home page.

##**Here are the some of the screenshotf from our app.**
1. **Home Page**
      ![alt text](https://github.com/Ayushkanodia11/D-j-vu/blob/main/screenshots/home1.jpeg?raw=true)
      ![alt text](https://github.com/Ayushkanodia11/D-j-vu/blob/main/screenshots/home2.jpeg?raw=true)
      ![alt text](https://github.com/Ayushkanodia11/D-j-vu/blob/main/screenshots/home3.jpeg?raw=true)
      ![alt text](https://github.com/Ayushkanodia11/D-j-vu/blob/main/screenshots/home4.jpeg?raw=true)
    
2. **Login Page** 
      ![alt text](https://github.com/Ayushkanodia11/D-j-vu/blob/main/screenshots/login.jpeg?raw=true)

3. **Register Page**      
      ![alt text](https://github.com/Ayushkanodia11/D-j-vu/blob/main/screenshots/register.jpeg?raw=true)

4. **Final Report Generation Page**
      ![alt text](https://github.com/Ayushkanodia11/D-j-vu/blob/main/screenshots/generate_report.jpeg?raw=true)


### ***Thank You for your valuable time.***
