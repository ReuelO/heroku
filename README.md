# heroku
### Express Generator Starter Template on Heroku
 
 To use the template, follow the steps below:
 Open a Heroku account. Check it out here: <tutorial link>
 Open the command prompt in the folder where you will have the app folder. Copy and paste the following to --
  Clone the repository and access the app folder

  
  ```
  git clone https://github.com/ReuelO/heroku.git
  cd heroku
  ```
  
  Check the git remote link and add an origin (main branch)
  ```
  git remote -v
  git remote remove origin
  git remote add origin https://github.com/ReuelO/heroku.git
  ```
  
  Create an app on Heroku
  ```
  heroku create <app_name>
  ```
  
  Connect the git repository to the Heroku app and deploy it
  ```
  heroku git:remote -a <app_name>
  git push heroku main
  ```
  
  Open the app: online or locally
  ```
  heroku open
  heroku local web
  ```
