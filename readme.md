Ark:SA-Server Installation for Linus using Pterodactyl

 Here is a quick guide to installing an ARK: Ascended server on Linux using Pterodactyl.

This installation assumes you have a dedicated machine with all the required open ports.
Pterodactyl Install
Use the docs here https://pterodactyl.io/project/introduction.html
Install the panel on your machine using the link provided.

Uploading the Egg
Use the link here to create a new egg https://pterodactyl.io/community/config/eggs/creating_a_custom_egg.html

Be sure to allocate the port needed before creating a server.

Create a new server and choose the resources for the server.
I recommend 200% CPU limit (1 core), 12288MiB of memory, and 10240MiB of disk space. For “Nest Config” pick the nest you made and the egg should auto-show up. After that put the required info under “Service Variables” and then click **Create Server**!
 
Now go to the server!
The server should be downloading the files it needs and auto-starting (if you choose that option when creating the server) once that is done, you can click the top tab **Startup** and edit some settings there!

That should be it.

Server Ports
Note: The Peer port must be set and will always be +1 from the Game Port!

Port	Default

Game	7777

Peer (Game+1)	7778

Query	27015

RCON (optional)	37015
