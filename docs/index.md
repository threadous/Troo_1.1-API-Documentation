# Troo 1.1 API Documentation

## Script Commands

This section contains commands to create a script, parent and name it. <br></br>
All script commands follow the same format and order `parent.class.name`. **TO ADD LOCAL SCRIPT INSTEAD OF A REGULAR SCRIPT, USE `lscript` AS CLASS INSTEAD OF JUST `script`** <br>
A **name** parameter is **mandatory**

<h3>QUICK TIPS</h3>

Whenever using these commands, the parent parameter will always be a `Service`, such as `ServerScriptService`, `ReplicatedStorage` etc. When denoting them in the parent parameter, if the service is only one word, it is usually denoted by its starting letter. If the service contains more than one word, the parameter is usually the short form. If it does not work, please review the full API Documentation below for the correct command. 

<h3>Creating A Script For Workspace</h3>

• `w script/TrooTest` <br>
• The following command creates a new script in workspace called `TrooTest`

<h3>Creating A Scipt For Players</h3>

• `p script/TrooTest` <br>
• The following command creates a new script in Players called `TrooTest`

<h3>Creating A Script In Lighting</h3>

• `li script/LightingScript` <br>
• The following command creates a new script in Lighting called `LightingScript`

<h3>Creating A LOCAL Script In Replicated First/Storage</h3>

• `repF lscript/MyScript` <br>
• The following command creates a new script in Replicated First called `MyScript` <br>
🔑 The parent command is `repF`, denoting `Replicated` (rep) and `First` (F) and the class is a local script, so is the reason for `lscript`. Use `repS` for Replicated Storage

<h3>Creating A Script In Server Script Service</h3>

• `server script/MyScript`

<h3>Creating A Script In Server Storage</h3>

• `sstorage script/MyScript`

<h3>Creating A Local Script In StarterGui</h3>

• `GUI lscript/MyScript`

<h3>Creating A Script In StarterPack</h3>

• `sp script/ToolScript`

<h3>Other Services</h3>

Troo Version 1.1 is compatible with the above Services only.


## Parenting Index

The above examples for the different parenting types was just as an introduction. It is better to memorize the parenting commands for easier use. For now onwards, usage of parent commands will be direct. There will be a space after each parenting command to denote the begining of the next command.

`w : workspace` <br>
`p : Players` <br>
`li : Lighting`<br>
`repF : ReplicatedFirst`<br>
`repS : ReplicatedStorage`<br>
`server : Server Script Service`<br>
`sstorage : Server Storage`<br>
`GUI : StarterGUI`<br>
`sp : StarterPack`<br>

## Organization Commands

This section contains commands which can be used to organize items in the explorer window. Such as creating folders and arranging children of folders. Please read the full API Documentation before proceeding and using commands.

<h3>Creating A Folder</h3>

Most commands are similar to the script commands. To create a folder and parent it ReplicatedStorage and name it as "Events", use the following command. <br>

• `repS folder/Events` <br>

<h3>Create a New Folder With Children</h3>

Instead of using two different commands to create a folder and then parent something else to it. Troo gives you the option to create a folder with pre-existing children. <br>

• `repS folder/Events MyScript:PetHandler:RemoteEvent` <br>

In this case, the example shows the addition of 3 children to the folder namemly, `MyScript`, `PetHandler` and `RemoteEvent`. They are divided by `:`. Caution is recommended before proceeding with this command as it will parent anything that has the same name given into the folder. Most actions are irreversible.

<h3>Removing And Adding An Object From A Folder</h3>

The current version of Troo does not support this feature yet, it may be introduced in the future.

<h3>Creating A Remote Event</h3>

You may use the Parenting Index provided as the first argument. <br>

• `repS re/PetEvent` <br>

<h3>Creating A Remote Function</h3>

• `repS rf/NewFunction` <br>

<h3>Creating A Module Script</h3>

• `repS module/PetModule` <br>

## Troo 1.1

Troo 1.1 was created on June 23rd, 2022 for the usage of all commercial and non-profit **creations**. <br>
