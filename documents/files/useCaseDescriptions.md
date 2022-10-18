<h1 style="color:cyan">use case descriptions : game </h1>

<h2 style="color:cyan"> use case: play game</h2>
<h3>Functionality:</h3>
<p>As a Player, I can play the video game</p>

<h3>Normal flow:</h3>
<p>The system displays a play game option. The Actor presses the button to start the video game. The system starts up the video game. The Actor interacts with the system just using one button press.</p>

---

<h2 style="color:cyan"> use case: use menu</h2>
<h3>Functionality:</h3>
<p>As a Player, I can use the game menu</p>
<h3>Preconditions:</h3>
<p>the game must be running</p>
<h3>Normal flow:</h3>
<p>The Actor presses the pause button. The system displays a in game menu which the actor can interact with for through various options.</p>
<h3>Alternatives process:</h3>
<p> <span style="text-decoration: underline">Restart level:</span> if the actor chooses to restart the level, the system will restart the current level the actor is playing </p>
<p> <span style="text-decoration: underline">Select level:</span> if the actor chooses to select the level, the system will open up an menu where the player can choose the level he would like to play</p>
<p> <span style="text-decoration: underline">Quit game:</span> if the actor chooses to quit the game, the system will end the game</p>

---

<h2 style="color:cyan"> (extend) use case: restart level</h2>
<h3>Functionality:</h3>
<p>As a Player, I can restart the current level</p>
<h3>Preconditions:</h3>
<p>The game must be running</p>
<h3>Normal flow:</h3>
<p>The Actor presses the pause button. The system displays a in game menu which the actor can interact with for through various options. The actor chooses the restart level option from the menu. The system will restart the current level the actor is playing.</p>

---

<h2 style="color:cyan"> (extend) use case: select level</h2>
<h3>Functionality:</h3>
<p>As a Player, I can select a level</p>
<h3>Preconditions:</h3>
<p>The game must be running</p>
<h3>Normal flow:</h3>
<p>The Actor presses the pause button. The system displays a in game menu which the actor can interact with for through various options. The actor chooses the select level option from the menu. The system will display a new menu with all the levels. The actor picks the level he likes to play in the list. The system will start the selected level</p>

---

<h2 style="color:cyan"> (extend) use case: quit game</h2>
<h3>Functionality:</h3>
<p>As a Player, I can quit the game</p>
<h3>Preconditions:</h3>
<p>The game must be running</p>
<h3>Normal flow:</h3>
<p>The Actor presses the pause button. The system displays a in game menu which the actor can interact with for through various options. The actor chooses the quit game option from the menu. The system will end the game. </p>
