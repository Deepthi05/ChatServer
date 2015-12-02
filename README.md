# ChatServer
Generating a random directed graph
"""
The candidate must implement a rudimentary web chat application based on two simple REST endpoints.
The first endpoint takes a user name and a message to be posted to all users participating in the chat. 
The second endpoint takes just a user name and returns plain text containing all messages posted to the chat that this user 
has not yet received. In other words, this endpoint should only return new messages (delta) posted to the chat by any users since 
the last time it was invoked by the user in question.
The candidate is free to use any web framework to expedite setup and development. 
"""
