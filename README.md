# 🌌 The Maze of Forgotten Paths 

You awaken in a place that feels both infinite and confined.
Stone corridors stretch in all directions, branching into forests, swamps, ruins, deserts, and shadowed halls.
The walls hum with whispers:

``“Three true keys… only then shall the exit open.”``

You do not know how you arrived, but you know this: the maze is alive. It tests, deceives, and tempts with false leads. Some paths are dead ends. Some hold secrets. Others hide traps or illusions. But somewhere, hidden in its folds, are the three real keys that can open the way to freedom.

Your only tool is your command line.
Your only map is your memory.
Your only hope is persistence.

The maze watches.
The maze waits.
Will you escape?

# 🕹️ How to Play

You explore the maze using terminal commands, just as if you were navigating a real filesystem.

# Movement

* ```ls``` → list available paths or items in the current location.

* ```cd <direction>``` → move into that path (e.g., cd north/cave).

* ```cd ..``` → go back one step.

* ```pwd``` → show where you currently are in the maze.

# Reading Clues

* ```cat <file>``` → read notes, hints, or warnings.

* Pay close attention! Clues may point you in the right direction… or lead you astray.

# Collecting Keys

* ```cp keyX.txt <destination>``` → copy a key into the exit chamber (you should fins it).

* Only three true keys will unlock the exit.

* Fake keys (like the one in the dungeon) will be rejected.

# Goal

* Deliver all three real keys into the exit/ folder.

* Once all are there, check the lock with cat lock.txt.

* If successful, freedom awaits!

# Warnings

* Some paths are ***traps*** or ***illusions***. They waste time, but may also contain clues.

* Notes, ruins, and warnings are not always direct—interpret carefully.

## 🎯 Victory Condition

* When all three keys are placed in a chamber exitt and the lock accepts them, the door opens.
<!-- /east/tunnel/chamber/exit/ -->
* You will see a message of triumph:

🎉 Congratulations, you escaped the maze with the true keys!
