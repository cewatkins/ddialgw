# ddialgw
ICB to IRC to ddial via libre
The questions to do code.

write a ICB to IRC gateway
add logging
add connection testing and retry
change icb_server to "default.icb.net"
change irc_channel to "#drmad"
change irc_server to irc.libera.chat
start irc first and log each message sent accross gateway
Error receiving from ICB: 'utf-8' codec can't decode byte 0x8b in position 0: invalid start byte. Reconnecting...
confirm nickname is set on icb server and message is sent to irc server
confirm login to icb and join channel #drmadicb
# So here's were i upload icb.py rather than pasting here. I said
use this code example as icb client part.  ## icb connection object
# This is because it wasn't logging into icb right
# then chatgpt forgot the rest of the chat so i don't have it, wasn't a whole lot.
ModuleNotFoundError: No module named 'icb_connection'
#I did this so it was in a seperate file and didn't import icb.py cause of matching code.
it imported it, but this isn't everything but should work this way.
#it's answer I have removed the external module import and integrated the IcbConn class directly into your code to prevent the ModuleNotFoundError. Let me know if there's anything else you'd like me to adjust!
