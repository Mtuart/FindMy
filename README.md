# FindMy

Addon for the Vehicles Plugin (made by Pollitoyeye), which allows you to find your Vehicles again!


** Plugin is no longer maintained **

---
### How to install:
> Step 1:
  Get Vehicles 13.6.2 (or higher) and at least Paper 1.17
  
> Step 2:
  Remove the old jar and folder and toss the new jar into your /plugins folder.
  (Download it by clicking on the "Releases" Tab on the right >)
  
> Step 3:
  Have everything installed and start your server.
  
> Step 4:
  Start losing your Vehicles!
  
---
### Features:
- Find all your Vehicles again!
- Limit the search to specific Vehicles!
- Search Vehicles from other people!
- Click to locate/teleport/move/pickup!
- Easy handling through a GUI!
- Easy Commands with TabComplete!
  
---
### Commands and Permissions:
```
/FindMy
/FindMy All                    > findmy.all
/FindMy <Vehicle>              > findmy.own
/FindMy All <Player>           > findmy.othersall
/FindMy <Vehicle | All> All    > findmy.everyoneall
/FindMy <Vehicle> <Player>     > findmy.others
/FindMy reload                 > findmy.reload
/FindMy id                     > findmy.id

Click to Teleport              > findmy.teleport
Click to Locate                > findmy.locate
Click to Remove                > findmy.remove
Click to Move                  > findmy.move
Click to Pickup                > findmy.pickup

Use the GUI                    > findmy.gui

All permissions                > findmy.*
```

---
### Config:
```
AutoCompleteSettings:
  listOfflinePlayers: false  > (USE WITH CAUTION ON LARGE SERVERS!) If the Autocomplete shall display offline players as well
GUISettings:
  useGUI: true               > Enable the GUI
LocateSettings:
  enable: true               > Enable the function to locate a Vehicle
  enableActionBar: true      > Enable the actionbar feature during locating.
TeleportSettings:
  enable: true               > Enable the function to teleport to a Vehicle
RemoveSettings:
  enable: true               > Enable the function to remove a Vehicle
PickupSettings:
  enable: true               > Enable the function to pickup a Vehicle
MoveSettings:
  enable: true               > Enable the function to move a Vehicle
```

---
### Dependencies:
```
(Hard)
Paper 1.17+
Vehicles 13.6.2+

(Soft)
PlaceholderAPI 2.11.2+
```

---
### Placeholders:
```
%findmy_TotalServer%  > Total Vehicles placed on the Server
%findmy_TotalPlayer%  > Total Vehicles placed by the Player
%findmy_GPS%          > Vehicle Type which is currently being located
%findmy_Direction%    > Direction towards located Vehicle
%findmy_Distance&     > Distance to the located Vehicle
```

---
### FAQ:
- **Why is there no config to edit the messages?**
  - Might follow in another update.

- **Why did you not upload the source code?**
  - Currently decided to not upload the source code.
  
- **What are you working on?**
  - Make GUI using easier.
