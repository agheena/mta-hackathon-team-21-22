from flask import Flask
from flask import render_template
from flask import jsonify
from flask import request

app = Flask(__name__)

@app.route("/")
def d3():
    return render_template('index.html')




if __name__ == "__main__":
    app.run("localhost", 7777, debug=True)
