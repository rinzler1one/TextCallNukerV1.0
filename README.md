# TextCallNukerV1.0
A console application that I created in Java that can spam US phone numbers with texts and calls by the number of texts/calls, minutes, or indefinitely using Twilio.
In order for this application to work in your IDE, you must add the twilio dependencies jar file to your project as a dependency. The file can be found in the TwilioDependencies folder on my github. You must have a Twilio account that is upgraded and not a free trial account in order to send texts and calls to any US phone number without verifying first. This project was created for educational purposes. I am not responsible for any damages or consequences that results from the use or misuse of this application. Please do not use this to harass or annoy others.

This console application uses a third party library provided by Twilio to send text messages and calls to US numbers. In order to use this application, you have to first create an account on twilio.com and once created, you will receive an account SID and account auth token. These two pieces of information are needed for this application to work. After receiving your account SID and account auth token, you will be provided a Twilio phone number and you also have the option in buying more Twilio phone numbers. This application relies on your Twilio phone number to send texts and calls. Please note that free trial Twilio accounts can only send texts and calls to verified target numbers. To remove this restriction, upgrade your Twilio account and you can send texts and calls to any US number without having to verify that number first.  

In this application, the source number is your Twilio phone number. The target number is the number you want to spam with texts or calls. You can spam the phone number with a text or call and there are three options in the length of time for spamming: Spam by number of texts, spam indefinitely, spam by number of minutes. Spam by number of texts means you input the number of texts that you want to spam. Spam indefinitely is the app will keep sending the texts until you close the app. Spam by number of minutes will prompt you to enter how many minutes you want to spam the number. The same is true for spamming with phone calls.

Once you add the account SID, account auth token, source numbers, and target numbers, you have the option to add the these information on seperate text files called 'account.txt', 'sources.txt', and 'targets.txt'. These text files will be created in the same directory as this project's .java file.

If for some reason your account SID, auth token, or source phone numbers don't work anymore or your account has been suspended, you will not be able to send texts or calls and there will be an error message that will let you know if that occurs. If the US number that you are sending texts or calls to blocks your source number, then the text or call will not get through.

Feel free to make changes to this application and improve it!




