# summarise

Table of Content

   - [Screenshot](#screenshot)
   - [Idea of application](#idea-of-Application)
   - [Technical Aspect](#Technical-Aspect)
   - [Installation](#Installation)
   - [Bug](#Bug)
   
  # Screenshot 
  ![Capture](https://user-images.githubusercontent.com/63425649/103823508-3b97fe80-5098-11eb-9267-029f3041a2fb.JPG)<br/>

  ![1Capture](https://user-images.githubusercontent.com/63425649/103823645-7d28a980-5098-11eb-8f7e-5950d2bd3399.JPG)<br/>
  ![2Capture](https://user-images.githubusercontent.com/63425649/103823695-96315a80-5098-11eb-87bd-bd8fd3da82d4.JPG)<br/>
![3Capture](https://user-images.githubusercontent.com/63425649/103823735-ab0dee00-5098-11eb-8396-9b5815eaec97.JPG)<br/>

  ![4Capture](https://user-images.githubusercontent.com/63425649/103823758-b95c0a00-5098-11eb-9314-8ac371e0cb61.JPG)<br/>
![5Capture](https://user-images.githubusercontent.com/63425649/103823816-d0026100-5098-11eb-83cf-ddd795f593b9.JPG)<br/>
![6Capture](https://user-images.githubusercontent.com/63425649/103823832-db558c80-5098-11eb-8297-0b6b80e2c484.JPG)<br/>
![7Capture](https://user-images.githubusercontent.com/63425649/103823868-e6a8b800-5098-11eb-9789-b31d21466fe2.JPG)<br/>

  # Idea of Application
  Built a Extractive text summariser as people as short of time...additionally how efficiently algorithms works to summarise the given texts by writing a gold summary as a reference can be evaluated.
  - Extractive text summariser (create summary from phrases or sentences in source document)

  # Technical Aspect
  It summarizes text using two algorithms-
  1. TextRank
  2. TF-IDF (Term frequency-Inverse document freqency)<br/>
  and analyzes their effciency using
  - ROUGE (Recall  oriented Understudy for Gisting Evaluation)
  
  # Installation
  The Code is written in Python 3.7 in Django framework. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```
After that you have to configure the database. Add the details to settings.py

Once it has been done and you have the keys and secrets, you have to make migrations and then migrate.

cd into the app directory and run
```bash
python manage.py makemigrations
```
to create migration files for the models already defined in the codes you have cloned. after that you have to run
```bash
python manage.py migrate
```
to start the development server
```bash
python manage.py runserver
```
  
  # Bug
  Incase any bug is found, kindly open an issue [here](https://github.com/Ashah2013/summarise/issues) by including your search query and the expected result.
  

