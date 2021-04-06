# Flipkart_ProductReview_Scraping

## Overview

__This web app scraps the product reviews using BeautifulSoup library and displays the result back to you.__


__Prerequisites__ :

The things needed before we start building a python based web scraper are:
* Python installed.
*	A Python IDE (Integrated Development Environment): like PyCharm, Spyder, or any other IDE of choice 
*	Flask Installed. 
*	MongoDB installed .
*	Basic understanding of Python and HTML.
*	Basic understanding of Git , [download Git CLI](https://gitforwindows.org/)
* [Download the Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli#download-and-install)

__How To Run__ :

Open Up Any Python IDE :
```bash
activate your environment 
```
Install the packages in your environment :
```bash
pip install -r requirements.txt
```
Open MongoDB Compass:
```bash
Connect from your local: mongodb://localhost:27017/ to see the reviews you have scrapped (after scraping)
```

Run app.py :
```bash
python app.py (on your terminal or right click and run)
```
- Enter The Product you want to scrap and the reviews will be displayed and stored in MongoDB so that next time it will scrap from the database itself.

**Heroku Deployment**

- After installing the Heroku CLI, Open a command prompt window and navigate to your ‘Flipkart_ProductReview_Scraping’ folder.

- Type the command to login to your heroku account as shown   below: :
```bash
heroku login
```

- After logging in to Heroku, enter the command as below to create a heroku app. It will give you the URL of your Heroku app after successful creation. :
```bash
heroku create 
```
- Before deploying the code to the Heroku cloud, we need to commit the changes to the local git repository.

- Type the command as below to initialize a local git repository  as shown below: :
```bash
git init 
```

```bash
git status
```

```bash
git add .
```

```bash
git commit -m "initial commit" 
```

- Enter the command as below to push the code to the heroku cloud.
```bash
git push heroku master
```
- After deployment, heroku gives you the URL to hit the web API. 

-	Once your application is deployed successfully, enter the command as below to see the logs.
```bash
heroku logs --tail
```
