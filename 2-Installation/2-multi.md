## Network Installation

<br />

**Important:** Before installing, make sure bungeecord is set to true in EVERY spigot.yml

<br />

Firstly install the *UltraPermissions.jar* on every Server including your BungeeCord.
In the next step, you have to enable MySQL for every Server with the ingame GUI.
**Note:** When you have already configuered permissions and groups on a server connect that server first and import its data. Than connect all other server.

<br />

* Execute **/upc addSuperadmin (Your IGN)** via Console to give yourself the ability to access /uperms
* Execute **/uperms**, navigate to *Expand > Settings > MySQL* and enter your MySQL credentials 
* Restart your Server

After you have repeated that process for every Server, Ultra Permissions should now be fully functional!

For the people that have already setup permissions and groups you need to run the folowing command!
**/upc Transfer File MySQL**

If Ultra Permissions did not connect please follow the steps below.

<br />

#### Connecting the Bungee (Proxy)
* Navigate to the Ultra Permissions folder of a connected server
* Enter the files *Registery.json* and copy the the MySQL key
**NOTE:** This key can continue on a second line!
* Navigate to the Ultra Permissions folder on the bungee
* Open the *Registery.json* file and replace the key

The bungee should now been connected to your database.

<br />

In the event that you create a new Server, just repeat the steps. The BungeeCord is configuring itself fully automatically
