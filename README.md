
# LinkBot

A bot for Hosting Lovense Orgy's And Posting links to control lovense toys in Discord Servers while enableing the Administrator of the server to police links with enforcement of permissions on who can connect to the link



## Deployment


 Install Linkbot by inviting it to you server, this is done in 3 different invites
 
[![Standard_install](https://img.shields.io/badge/Link_Bot-Standard_Install-8A2BE2)](https://discord.com/api/oauth2/authorize?client_id=1180169543130300557&permissions=17600776022016&scope=bot)
       Allows the following permissions: Manage Events, Create Events, Send Messages, Manage Messages, Attach Files

[![Standard_install](https://img.shields.io/badge/Link_Bot-Add_Mention_@everyone-8A2BE2)](https://discord.com/api/oauth2/authorize?client_id=1180169543130300557&permissions=17600776153088&scope=bot)
       Allows the following permissions: Manage Events, Create Events, Send Messages, Manage Messages, Attach Files, Mention @Everyone

[![Standard_install](https://img.shields.io/badge/Link_Bot-No_Permission_Install-8A2BE2)](https://discord.com/api/oauth2/authorize?client_id=1180169543130300557&permissions=0&scope=bot)
          This Link Allows No default Permissions- 

    
## Deployment

```bash

  - Required Setup steps
          The First item to setup is the Channel in your server you would like to have links Posted - This is done by using the command "/linkbot-setup-channel-to-post" and selecting the channel in your server from the drop down list

      - Roles That may be mentioned/control the toy
          The Bot is designed to alert people who are a member of the role that the user allows to control their lovense toy, when a user creates a link to be posted - they will specify what roles are allowed to retrieve their link. For this you will use the command "/linkbot-add-playrole" and select a the Role
             - a list of roles may by retrieved by using "/linkbot-list-playroles"
             - an unwated role may be removed by using "/linkbot-remove-playrole"

    - Recomended Setup Steps
      - setup a History Retrieval Password  - "/Linkbot-set-password"
                Due to the history of abuse of links between people - we have added a history option for administrators- This option is sensitive and requires extra permissions to run, You must be an admin to request the history and provide the password setup in this step

    - Optional Setup Steps
      - The bot allows you to set a required for Posting a link - This is to allow the server administrator to enforce verification, or limit posters in anyways they so desire.
                         
```
    
## Posting Links
```bash

  1 "/Droplink" (Named)  And "/Dropanonlink" (Anonymous)
        Required Items - 
            "Link" This is the link generated in the lovense app - There is security in this link to ensure the link is pointed to the correct endpoint.
            "Toy" Choose from a drop down what toy you are putting out to be played with
            "Role1" Selects a Role that is allowed to grab the link and be mentioned when the user creates the link
            "Sex" From a dropdown of sex's to choose from to allow the person grabbing the link to know the sex of the person they are playing with
          Optional Items -
            "Role 2,3,4" Specifies up to 3 additional roles that will be mentioned and will be allowed to get the link.
            "Reoccuring" if the link is reocuring it is not removed when the link is claimed
            "Special_Instructions"  Allows a free form place for someone to put free form instructions to be displayed on the link
```
Anonymous Post:

![App Screenshot](https://github.com/MrNiceGuy0903/linkBot/blob/main/Images/Anonymous-Post.jpg)

Named Post:

![App Screenshot](https://github.com/MrNiceGuy0903/linkBot/blob/main/Images/Named-Post.jpg)
## Creating an Event/Orgy
```bash
"/create-event"
Required Item "Trigger Word"
 This is the string of chars that when seen will trigger the Orgy to begin.  Then selection begins
```


Step 1: What Kind of Event would you like to have private (just you) or Public so Eveyrone can Join in

![App Screenshot](https://github.com/MrNiceGuy0903/linkBot/blob/main/Images/Start.jpg)

Step 2: Would you like a Constant Vibration or A lovense pattern

![App Screenshot](https://github.com/MrNiceGuy0903/linkBot/blob/main/Images/Pattern-Vibe.jpg)

Step 3: If you choose a Pattern, What Pattern would you like

![App Screenshot](https://github.com/MrNiceGuy0903/linkBot/blob/main/Images/Choose-Pattern.jpg)


Step 3: if you Choose Vibes How Strong?

![App Screenshot](https://github.com/MrNiceGuy0903/linkBot/blob/main/Images/vibes.jpg)

Step 4: How long would you like to vibe when someone says the Keyword

![App Screenshot](https://github.com/MrNiceGuy0903/linkBot/blob/main/Images/Pattern-Runtime.jpg)

Step 5: How long would you like the event to last

![App Screenshot](https://github.com/MrNiceGuy0903/linkBot/blob/main/Images/Runtime.jpg)

Step 6 Confirmation: Ensure the information is correctly setup as you would like

![App Screenshot](https://github.com/MrNiceGuy0903/linkBot/blob/main/Images/Private-Confirmation.jpg)

Step 7: Event Created
Private:
![App Screenshot](https://github.com/MrNiceGuy0903/linkBot/blob/main/Images/Private-Event.jpg)
Public:
![App Screenshot](https://github.com/MrNiceGuy0903/linkBot/blob/main/Images/Public-Event.jpg)
## Support

For support, email iamnceguy0903@gmail.com



