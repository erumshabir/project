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



For Deployment on heroku
1. First, create an Heroku account (free account is fine for testing)
2. Install Heroku on your machine: https://devcenter.heroku.com/articles/getting-started-with-python#set-up
3. Clone this repository,
or create your own repository that follows the same structure:
i- Create your Notebook and put it in the notebooks folder
ii-Add the dependencies needed for running your Notebook in the requirements.txt file
iii-Edit the Procfile file by replacing notebooks/yourfilename.ipynb by the path to your Notebook
iv-Commit everything
    -git add -A
    -git commit -m "My awesome app on Heroku!"
    
4:Open anaconda prompt:
write hreoku login and it will open heroku on browser write username and password and login it will show login in prompt

5: Write heroku create to create project on heroku

6:Write git push heroku master for deployment

7:When it done write heroku open it will open app on your browser.
