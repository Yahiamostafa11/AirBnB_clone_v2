# Flask Web Application

This is a Flask web application that listens on 0.0.0.0, port 5000. It has several routes that display different messages.

## Installation

To install the necessary requirements for this project, run the following command:

```bash
pip install flask

python app.py

The application has the following routes:

/: Displays "Hello HBNB!"
/hbnb: Displays "HBNB"
/c/<text>: Displays "C ", followed by the value of the text variable (replace underscore _ symbols with a space)
/python/(<text>): Displays "Python ", followed by the value of the text variable (replace underscore _ symbols with a space). The default value of text is "is cool"
/number/<n>: Displays "n is a number" only if n is an integer

Contributing
Contributions are welcome. Please fork the repository and create a pull request with your changes.

License
This project is licensed under the MIT License.