# Barrage
Machine learning Model stealing testing pipeline

# TODO

# Round 0
- train the victim client
- test accuracy
- back door the victim
- test strength of backdoor

# Round 1
- currently this is under construction for a CL watermarking paper
- this will follow the structure of a client-server (But not actually online)
- server will go in rounds
- all clients will connect, and one at a time querry the victim with their image
- server will respond to each client in order (Maybe multithread and queue)
- client will receive the classification of their data from victim model
- pirates will then train 

# Round 2
- we will then test the accuracy of all pirate models
- after testing and comparing accuracy
- we test pirates backdoor accuracy
- check strength of backdoor accuracy
