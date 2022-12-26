# Salesforce Lightning Component: Whos Viewing My Record
https://github.com/jlondrejcka/Salesforce-Lightning-Component-Whos-Viewing-My-Record　の日本語化

Install via SFDX by downloading this repo:
```
git clone https://github.com/jlondrejcka/Salesforce-Lightning-Component-Whos-Viewing-My-Record-JA
cd Salesforce-Lightning-Component-Whos-Viewing-My-Record-JA
sfdx force:org:create -s -f config/project-scratch-def.json -a "default scratch org"
sfdx force:org:open
sfdx force:source:push
```

Once Installed into your Org:
1. Open the Who's Viewing App to test out.

Add the Component to an Existing App
1. Setup > App Manager.
2. Click Edit next to the Lightning App you would like to add the component too. 
3. Go to Utiltiy Bar settings.
4. Click "Add" next to Utlity Bar Items.
5. Select "whosViewing" under Custom Component.
6. Click "Save".


## Resources
Inspired by the following resources:
* https://github.com/afawcett/streamingcomponent
* https://andyinthecloud.com/2018/02/25/user-notifications-with-utility-bar-api/ 


## Requirements
* Lightning Experience
* Platform Events
* Utility Bar



