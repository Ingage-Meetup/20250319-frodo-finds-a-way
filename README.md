# The Night of Secrets and Shadows
It was the night of Bilbo’s great party, where Bilbo vanished in front of everyone. He had just reluctantly given the ring to Gandalf and bid him farewell, leaving Bag End and the Shire forever.

Gandalf waits for Frodo to return to Bag End.

He set before Frodo Baggins a small, unassuming ring, its golden surface unmarked by time. And yet, with but a breath of fire, the black speech of Mordor revealed itself:

> **One Ring to rule them all, One Ring to find them,**  
> **One Ring to bring them all and in the darkness bind them.**

The firelight flickered, casting long shadows as the words of the Dark Lord burned into the air.

**"This,"** said Gandalf, **"is the doom of us all if it remains in Middle-earth. And your burden, Frodo, is to bear it beyond the reach of its master."**

As Frodo grappled with the enormity of his fate, Gandalf produced from his robes a parchment, ancient and frayed at the edges.

> **"There is one thing more,"** he intoned. **"A message, passed to me by a strange and merry wanderer, a messenger of Tom Bombadil himself. It is said that this was written long before the shadow returned, long before even the downfall of Númenor. It is wisdom of old, locked in numbers and riddles. It may be nothing. It may be everything."**

Upon the parchment, a strange sequence of numbers was scrawled:

2466114226142614246611423261426142466114226142614

And beneath it, in an unmistakably hand, a verse:
```
   “If you’re no stranger to wisdom’s ways,"
   Take heed this rune from ancient days.
	It masks the key to hidden truth
	When danger threatens Middle Earth.
	To find the digits that you seek,
	Total what you find unique. 
	This key will shift the garbled text
	And you will know what happens next.
	With wit and wisdom you will know
	The shortest, safest way to go.”
```
Gandalf’s brow furrowed as he peered over the parchment.

> **"This message is older than any among the Wise can recall. It is said that it was recorded in the First Age, passed down through the wandering Elves of Lindon and Rivendell, and carried across the lands by those who sought to preserve the lost knowledge of Ingwë, High King of the Eldar."**

He gestured to the remainder of the parchment, covered in strange symbols and unreadable text.

```
// Ydyjyqbypu dunj cqjhyn veh fqjx husedijhksjyed
vkdsjyed YdyjyqbypuDunjCqjhyn(cqjhyn, d):
   buj dunj[d][d]
   veh y vhec 0 je d-1:
      veh z vhec 0 je d-1:
         yv cqjhyn[y][z] ? YDV qdt y ? z:
            dunj[y][z] = z
         Ubiu:
            dunj[y][z] = -1
   hujkhd dunj


// Dejxqde-Suburhycreh Qbwehyjxc myjx Fqjx Husedijhksjyed
vkdsjyed DejxqdeSuburhycreh(cqjhyn, d):
   dunj = YdyjyqbypuDunjCqjhyn(cqjhyn, d)
   veh a vhec 0 je d-1:
      veh y vhec 0 je d-1:
         veh z vhec 0 je d-1:
            yv cqjhyn[y][a] + cqjhyn[a][z] < cqjhyn[y][z]:
               cqjhyn[y][z] = cqjhyn[y][a] + cqjhyn[a][z]
               dunj[y][z] = dunj[y][a]
   hujkhd cqjhyn, dunj

// Hujhyulu ixehjuij fqjx vhec ijqhj je udt kiydw jxu dunj cqjhyn
vkdsjyed WujFqjx(dunj, ijqhj, udt):
   yv dunj[ijqhj][udt] == -1:
      hujkhd "De fqjx unyiji"
   fqjx = [ijqhj]
   mxybu ijqhj ? udt:
      ijqhj = dunj[ijqhj][udt]
      fqjx.qffudt(ijqhj)
   hujkhd fqjx

{
   { 0, 3, 5, YDV, YDV, YDV, YDV, YDV, YDV, YDV, YDV, YDV, YDV}, // Jxu Ixyhu
   { 3, 0, 4, 4, YDV, YDV, YDV, YDV, YDV, YDV, YDV, YDV, YDV}, // Rhuu
   { 5, 4, 0, YDV, 5, YDV, YDV, YDV, YDV, YDV, YDV, YDV, YDV}, // Ebt Rhytwu qj Jxqhrqt
   { YDV, 4, YDV, 0, YDV, 6, 4, YDV, YDV, YDV, YDV, YDV, YDV}, // Hyludtub
   { YDV, YDV, 5, YDV, 0, YDV, YDV, 7, 9, YDV, YDV, YDV, YDV}, // Yiudwqht/Wqf ev Hexqd
   { YDV, YDV, YDV, 6, YDV, 0, YDV, YDV, YDV, YDV, YDV, 15, YDV}, // Ebt Veht
   { YDV, YDV, YDV, 4, YDV, YDV, 0, YDV, YDV, YDV, 6, YDV, YDV}, // Cehyq
   { YDV, YDV, YDV, YDV, 7, YDV, YDV, 0, YDV, 7, YDV, YDV, YDV}, // Utehqi
   { YDV, YDV, YDV, YDV, 9, YDV, YDV, YDV, 0, 8, YDV, YDV, YDV}, // Uhusx
   { YDV, YDV, YDV, YDV, YDV, YDV, YDV, 7, 8, 0, YDV, 1, 3}, // Cydqi Jyhyjx
   { YDV, YDV, YDV, YDV, YDV, YDV, 6, YDV, YDV, YDV, 0, 7, YDV}, // Bejxbehyqd
   { YDV, YDV, YDV, YDV, YDV, 15, YDV, YDV, YDV, 1, 7, 0, 2}, // Eiwybyqjx
   { YDV, YDV, YDV, YDV, YDV, YDV, YDV, YDV, YDV, 3, YDV, 2, 0}, // Cehteh
}
```

