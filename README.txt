README:


FILE CONVERSION:

--------------------------------------------------

AIConsulPY.txt: TURN THIS INTO A PYTHON SCRIPT

CombinedPy.txt: TURN THIS INTO A PYTHON SCRIPT

FolderSpawnerSH: TURN THIS INTO A BASH SCRIPT

---------------------------------------------------

WORDLIST STRUCTURING:

It is important to understand that the two primary goals
of this "repository" or "package" (I have no idea how to
do this github thing):

1.) Organize Folder structure for Penetration Testing Practice

2.) Use an AI as an assistant if asked

---------------------------------------------------

Use PENTESTPHASES.txt as your MASTER FOLDER

Write as many folder titles as you would like, with a line skip (enter) 
between each, and whatever you find fit.

The goal is to take pentration testing phases, spawn their respective folders,
then spawn folders of tools that would be used in them.

---------------------------------------------------

SPAWNING TOOLS IN RESPECTIVE FOLDERS:

Each tool list must be titled "wordlist_(TITLE).txt" with TITLE 
being replaced by the title in your MASTER FOLDER text file.

This will tell the script what folders to spawn in where.

---------------------------------------------------

AI USE CASE:

CombinedPy utilizes the OpenAI API key to read the output
from files generated in the Folder tree, and interprets them
automatically.

THEN after doing the above, it gives you the option to choose 
any files to be read outloud with ELEVENLABS API.

----------------------------------------------------


TIPS AND TRICKS FOR AI USAGE:

- UTILIZE THE PROMPT: You can go into the Combined.Py file and edit the prompt
			to your liking. This can have an effect on personality,
			if using ElevenLabs, among other effects. Adjust this to
			your liking, especially if you are a hacker don't come
			crying to my repo about "what prompt" - Try Harder ;).

----------------------------------------------------

Basic usage:

1.) Spawn Folder(s) using FolderSpawner.sh

2.) Do your duties as a pentester, output files into
	their respective folders

3.) Run AI Assistant if desired
	- python3 Combined.py

----------------------------------------------------


Good Luck! Have Fun!


