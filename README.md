# app.py
from flask import Flask

app = Flask(__name__)
never slow down with me
@app.route('/')
def hello_world():
    return 'Hello, World!'

if __name__ == '__main__':
    app.run(debug=True)
