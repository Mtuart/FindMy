# FindMy

Addon for the Vehicles Plugin (made by Pollitoyeye), which allows you to find your Vehicles again!

---
### How to install:
> Step 1:
  Get Vehicles 13.6.2 (or higher) and at least Paper 1.17
  
> Step 2:
  Toss the jar file into your /plugins folder. (Download it by clicking on the "Releases" Tab on the right >)
  
> Step 3:
  Have everything installed and start your server.
  
> Step 4:
  Start losing your Vehicles!
  
---
### Features:
- Find all your Vehicles again!
- Limit the search to specific Vehicles!
- Search Vehicles from other people!
- Click the locate/teleport/move/pickup!
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
```

---
### Config:
```
AutoCompleteSettings:
  listOfflinePlayers: false  > If the Autocomplete shall display offline players too (USE WITH CAUTION ON LARGE SERVERS!)
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
VehicleTeleport 1.0+ (Will receive rework soon and is already integrated into FindMy)
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
  - This is a premium freeware addon in my eyes... Meaning that I spent so much time to work on this, it makes it fairly unique currently.
  
- **What are you working on?**
  - Make GUI using easier.
