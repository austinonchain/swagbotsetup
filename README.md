# swagbotsetup
This is a guide for setting up the swag bot on Twitter
## Twitter Developer Account
In order to use the swag bot, you'll need a dedicated Twitter account with Elevated API Access. Here's how to do that.
1. Create new account
2. Visit (https://developer.twitter.com) and sign up
3. Fill out all the required information to get Essential Access
4. Once you have Essential Access, you have to apply for Elevated Access
5. Elevated access requires filling out more detailed questions. Save your answers somewhere because they will most likely email you asking the same questions.

After applying, it will usually take a day or two to get access. Once you get Elevated Access move on to the steps below.
## Twitter API Keys
Now that you have a new Twitter accout with Elevated API Access, you'll need to get all the required API keys and tokens.
You will need the **Bearer Token, API Key and Secret,** and the **Access Token and Secret**.
1. On the left sidebar, click Projects & Apps > Overview.
2. Click Add App and set it to Production. Click Next
3. Choose a Name. Click Next
4. On the next screen you'll see the Bearer Token and API Key/Secret. **Don't save these**.
5. Click App Settings at the bottom.
6. Scroll to the bottom of the page and click the Set Up button under **User authentication settings**  
7. Turn on **OAuth 1.0a** only
8. Under App permissions, choose **Read and write**
9. For the Callback URI and Website URL, just put your project's website.
10. Click Save and Yes to change permissions

Now you should be back to your App Settings page. Click "Keys and Tokens" at the top.
1. Under Consumer Keys, click regenerate and save the new API Key and API Secret somewhere.
2. Under Authentication Tokens, click regenerate next to Bearer Token. Save it.
3. Next to Access Token and Secret, click generate and save it.

