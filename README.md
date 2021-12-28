<h1>README for Escape the Dungeon!</h1>

<h2>About</h2>
Escape the Dungeon! finally provides graphical user interfaces with a bunch of new features to make the game more interesting! Play the game and you will see what the author offers you. 

<h2>List of features</h2>
1. Newly developed graphical user interfaces. 
2. Highly customizable game settings. 
3. Support all original features such as shooting arrows and collecting pieces of treasure. 
4. [!EXTRA!] I add two-way portals in the map so that player can enter the portal and be teleported to somewhere else.
5. [!EXTRA!] I add magic scrolls shop in the game so that player can use magic scrolls to light up 5 * 5 surroundings. Player can buy magic scrolls using pieces of treasures collected in the dungeon. 

<h2>How To Run</h2>
java -jar project5.jar

<h2>Description of Examples</h2>
I highly recommend you play this game. The game offers user-friendly instructions and statistics. 
You can check my video demo later. 


<h2>Design Changes</h2>
1. Add a whole bunch of pop-up windows to make the game more user-friendly and interesting. 

<h2>Assumptions</h2>
1. Smell does not reduce in tunnels. 
2. Shooting distance is auto-calculated by (3 - smellLevel), which is always correct. 


<h2>Limitations</h2>
The java swing has some lagging when replacing image icons for a large amount of labels. When the player kills a monster, the "smell" of the whole map is re-calculated and the images are replaced, which might cause some latency in displaying the updated images.  

<h2>Citations</h2>
I used this CompoundIcon.java written by Rob Camick in the following website to facilitate the process of multiple images on Z-Axis: https://tips4java.wordpress.com/2009/03/29/compound-icon/