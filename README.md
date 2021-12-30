# simple_chat
simple chat using python socket 


# Relese 0.0.1

here two main files server.py and client.py
 -server.py 
    in server.py imported inbuilt module socket then created socket using socket.AF_INET and socket.SOCK_STREAM
    then binding server to localhost with port 9999
    then listen through server
    and accepting client through server
    if done is false means its not done and msg was quit then it will close the client and server
    if its done == False then it will pass the msg to 
  
 -client.py
    in client.py imported inbuilt module socket and created client socket using socket.AF_INET and socket.SOCK_STREAM
    then bindig client to localhost with port 9999
    if done is false means its not done and msg was quit then it will close the client and server
    if its done == False then it will pass the msg to 
    
   
   here used a utf-8 encoding and decoding method 
