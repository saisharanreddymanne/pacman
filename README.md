<h1>Multi-Agent Pacman:</h1>

![image](https://github.com/saisharanreddymanne/pacman/assets/148990776/e0517b54-cef0-4249-93a2-0c83da9b50d6)



First, play a game of classic Pacman:

“ python pacman.py ”

Now, run the provided ReflexAgent in multiAgents.py:

“ python pacman.py -p ReflexAgent ”

Note that it plays quite poorly even on simple layouts:

“ python pacman.py -p ReflexAgent -l testClassic “

Inspect its code (in multiAgents.py) and make sure you understand what it's doing.

Reflex Agent Evaluation Function:
The provided reflex agent code
provides some helpful examples of methods that query the GameState for information. A capable
reflex agent will have to consider both food locations and ghost locations to perform well.
Your agent should easily and reliably clear the testClassic layout:

“ python pacman.py -p ReflexAgent -l testClassic “

Try out your reflex agent on the default mediumClassic layout with one ghost or two:

“ python pacman.py --frameTime 0 -p ReflexAgent -k 1 “

“ python pacman.py --frameTime 0 -p ReflexAgent -k 2 “


Options: Default ghosts are random; you can also play for fun with slightly smarter directional
ghosts using -g DirectionalGhost. 
If the randomness is preventing you from telling whether your
agent is improving, you can use -f to run with a fixed random seed (same random choices every
game). 
You can also play multiple games in a row with -n. Turn off graphics with -q to run lots of
games quickly.