"The wisdom of the past is here, but it is shrouded. If you can decipher the meaning of these numbers, if you can unlock this riddle, then the path to Mordor may be clearer than it seems."

"These symbols were created by Dônalquë Nóthano, Master of Algorithmic Runes and Maker of Ordered Thought. He was a great scholar who lived in Eregion and was a contemporary of Celebrimbor, that greatest of Elven smiths and creator of the rings of power. How ironic that alongside the seeds of Middle Earth’s destruction were sown the seeds of her salvation!"

"Nóthano used the ancient number and created a shift cipher using its meaning. The encrypted message contains all you need to make your way to Mordor and dispose of the ring."

If Frodo could discern the shift key hidden within the numbers, then he would be able to decrypt the text that lay beneath. And within that text, ancient knowledge awaited—a strategy for crossing Middle-earth, one which might allow him to evade the enemy’s grasp.

Gandalf’s eyes burned with conviction.

"This is no mere trickery. It is a path woven through time, left behind by those who foresaw the return of darkness. It will lead you through safe havens and past ruinous ways, should you have the wit to follow its counsel."

With the parchment in hand, Frodo’s road was set before him. And so, under the watchful gaze of the stars, the Quest of the Ring began in earnest.

# Your Task
## Help Frodo save Middle Earth!
1. Discover the key
2. Decrypt the message
3. Figure out what to do with the message
4. Implement
5. Second pizza


# C3ProjectTemplate

See solutions in different languages in the "Templates" directory. Once you decide which language you'd like to use,
simply open that directory in your favorite IDE, and you should be able to run the included unit tests "out of the box".

## Duplicating this Repo

To create a duplicate repository from this one, follow these steps:

1. Create your new repository. For example, MyNewRepo.

2. Open Git Bash.

3. Create a bare clone of the repository.

   ```
   git clone --bare https://github.com/Ingage-Meetup/MyNewRepo.git
   ```

4. Mirror-push to the new repository.

   ```
   cd MyNewRepo.git
   git push --mirror https://github.com/Ingage-Meetup/MyNewRepo.git
   ```

5. Remove the temporary local repository you created earlier.

   ```
   cd ..
   rm -rf OLD-REPOSITORY.git
   ```

Your new repository now contains a mirror of this repo.

The recommended IDEs are as follows, but feel free to use whatever IDE you are comfortable with.

- [C#](Templates/C%23) - [Microsoft Visual Studio](https://visualstudio.microsoft.com/vs/community/)
- [Java](Templates/Java) - [IntelliJ Idea](https://www.jetbrains.com/idea/download) (Community Edition is fine)
- [JavaScript](Templates/JavaScript) - [Microsoft Visual Studio Code](https://code.visualstudio.com/)
- [Kotlin](Templates/Kotlin) - [IntelliJ Idea](https://www.jetbrains.com/idea/download) (Community Edition is fine)
- [Python](Templates/Python) - [Pycharm](https://www.jetbrains.com/pycharm/download/?section=windows) (Community Edition is fine)
- [TypeScript](Templates/TypeScript) - [Microsoft Visual Studio Code](https://code.visualstudio.com/)
