# Project title - CodeChat
By Yuang Fan, Linjian Li

### What and why?
- This will be a minimal and clean web chat application which provides the feature of sending and displaying nicely formatted code that can be edited and copied while having most features that a classic chat apllication does such as adding friends, creating group chats, sending texts, images, files...
- While there exist platforms such as github that let developers to contribute to the same project and IDEs such as atom or VSCode that let developers work on the same document simultaneously, we feel there is a lack of applications that offer a smooth transition between discussing and sharing relatively smaller pieces of code. Most coding focused forums lack synchronous communication and most chat softwares cannot display code in a satisfying layout like an IDE.
- This is why we would like to create an application that implements a semi IDE within the chat window, offering developers a platform to discuss visualy pleasing code with ease.

### For whom?
The app is mainly targeted at coders who wish to discuss chunks of code.

### How?
- ***User register*** - creating an account with username and password, giving back an UID
- ***User login*** - loging into your own account and receiving new messages
- ***Adding friends*** - search for a friend with their usernmae or UID
- ***Creating and joining group chats*** - user can create group chats and adding their friends into it
- ***Sending messages, images, files*** - just like usual chatting sofwares with a chat box and some options of uploading images and files
- ***Viewing messages*** - messages will appear in a chat browser right above your own chat box
- ***Sending codes*** - there will be a button to turn your text box into a mini IDE that allows you to select the coding language and then you can type or paste the code with the proper colors and layout
- ***Viewing codes*** - codes will appear as normal messages in the chat browser with a block very similar to the code block in Slack, but also the colors and formatts of the language

### Scope
- UI design - minimalistic in general, with extra attention on the mini IDE and display of code in chat browser to make the user experience smooth
- User info - database management of how username, password, friends, groups...
- Code input & visualization - needs support for several language, maybe providing "intellisense"
- Chat functions - how messages and files are exchanged  
  
All of these aspects may need one to two people to work on in order to produce a pleasing result.
