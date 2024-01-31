# A simple clone of Flappy Bird
To start learning Unity, a very simple clone of Flappy Bird, following the Game Makers Toolkit tutorial on [YouTube](https://www.youtube.com/watch?v=XtQMytORBmM)

~~ A rather weird thing happened. I set a variable (float) on PipeMove called deadZone to -45. Realised this was too high so changed it to -30.
 It was still using the value of -45 in the debug log.

 I had to create a new variable and use that one. Unity might be cacheing it somehow? ~~

 When updating a script attached to a prefab - you may need to force the prefab to update.
