## Network Installation

<br />

**Important:** Before installing, make sure bungeecord is set to true in EVERY spigot.yml

<br />

Firstly install the *UltraPermissions.jar* on every Server including your BungeeCord.
In the next step, you have to enable MySQL for every Server via the intuitive interface.
**Note:** If you already have permissions connect the server with permission first!

<br />

* Execute **/upc addSuperadmin (Your IGN)** via Console to give yourself the ability to access /uperms
* Execute **/uperms**, navigate to *Expand > Settings > MySQL* and enter your MySQL credentials 
* Restart your Server

After you have repeated that process for every Server, Ultra Permissions should now be fully functional!
If UltraPermissions did not connect please follow the steps below.

<br />

#### Connecting the Bungee (Proxy)
* Navigate to the UltraPermissions folder of a connected server
* Enter the files *Registery.json* and copy the the MySQL key
**NOTE:** This key can continue on a second line!
* Navigate to the UltraPermissions folder on the bungee
* Open the *Registery.json* file and replace the key

The bungee should now been connected to your database.

<br />

In the event that you create a new Server, just repeat the steps. The BungeeCord is configuring itself fully automatically
