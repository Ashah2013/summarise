# summarise

Table of Content

   - [Screenshot](#screenshot)
   - [Idea of application](#idea-of-Application)
   - [Technical Aspect](#Technical-Aspect)
   - [Installation](#Installation)
   - [Bug](#Bug)
   
  # Screenshot 
  ![prev](https://user-images.githubusercontent.com/63425649/102718342-a95cd000-430d-11eb-9ed4-f20b70c6a7a9.JPG)

  ![curr](https://user-images.githubusercontent.com/63425649/102718387-e032e600-430d-11eb-9902-2a2a1368b8c9.JPG)

  ![run](https://user-images.githubusercontent.com/63425649/102718372-cf827000-430d-11eb-94d1-862e1b9a987e.JPG)

  ![end](https://user-images.githubusercontent.com/63425649/102718407-f3de4c80-430d-11eb-9c55-7229d9dc2575.JPG)
  
  # Idea of Application
  Built a Extractive text summariser as people as short of time...additionally how efficiently algorithms works to summarise the given texts by writing a gold summary as a reference can be evaluated.
  -Extractive text summariser (create summary from phrases or sentences in source document)

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
  Incase any bug is found, kindly open an issue [here](https://github.com/Ashah2013/voiceAssistant/issues/new) by including your search query and the expected result.
  

