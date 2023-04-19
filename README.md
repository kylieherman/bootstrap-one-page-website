# bootstrap-one-page-website :desktop_computer:

starter files for creating a basic one page html/css website, please **fork** this repository into your own repo. If you've forgotten how, please revisit this content: https://github.com/Northern-State-University/github-starter-course specifically: https://github.com/Northern-State-University/github-starter-course#-github-terms-to-know

Once you've successfully forked the files, please follow the below instructions. The file you should be working on is called ```one-page-website-starter.html``` **IF** you get stuck you can peek at the ```one-page-website-final.html```.

No matter how (un)comfortable :sweat_smile: you may feel about coding, there is something here for every level. The most important takeaway from this lesson is reading comprehension and following instructions. Don't be intimidated, you got this. Hints also exist in the ```one-page-website-starter.html``` file.

## What you will learn
### Get more familiar with Github
### Introduce yourself to basic web coding
### Run a local web server right on you GitHub repository

## Step 1
Let's view your live webpage in your repository, click the green code button and the click "Open Codespaces"

![screenshot1](https://github.com/Northern-State-University/bootstrap-one-page-website/blob/main/one%20page%20website/img/step1.png)

👉 Then click your ```one-page-website-starter.html``` on the left 👈

![screenshot1](https://github.com/Northern-State-University/bootstrap-one-page-website/blob/main/one%20page%20website/img/step1c.png)

Open the terminal if not already opened (ctrl+shift+p to open the command palette, and then type "toggle terminal" and Enter to select)

Type ```npm i -g http-server``` in the newly opened terminal (this will install the tool to easily create a server) 1
Next, you have to run the server, type ```http-server``` in the same terminal.

You'll then be prompted with this notification Open in Browser prompt You can click Open in Browser and see the result there, if your index.html file is at the root of your project it will be opened by default or else you'll need to write the correct path in the URL bar.

![screenshot1](https://i.stack.imgur.com/B5ho8.png))

You should see something like this:

![screenshot1](https://github.com/Northern-State-University/bootstrap-one-page-website/blob/main/one%20page%20website/img/step2.png)

## Step 2

Let's explore the ```href``` atrtibute. ```href``` is [simply a link to a file, image or website](https://www.googleadservices.com/pagead/aclk?sa=L&ai=DChcSEwjhi6vW1Lb-AhVe8eMHHbfXCagYABAAGgJ5bQ&ohost=www.google.com&cid=CAESbeD28oHZZWLyNuYi6kIFjHX4ECsklIUw9Qf6Y-wbsMJ2w_b2uXwoiCwXd_lvLediInGFY2-CQxoyaAVmKESjMusTPDvYdGzmK47fJLHoXQAmxPSxRlEKI3t7LaQqJnSmhXMSV2K8_T0iWbWxFjg&sig=AOD64_3xQxaxJJ10ZuOgbjeivWv5kJms4A&q&adurl&ved=2ahUKEwjt-6HW1Lb-AhURjokEHYzkBIUQ0Qx6BAgDEAE) that you can use to display on your web page or click out to visit another. ```one-page-website-starter.html``` is where we are going to be doing all of our work. 

open ```one-page-website-starter.html``` here in GitHub

![screenshot1](https://github.com/Northern-State-University/bootstrap-one-page-website/blob/main/one%20page%20website/img/step1a.png)

![screenshot2](https://github.com/Northern-State-University/bootstrap-one-page-website/blob/main/one%20page%20website/img/step1b.png)

We need to use ```href``` to link the ```css/styles.css``` file (this styles our code to make it look nice in a web browswer, to our ```.html``` file. There is a comment in the bottom of the ```<head>``` section. Use ```<link rel="stylesheet" href="css file path here">``` to link your style sheet to your web page.

## Step 3
Let's continue 👉 with ```href``` now by using external links. Click around on your live webpage. Notice your menu links. Lets add real URLs to them! Pick any website you like and put that website in the ```href``` for each of the three links. then change the text in the menu to reflect what website a person would be clicking on.

## Step 4
Let's add to our knowledge of paths and URLs, this time with images using the ```src``` tag. It's basically like href, but it doesn't link out from the webpage, rather brings content in. Go to [https://getavataaars.com/](https://getavataaars.com/) and create an avataar and upload it to the img folder in your repository. If you'd like, you can use the one that is already there. the same way we linked ```css/styles.css``` above, lets now add '''img/myavataarname.png``` to the ```scr=""``` in the ```<img>``` tag. Control-S to save. Preview that it works in your live webpage. 
