# web-demo
A demo of web application


# app.pyfrom flask import Flask           # import flask
app = Flask(__name__)             # create an app instance

@app.route("/")                   # at the end point /
def hello():                      # call method hello
    return "Hello World!"         # which returns "hello world"if __name__ == "__main__":        # on running python app.py
    app.run()                     # run the flask app@app.route("/<name>")              # at the end point /<name>
# with name

def hello_name(name):              # call method hello_name
    return "Hello "+ name          # which returns "hello + name 
    
    
    
    















