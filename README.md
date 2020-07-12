"Predict Future Product Prices Using Facebook Prophet"
-It is project "Avocado Price Prediction using FB Prophet.ipynb" file from couresera, It predict the
future sales in US and it region. fbprophet is used for prediction. 
fbprophet is an open source library published by Facebook.
-The data set is used in this project is "avocado.csv", this file consist  sales of avocados in different
 regions of US.
-This project plot graphs of given data and after predicting the future.We can see sverage price in All regions and also in particuler region.

-I created web app using Voila and widgets "app.ipynb" this is based on "Avocado Price Prediction using FB Prophet.ipynb" 
and show graph of data and predicted average prices in region of US.

Execution of project:
We need for jupyter notebook( we can download from here https://jupyter.org/install or any othr site)
We write code "Avocado Price Prediction using FB Prophet.ipynb" on jupyter notebook (install libries)
{You must install fbprophet package as follows: pip install fbprophet
If you encounter an error, try: conda install -c conda-forge fbprophet}
 and used "avocado.csv".
Run jupyter notebook on anaconda prompt(or other cmd) it will open jupyter notebook, upload ipynb file and dataset and run.


For python webapp:
We need jupyter and voila
open cmd(anaconda prompt) write following commnads
mkdir voila
cd voila
python -m venv venv
source venv/bin/activate
pip install voila
pip install jupyter numpy matplotlib

place "avocado.csv",and "app.ipynb" inside voila folder
and write this command voila app.ipynb in anaconda prompt.It will load file(website) on localhsot.
