## Commands

* **/uperms** to open the Administrative GUI
  (Requires to have *superadmin access*)
  
<br />

### Other Commands
* **/upc AddGroup (User) (Group)** *Options..*
* **/upc AddGroup (User)) (Group) (Optional Operator: "+" or "-")** *Options..*
* **/upc AddGroupPermission (Group) (Permission)** *Options..*
* **/upc AddPlayerPermission (User) (Permission)** *Options..*
* **/upc AddSuperAdmin (User)**
* **/upc DeleteGroup <Group>**
* **/upc PurgeGroup (Group)**
* **/upc PurgeGroupPermission (Permission)**
* **/upc PurgePlayerGroups <User>**
* **/upc PurgePlayerPermission (Permission)**
* **/upc PurgeSuperAdmins**
* **/upc RemoveGroup (User) (Group)**
* **/upc RemoveGroupPermission (Group) (Permission)**
* **/upc RemovePlayerPermission (User) (Permission)**
* **/upc RemoveSuperAdmin (User)**
* **/upc RestrictGroupToWorld <World>**
* **/upc SetGroups (User) (Groups..)**
* **/upc SetPlayerPrefix (User) (Prefix)**
* **/upc SetPlayerSuffix (User) (Suffix)**
* **/upc Transfer (File/MySQL) (File/MySQL)**
* **/upc AddGroup <Player> <Group> <Optional Operator: "+" or "-"> <Time>**
* **/upc createGroup <groupName>**
* **/upc setGroupPriority <Group> <Priority>**
* **/upc SetGroupPrefix <Group> <Prefix>**
* **/upc SetGroupSuffix <Group> <Suffix>**
* **/upc PurgePlayerGroups <User>**
* **/upc DeleteGroup <Group>**
* **/upc SetGroupPrefix <Group> <Prefix>**
* **/upc SetGroupSuffix <Group> <Suffix>**
* **/upc deleteUser <User>** (Deletes all data of this player)
* **/upc TransferAccount <All/Groups/Permissions> <Append/Overwrite> <From> <To>** (Transferes the selected data (all (=group & permissions), groups, permissions) from user (<From>) to user (<To>). If **Append** is selected the transferred files will be appended to the existing datas of <To>. If **overwrite** was seleceted... the groups and permissions of <To> will be deleted and then the datas of <From> will be added. The Datas of <From> (groups & perms) will be deleted in every case

### Options
* Timed Options e.g ``3d`` or ``20h 4m``
* Server Options e.g ``lobby``
* World Options e.g ``world_nether``

<br />

These commands are mainly added for automation since everything can be controlled more conveniently through the GUI.

<br>

If you still want to use those commands manually, you will need to have *superadmin access*
