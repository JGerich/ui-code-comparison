**UI Code Comparison: React (JavaScript) vs Flask and Streamlit (Python)**
__________________________________________________________________________
__________________________________________________________________________
<br/><br/>



__⚛️ React (JavaScript) 🟨__  (Source: https://react.dev/learn )



The following code is written in JavaScript using React, a library for building user interfaces. 
It uses JSX (JavaScript XML) syntax and defines two functional components: MyButton and MyApp.

<img src="https://github.com/user-attachments/assets/cc3a0c14-830b-4283-83e5-7f92be5cbc75" width="350"/>


<br/>This code displays a heading and a button. React uses JSX, ES6 module syntax (export/import), and is JavaScript-based.<br>




<br/>And here’s the result:

<img src="https://github.com/user-attachments/assets/086b7c50-5e9b-4987-bb4e-c5a8cf984675" width="300"/>




<br/>(Source: https://codesandbox.io/p/sandbox/xftrpt?file=%2Fsrc%2FApp.js%3A10%2C11 )



<br/><br/>

_____________________________________________________________________________________________
_____________________________________________________________________________________________

<br/><br/>


__🐍Python (Flask ☕ + Jinja2 🔧)__

To achieve similar UI in Python, we can use a web framework like Flask or Django.
Here is a simple example HTML template using Flask and Jinja2:
<br/>

1.Create a new project folder:
   
mkdir my_flask_app

cd my_flask_app


<br/>
2. Create the Python file:


app.py<br/><br/> 


3.Create the templates folder. This is where Flask looks for HTML files by default.

mkdir templates


<br/>
4. Create the HTML file inside templates


index.html


<br/>
5. Final Folder Structure Should Look Like:

<img src="https://github.com/user-attachments/assets/bce6c84d-c1de-4df8-bd40-a55bb10a4ac3" width="160"/> <br>








<br> The result:

<img src="https://github.com/user-attachments/assets/91caf05d-6800-425e-b726-96f91eb457f8" width="350"/>







<img src="https://github.com/user-attachments/assets/e24ac543-d24c-41e8-a0cc-a73e09fb2984" width="300"/> <br>





<br/>
<br> This renders a webpage at localhost:5000/ with a heading and a button, just like React example above:
<br/><br/>



<img src="https://github.com/user-attachments/assets/190d94b0-dfbb-4f6a-a2b6-0b988c606be3" width="200"/>



<br/><br/>
________________________________________________________________________________________________________________
________________________________________________________________________________________________________________

<br/><br/>
**Python (Streamlit)**

In order to create a similar and interactive result by using purely Python (without writing HTML), we could use Streamlit or Anvil.
Streamlit allows to build interactive web apps with pure Python. It's easier and doesn't require HTML or JS.
<br/>

1. Install Streamlit:

pip install streamlit



<br/>
2.	Create a Python file (e.g.: app.py)

app.py


<br/>
3.	Import streamlit as st
<br/><br/>


<img src="https://github.com/user-attachments/assets/3be70d24-e9b5-4f90-8d41-5da2b22b7568" width="400"/>



<br/><br/> 
4.	Run the app:

streamlit run app.py




<br/><br/>
This will open the app in a browser window at http://localhost:8501:


<br/>
<img src="https://github.com/user-attachments/assets/8559e77f-e926-4c8d-82cb-23f5e917229a" width="300"/><br/><br/>





<img src="https://github.com/user-attachments/assets/cf7585d8-1384-4f6e-aed8-34ec7cf7158b" width="200"/>




<br/><br/>
____________________________________________________________________________________________________________________
____________________________________________________________________________________________________________________





