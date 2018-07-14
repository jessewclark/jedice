# jedice
Slack integration for rolling Star Wars dice

This script is a Lambda function for AWS Lambda meant to be paired with AWS API Gateway and a Slack slash command. If everything goes well,  you should be able to do this:

![alt text](https://github.com/wecter/jedice/blob/master/img/Diceroller_in_action.png)

Ok. Hit Slack and create a App and a Bot User for the App.
https://api.slack.com/apps

Click on the "Create New App" button.


![alt text](https://github.com/wecter/jedice/blob/master/img/Screenshot%202018-07-12%20at%209.48.07%20PM.png)


Give it an awesome name and select your Slack domain as the environment.


![alt text](https://github.com/wecter/jedice/blob/master/img/Screenshot%202018-07-12%20at%209.48.53%20PM.png)

In the left hand navigation bar, choose "Bot Users".


![alt text](https://github.com/wecter/jedice/blob/master/img/Screenshot%202018-07-12%20at%209.49.19%20PM.png)

Click "Add a Bot User".


![alt text](https://github.com/wecter/jedice/blob/master/img/Screenshot%202018-07-12%20at%209.49.37%20PM.png)


Fill out details for the bot user name and click "Add Bot User".

![alt text](https://github.com/wecter/jedice/blob/master/img/addBotUser.png)

After saving the bot, navigate to the Slash Commands on the left nav menu.

![alt text](https://github.com/wecter/jedice/blob/master/img/navToSlashCommand.png)

Click "Create New Command".

![alt text](https://github.com/wecter/jedice/blob/master/img/createNewCommand.png)

Name the command and save it for now. We'll come back for that Request URL field shortly.

![alt text](https://github.com/wecter/jedice/blob/master/img/nameSlashCommand.png?raw=true)




