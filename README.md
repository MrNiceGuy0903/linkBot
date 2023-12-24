
# LinkBot

A bot for Hosting Lovense Orgy's And Posting links to control lovense toys in Discord Servers while enableing the Administrator of the server to police links with enforcement of permissions on who can connect to the link Utilizing the Lovense Standard API
## Updates
- Linkbot now has a blocklist option!
- Linkbot has a new option for Re-occuring links! 
## Deployment


 Install Linkbot by inviting it to you server, this is done in 3 different invites
 
[![Standard_install](https://img.shields.io/badge/Link_Bot-Standard_Install-8A2BE2)](https://discord.com/api/oauth2/authorize?client_id=1180169543130300557&permissions=17600776022016&scope=bot)
       Allows the following permissions: Manage Events, Create Events, Send Messages, Manage Messages, Attach Files

[![Standard_install](https://img.shields.io/badge/Link_Bot-Add_Mention_@everyone-8A2BE2)](https://discord.com/api/oauth2/authorize?client_id=1180169543130300557&permissions=17600776153088&scope=bot)
       Allows the following permissions: Manage Events, Create Events, Send Messages, Manage Messages, Attach Files, Mention @Everyone

[![Standard_install](https://img.shields.io/badge/Link_Bot-No_Permission_Install-8A2BE2)](https://discord.com/api/oauth2/authorize?client_id=1180169543130300557&permissions=0&scope=bot)
          This Link Allows No default Permissions- 

# Linkbot command list and permission requirements
## User Commands
### Link's
- ```/droplink``` create a lovense link (with your Name!)
- ```/dropanonlink``` Create a lovense link (without your Name!)
### Orgy Event
- ```/create-orgy``` 	  	 Create an orgy event
- ```/add_word_to_my_orgy``` 	  	 add a new trigger word to your vibe your toy
- ```/cancel-my-orgy``` 	  	 cancels all lovense orgies you created- and invalidates the qr codes
### User Protection
- ```/linkbot-block-user``` 	  	 create a block so that a user may not pick up your link
- ```/linkbot-remove-userblock```	  	 remove the block on a user
- ```/linkbot-show-my-blocks``` 	  	 Shows your blocked user list
## Commands Available for anyone who can setup roles
- ```/linkbot-setup-channel-to-post``` 	 Choose Channel to post Required to Setup in order to post
- ```/linkbot-playroles-add``` 	 Sets Roles that can be mentioned
- ```/linkbot-playroles-list``` 	 Shows a list of the roles that can be selected for links
- ```/linkbot-playroles-remove``` 	 Removes a Role that can be mentioned in links
- ```/linkbot-setup-role-who-can-use``` 	 Setting this will prevent anyone that is not assigned this role from posting
## Administrator Only commands
### Commands Related to user Server wide User blocks
- ```/linkbot-add-server-block``` 	 create a block so that a user may not pick up any links
- ```/linkbot-remove-server-block``` 	 remove the block on a user
- ```/linkbot-list-server-block``` 	 Shows the severs blocked user list
### Link History Related
- ```/linkbot-set-password``` 	 Sets password to reveal link information
- ```/linkbot-get-information``` 	 Gets information on who dropped or grabed a link
### Other Usefull Items
- ```/linkbot-show-users-blocklist``` 	 Shows user blocklist for selected user
- ```/linkbot-admin-cancel-orgy``` 	 Allows An admin To cancel a lovense Event
   
## Deployment

### Required Setup steps
#### Setup Channel for Linkbot to Post
 - using the command ```/linkbot-setup-channel-to-post``` and selecting the channel in your server from the drop down list

#### Setup & edit Roles That may be mentioned/control the toy
- Use the command ```/linkbot-add-playrole``` and select a Role
- A list of roles may by retrieved by using ```/linkbot-list-playroles```
- An unwanted role may be removed by using ```/linkbot-remove-playrole```

### Recomended Setup Steps
#### setup a History Retrieval Password  
- ```/Linkbot-set-password```
                Due to the history of abuse of links between people - we have added a history option for administrators- This option is sensitive and requires extra permissions to run, You must be an admin to request the history and provide the password setup in this step
#### Optional Setup Steps
- The bot allows you to set a required for Posting a link - This is to allow the server administrator to enforce verification, or limit posters in any way they so desire.
                         

    
## Posting Links

Commands ```/Droplink``` (Named)  And ```/Dropanonlink``` (Anonymous)
#### Required Fields 
- "Link" This is the link generated in the lovense app - There is security in this link to ensure the link is pointed to the correct endpoint.
- "Toy" Choose from a drop down what toy you are putting out to be played with
- "Role1" Selects a Role that is allowed to grab the link and be mentioned when the user creates the link
- "Sex" From a dropdown of sex's to choose from to allow the person grabbing the link to know the sex of the person they are playing with
#### Optional Fields -
- "Role 2,3,4" Specifies up to 3 additional roles that will be mentioned and will be allowed to get the link.
- "Reoccurring" if the link is reoccurring it is not removed when the link is claimed
- "Special_Instructions"  Allows a free form place for someone to put free form instructions to be displayed on the link
Anonymous Post:

### Screen shots 
#### Update
-The Screen shots below do not include the new footer that lets users know that admins can pull history, New Screen shots will be up in the future to reflect this change.
#### Anonymous

![App Screenshot](https://github.com/MrNiceGuy0903/linkBot/blob/main/Images/Anonymous-Post.jpg)

#### Named Poster

![App Screenshot](https://github.com/MrNiceGuy0903/linkBot/blob/main/Images/Named-Post.jpg)
## Creating an Event/Orgy

```/create-event```
Required Item "Trigger Word"
 This is the string of characters that when seen will trigger the Orgy to begin.  Then selection begins


#### Step 1: What Kind of Event would you like to have private (just you) or Public so Eveyrone can Join in

![App Screenshot](https://github.com/MrNiceGuy0903/linkBot/blob/main/Images/Start.jpg)

#### Step 2: Would you like a Constant Vibration or A lovense pattern

![App Screenshot](https://github.com/MrNiceGuy0903/linkBot/blob/main/Images/Pattern-Vibe.jpg)

#### Step 3: If you choose a Pattern, What Pattern would you like

![App Screenshot](https://github.com/MrNiceGuy0903/linkBot/blob/main/Images/Choose-Pattern.jpg)


#### Step 3: if you Choose Vibes How Strong?

![App Screenshot](https://github.com/MrNiceGuy0903/linkBot/blob/main/Images/vibes.jpg)

#### Step 4: How long would you like to vibe when someone says the Keyword

![App Screenshot](https://github.com/MrNiceGuy0903/linkBot/blob/main/Images/Pattern-Runtime.jpg)

#### Step 5: How long would you like the event to last?

![App Screenshot](https://github.com/MrNiceGuy0903/linkBot/blob/main/Images/Runtime.jpg)

#### Step 6 Confirmation: Ensure the information is correctly setup as you would like.

![App Screenshot](https://github.com/MrNiceGuy0903/linkBot/blob/main/Images/Private-Confirmation.jpg)

#### Step 7: Event Created
##### Private:
![App Screenshot](https://github.com/MrNiceGuy0903/linkBot/blob/main/Images/Private-Event.jpg)
##### Public:
![App Screenshot](https://github.com/MrNiceGuy0903/linkBot/blob/main/Images/Public-Event.jpg)
## Support

For support, email iamnceguy0903@gmail.com



