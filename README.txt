# Introduction

This chat application is built on a peer-to-peer architecture, ensuring direct and efficient communication. For secure user authentication, it employs the Mutual Challenge Handshake Protocol (CHAP). Each message is encrypted with a unique key, safeguarding every interaction and setting a high standard for security.

---------------------------------
# Steps

Step 1: run new_server_client.py on 2 terminals
Step 2: enter server port 1234 on 1st terminal and username user1 and password 123
step 3: enter server port 4321 on 2nd terminal and username user3 and password 123
Step 4: enter id 3 on 1st terminal and id 1 on 2nd terminal
Step 5: press enter and start sending messages
Step 6: all pdu's are logged with its username(use3.txt and user1.txt) as filename --->(only server logs the info)
Step 7: all connection requests and socket info are logged in main_file_log.txt
