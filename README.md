# Description
**Youtube Comment Scraping and Analysis:**  It is a web application made specially for youtube content creators to know their reviews separately as positive and negative comments.



# What it does
- Asks for youtube video url and mail id.
- The web application scrapes the comments of the video and analyses the positive and negative comments.
- The time for scraping the comments depends on how many comments in the video. The estimate is that, it takes about 5 to 6 minutes to scrap 1000 comments.
- After the process is complete, the comments are mailed to the mail-id given by the user, as a excel file.
- Three files will be sent to the mail-id:
  - Full comments
  - Positive comments
  - Negative comments
- It will also produce a HTML table when the process is finished in the background.
- There are two tables: Positive Comments Table and Negative Comments Table.

- Run the codes in your preferred IDE [I JUPYTER NOTEBOOK]. It will run fine on local machine.
  

# Mail Sending File Changes
- Changes to be done in mail_sending_to_user_with_attached_csv_files.py
- Create one Gmail ID for sending emails to the user.
- **NOTE:** Do not use the password you created when opening the mail-id.
- After Creating Gmail id, Create your App Password and use this generated password in the program, so that google enables you to sign in via bot.
- Steps to Create App password:
  - Go to manage your google account -> Go to Setting -> Scroll down to find Signing in to Google -> Click App passwords -> Enter password -> Generate your App password.
- Change Subject of your wish.
