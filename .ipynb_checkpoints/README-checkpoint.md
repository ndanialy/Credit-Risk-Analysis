# Credit Risk Analysis
 A supervised learning model to classify loans.

---

## Technologies

This project uses Jupyter Lab in addition to the following libraries and add ons:

* [pathlib](https://docs.python.org/3/library/pathlib.html) for the path functions to locate the csv files.

* [pandas](https://pandas.pydata.org/docs/) for working with dataframes.

* [matplotlib](https://docs.python.org/3/library/pathlib.html) for the data visualization.

* [numpy](https://numpy.org/doc/) for certain numericalfunctions.

* [sklearn](https://scikit-learn.org/stable/user_guide.html) for the logistical regression.
---

## Installation Guide

Please run the following commands in your terminal before running the app:
```
pip install jupyterlab

pip install python-dotenv

pip install sklearn

```
---

## Usage

The App imports loan data from the csv in the resources fileand displays it:

![Data_import](https://user-images.githubusercontent.com/96391748/159152633-5535afea-8308-44f9-9828-d7295921cc01.PNG)

The data isthen processed, split, andrun through a logistic regression model with the results being displayed:

![regression_results](https://user-images.githubusercontent.com/96391748/159152701-80333319-569d-46e9-9557-8732ef73900f.PNG)

Finally, the data is resampled, the regression is run once more andthe results are compared:

![resampled_results](https://user-images.githubusercontent.com/96391748/159152740-5cd6dd2f-9d75-40e0-831b-f9c4f7635753.PNG)

---

## Contributors

* Nicklaus Danialy nickdanialy@gmail.com 

---

## License

Copyright (c) [2021] [Nicklaus Danialy]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE