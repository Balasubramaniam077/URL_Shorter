# URL_Shorter


URL shortening is a technique used to create a shorter, more manageable version of a long URL. This can be useful for sharing links on social media or in messaging apps, where character limits may apply. In Python, a URL shortener can be implemented using a library such as TinyURL or Bitly, which provide APIs for generating short URLs from long ones. The process typically involves making an HTTP request to the shortening service's API endpoint, passing in the long URL as a parameter, and then receiving a shortened URL in the response. The returned shortened URL can then be used in place of the original long URL

# Describe

The code uses SQLAlchemy, an ORM library, to create a database to store the original URLs and the shortened URLs which is an sqlite3 database and is stored in the local file system.

==>It creates a Flask app and a SQLAlchemy object, which will be used to interact with the database. 
==>It defines a URL model which is a Python class representing the URLs table in the database. 
==>It has two fields, id and original_url, where id is a primary key and original_url is the original url that is stored in the database.

# Requirements

 Anaconda (envs)
 Python == 3.9.2
 Flask == 1.2.1
 SQLAlchemy == 1.4.46
 
 # Installation
 
 ==> Pre-Requirement
 
 Anaconda(Anaconda is a distribution of the Python and R programming languages for scientific computing, that aims to simplify package management and deployment)
 
 # Github 
 
 Step 1 : Clone the Github Repo
 
            https://github.com/Balasubramaniam077/URL_Shorter.git
            
 Step 2 : Open the Anaconda Prompt and Create the New Envs using the given comment Below
 
            Conda Create -n  "Project name" "Python Version"
          
 Step 3 : Open the terminal into the cloned Folder or Direct enter the path by provide the cd Commend
 
 Step 4 : Install all the requirements for the URL shorter project by providing the commend it will process and Install all the Pre-Requirements
 
          pip install -r requirements.txt
          
 Step 5 : After completion of Installation for Requirements Libraries run the Python code 
 
          python app.py
          
 Step 6 : It takes Some time to proccess after completing the code the url will generate. Simply copy the url and apply in Browser it will open the Flask Web Application !!!
