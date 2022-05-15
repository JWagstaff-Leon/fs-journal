# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
to list the dependancies required by the project
``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
the top level of the server, because the platform you deploy to will be the server
```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm run build
```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
evironment variables (.env)
```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
from the app page on the heroku dashboard, under the more tab
using the heroku cli 'heorku logs' command
```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
rebuild it and push it to the provided git remote
```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
It allows continuing development without disrupting the main branch, while still retaining the benefits of committing often and potential rollbacks.
```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
Ideally while it is being written, through the use of partner programming; but otherwise before deployment.
```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
merging
```