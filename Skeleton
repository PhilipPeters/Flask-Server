from flask import Flask
import random

colors = [red, 'orange', 'yellow', 'green', 'blue', 'indigo', 'violet']

app = Flask(__name__)
@app.route("/")
def home():
    return "Hello, World!"
@app.route("/Philip")
def Philip():
    return "Hello, Philip"
@app.route('/user/<username>')
def user():
    index = random.randint(0, 7)
    color = colors[index]
    return 'Hello User ' + username + '. Is your favourite color ' + color + '?'

if __name__ == "__main__":
    app.run(debug=True)
