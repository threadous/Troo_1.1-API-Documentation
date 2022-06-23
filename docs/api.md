# Troo 1.1 API Documentation

## Script Commands

This section contains commands to create a script, parent and name it. <br></br>
All script commands follow the same format and order `parent.class.name`. **TO ADD LOCAL SCRIPT INSTEAD OF A REGULAR SCRIPT, USE `lscript` AS CLASS INSTEAD OF JUST `script`** <br>
A **name** parameter is **mandatory**

<h3>QUICK TIPS</h3>

Whenever using these commands, the parent parameter will always be a `Service`, such as `ServerScriptService`, `ReplicatedStorage` etc. When denoting them in the parent parameter, if the service is only one word, it is usually denoted by its starting letter. If the service contains more than one word, the parameter is usually the short form. If it does not work, please review the full API Documentation below for the correct command. 

<h3>Creating A Script For Workspace</h3>

• `wcript/TrooTest` <br>
• The following command creates a new script in workspace called `TrooTest`

<h3>Creating A Scipt For Players</h3>

• `pscript/TrooTest` <br>
• The following command creates a new script in Players called `TrooTest`

<h3>Creating A Script In Lighting</h3>

• `liscript/LightingScript` <br>
• The following command creates a new script in Lighting called `LightingScript`

<h3>Creating A LOCAL Script In Replicated First/Storage</h3>

• `repFlscript/MyScript` <br>
• The following command creates a new script in Replicated First called `MyScript` <br>
🔑 The parent command is `repF`, denoting `Replicated` (rep) and `First` (F) and the class is a local script, so is the reason for `lscript`. Use `repS` for Replicated Storage

<h3>Creating A Script In Server Script Service</h3>

• `serverscript/MyScript`

<h3>Creating A Script In Server Storage</h3>

• `sstoragescript/MyScript`

<h3>Creating A Local Script In StarterGui</h3>

• `GUIlscript/MyScript`

<h3>Creating A Script In StarterPack</h3>

• `spscript/ToolScript`

<h3>Other Services</h3>

Troo Version 1.1 is compatible with the above Services only.




