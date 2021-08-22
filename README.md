checkout blockchain.py inside the gymcoin folder to see implementation \
Read more about this project here: https://medium.com/@nathan_149/making-my-own-cryptocurrency-from-scratch-42e05d4460c2
if you "pip install" all the dependencies in blockchain.py, and then run run.py on one terminal and run2.py on another terminal it should work!


Steps : 

Install python 
Now go to the installation directory 
C:\Users\<User>\AppData\Local\Programs\Python\Python39\Scripts
C:\Users\<User>\AppData\Local\Programs\Python\Python39

Now add these to the environment variables to access the script commands like PIP in the command prompt



Now upgrade pip 
c:\users\<User>\appdata\local\programs\python\python39\python.exe -m pip install --upgrade pip

Now you require a requirements.txt 
```
pip install pipreqs

pipreqs /path/to/project
```

This will install pipreqs package 

> pipreqs gymcoin/blockchain.py 

This will create the requirements file in the gymcoin project 

or you can create a requirements.txt with the below content 
requests==2.26.0
Flask==2.0.1
flask_bcrypt==0.7.1
flask_login==0.5.0
flask_sqlalchemy==2.5.1
flask_wtf==0.15.1
jsonpickle==2.0.0
pycryptodome==3.10.1
WTForms==2.3.3

now 
> pip install -r gymcoin/requirements.txt
>pip install email_validator
> python run.py    
This will not work for permission issue 

Now you have to open command prompt in admin previledge and browse to this folder 
 
> python run2.py  
This will work
Now you can run multiple instances by copying the run2.py and changing the port numbers 

Now access the page in the browser like this 
http://127.0.0.1:5001/