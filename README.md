# mcconnect
connect minceraft to web interface


## stuff it will do

### admin stuff

send commands to minceraft server to do stuff

-> start/stop servers
-> whitelist new users, ban infracting users
-> execute commands from web console with clusterstorm interface (runs os.system of a command on a separate thread)
-> shows server cmd output to admin login console

### general user stuff

-> links minecraft users to Venkataraman Industries auth system
-> shows server status, map, event board, etc


### chatting

-> shows server chat to logged in (donesnt need to be admin) users
-> users outside server can send chat messages to users in sever through log in interface, shows server chat in website
-> discord integration- certain channel in a linked server where minecraft chat messages in the mc server are sent by the bot, and messages sent in the discord channel by other users are sent in the minecrat server


## Tech Stack

Django backend for webserver, minecraft server thing
bridge between them -> async functions and multithreading
basic html and some css framework for frontend, with some javascript stuff to make map n stuff, and websocket for chat in website
Django-discord integration
discord bot



