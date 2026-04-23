# GDIM 33 In-Class Activities
## W1
### Activity 1
Put your inspo board link here. Do NOT leave a bare URL. REMOVE ALL INSTRUCTIONAL TEXT.

[inspo board](https://docs.google.com/drawings/d/1NBVLU4cgm-I5z3xeXDWoZHF7FU9SQAYL-yKoIxd6QZg/edit?usp=sharing)

1. Merging machanics, have some sort of upgrade system (e.g home, pets, romance charactor), puzzler
2. Action games, rpgs.
3. Likes merging machanic. Likes rpgs.

### Activity 2
[break-down](https://docs.google.com/drawings/d/1VlxVvg0mTTwS7AS_746No2ra2WYkIBEiiZcvD8d0nSM/edit?usp=sharing)


## W2
Pushed to github.

Continue adding additional headers below this one for future weeks and future activities.


## W3
### Activity 1 
[BreakDown](https://github.com/user-attachments/assets/295d21c1-968a-4856-870b-17687ddc7d34)

### Activity 2
1. Why is it advantageous to save the event name for the explore-to-dialogue state transitions as Scene variable ("clickNpcEventName")?

The Scene Variable can be accessed by the state machine on another game object that is calling the event. It is faster to drage in and avoid human typing error.

2. Describe how using at least one Debug.Log() node helped you test your Graphs at an intermediate step.

It helps me locate where the problem is comming from. When I am testing the tranfition to dialog state, the debug in transition is not showing up while the debug before calling the event does. So I only need to check why the transition is not called.

3.Is the Set Cursor Lock State relevant to your Vertical Slice? Why or why not?

No because my vertical Slice is a 2D platformer that does not use cursor.

4. Is the concept of a "game state" relevant to your Vertical Slice? Why or why not?
Yes. Because I am also implementing dialogue in the game where I want to lock player movement.


## W4
### Activity 1
Playable: Player can move around in 2D room space, there is an opening dialogue with 4 lines and an interactable object in the room. The dialogue will prompt the player to interactable and open up a crafting UI Canvas. Player can drag 3 types of items in 4 slots in this canvas, if player follow prompt to drag them in right order, it will crete target item and advance ending dialogue with 4 lines. After that the player will switch to next room scene.

Play Test Goal: Test if basic movement and crafting system work. Test if dialogue introduce the setting clearly and get feedback on whether its interesting. 

Play Test Notes: Interactable object use [E] and need a clear indecation for it or add other keys(player often try space/mouse/enter first). Some typo in dialogue but overall understandable and interesting(wants to learn more about who is him, why MC wants to forgot, how we get the recipe, and is there other costs to forget). Crafting System icon and background need polish but code work in different situations. Player movement need polish (jump in arrow keys, lock rotation). Maybe add paralax background as a cool effect later. The second puzzle (from classic math questions, not in build yet but tested on paper with 6 people) is interesting  yet hard (2 give up after 5 minute, fastest solve 10 minute, longest 25 minute).

