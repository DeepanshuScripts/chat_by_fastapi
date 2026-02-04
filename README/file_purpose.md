# main.py
→ It is the entry point of fastapi.
→ Combination of Django → urls.py + settings.py
→ the app starts,routes are registered
→ middleware and authentication
→ websocket routes beacome active
→ router - group of endpoints 
→ websocket endpoints - chat live here

# websocket.py – Connection manager
→ It works like all connnection admin
→ where connection get connect, disconnect, send_message
→ Keeps track of who is online
→ Knows who joined
→ Knows who left
→ Sends messages to everyone or one person
