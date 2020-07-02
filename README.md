![title](C:\Users\alber\OneDrive\Desktop\SANTORINI IMAGES\title.png)

Welcome to Santorini, a Cranio Creations game adapted by Tavini, Reale and Saputelli (GC27)



What we chose to implement was:

![regole complete+cli+gui+ecc.](C:\Users\alber\OneDrive\Desktop\SANTORINI IMAGES\regole complete+cli+gui+ecc..PNG)

In particular for advanced functionalities we opted for:

- Multiple matches

- Advanced Gods (Hestia, Ares, Triton, Zeus, Chronus)



Additional features

- Serialization and Deserialization of Gods from Json File, with the possibility to insert personalized decks of gods

- A chat that players can use while playing with the GUI 

- In addition to the type of lobbies required from specification (that we called Casual) we give the possibility to create and join public and private lobbies with name and eventually a password



By considering only the classes for which testing was required, these are the general reports on coverage of tests:

![coveragetest](C:\Users\alber\OneDrive\Desktop\SANTORINI IMAGES\coveragetest.PNG)



**INSTRUCTIONS**

In the folder with the Jar files you will find the .bat to allow the game to run on local host. In particular the Server has an optional argument which is a path for saving a logfile (if not used, the server simply won't print any log) and the Client will take "c" or "g" as first argument to decide wheter you want to play with CLI or GUI, while the second argument is the IP address to which it will connect (in the .bat we used 127.0.0.1).