![alt tag](http://challengepost-s3-challengepost.netdna-ssl.com/photos/production/software_photos/000/288/091/datas/gallery.jpg)

# Potter League
#####What is Potter League?

Potter League is an exciting combination of the hit game Rocket League and the game Quidditch from the fairly well known series Harry Potter. In Potter League, you may play as Harry, Ron, Hermione, or the Dark Lord himself, flying around on your broomsticks, trying to score in the opposing goal.    

#####What makes Potter League so Amazing?

In Potter League, all of your flying motion is done through you phone. The accelerometor data from your phone is sent through Socket to a private server that the Unity enginge is running on. This allows you to truly feel like you are controlling the flight of your character directly.  

#####How does this work?

The main part of the game was made in the Unity game engine. All movements and game objects were created and animated in the engine. Using an API provided by EA (Electronic Arts), I was able to use NodeJS to pass JSON data from a webpage to Unity. I then tracked the user's accelerometor data from their phone and calculated a direction and speed for their player.

***

#####Built With:

unity c# javascript html5 json jquery node.js eapathfinders-api
