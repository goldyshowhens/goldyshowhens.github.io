# Email Setup Instructions


## Gmail Login Alias

You can also setup a google account alias, so that you can login to gmail using the example@goldyshowhens.com by using the following steps:

1.	Go to: https://myaccount.google.com
2.	Click on the `Personal Info` tab at the top of the page.
3.	Scroll down to the `Contact Info` box.
4.	In the `Contact Info` box click the `Email` box.
5.	Click the `Alternate Emails` box.
6.	When prompted, enter your login information to verify it is you.
7.	Click `Add Other Email`
8.	In the pop-up enter `example@goldyshowhens.com`
9.	A verification email will now be sent to your gmail account. Click on the link in the verification email to complete the setup.
10.	You may now login to google using your `example@goldyshowhens.com` email address.


## Gmail.com Setup

In order to send an email as `example@goldyshowhens.net` using a gmail account, you will have to setup google smtp by using the following steps.

#### Step 1: Generate your app password

1. On your computer, go to your Google Account. 
2. At the left, click Security. 
3. Under "Signing in to Google," click App passwords and sign in, if required.
    - If you don't find "App passwords," click 2-Step Verification and follow the steps to turn on 2-step verification for your account. You may have to sign in again.
4. Under “App passwords,” click Select app and then Mail.
5. Click Select device and then Other.
6. Enter the name of your domain and click Generate.
7. From the app password box, copy the 16 character password generated. You'll need this address when you add your new send-as (forwarded) account (in Step 2 below).

#### Step 2: Add an email alias

1.  On your computer, go to Gmail.
2.  At the top right, click Settings Settingsand then Settings.
3.  Select the Accounts and import or Accounts tab.
4.  In the "Send mail as," click Add another email address.
5.  In the window that opens, enter the name you want recipients to view.
6.  Enter the email address alias you’ve set up for email forwarding. 
7.  Confirm that "Treat as an alias" is marked, and click Next step. 
8.  In the "SMTP Server" field, enter: smtp.gmail.com.
9.  From the "Port" menu, choose and then 465.
10. In the "Username" field, enter the username you're signed in with. 
11. In the "Password" field, enter the 16-character generated app password that you copied in Step 1. 
12. Confirm that the Secured connection using TLS box is marked.
13. Click Add account.

#### Step 3: Confirm the address

1. On your computer, go to Gmail.
2. Open the confirmation message you received from Gmail.
3. Click the link. 

#### Step 4: Change the "From" address

1. In your message, click the "From" line.
    - If you don't find the "From" line, click the space next to the recipient’s email.
2. Select the address to send from. 

For more help on how to send email from your email alias in Gmail, visit the Gmail Help Center.


## iOS Email Sendas

It is possible to setup sendas for ios using gmail and the `smtp.gmail.com` sendmail server, 
however, google seems to have recently changed the way that their `smtp` server works,
so that sending mail from iOS no longer works well without a great deal of manual configuration.
