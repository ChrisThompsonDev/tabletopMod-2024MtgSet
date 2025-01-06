![Screenshot](/images/coverImage.png)

# Introduction

This is a mod for Tabletop Simulator that provides players with everything Magic The Gathering released in 2024! There is something here for every magic fan. Whether you want to play with a Commander Precon, 

# Check Out the Live Application!

If you don't have tabletop simulator already on Steam, you will need to purchase it to see everything in action. Once you own the game, follow these steps to install the mod:

Simply go to the [Workshop page and subscribe to the mod](https://steamcommunity.com/sharedfiles/filedetails/?id=3401546551). 

![Subscribe Button](/images/workshopSubscribe.png)

When you open the game, greate a singleplayer game.

![Create Game Button](/images/createGame.png)
![Single Player Button](/images/singlePlayer.png)


Go to the Workshop section and launch the mod. 
![Workshop Button](/images/workshop.png)

![Mod Button](/images/selectMod.png)


You can then right click on the objects and save them. You will then be able to use the saved objects in any environment/mod in the game!



---

> Be sure to add that lovely star 😀

---

## How Everything Works:

# Deckboxes
Each Deckbox is dedicated to an individual set. So let's grab the Fallout deckbox and take a look! Simply Click on the box and hold. YOu will then be able to move the box around freely. 

You will see that the box is labeled for the "Complete Set". 
![Fallout Complete Set](/images/falloutSet.png)

Now if you click/hold (quickly) and pull away from the boox you will remove the first of it's contents. 

The first thing that you will remove is the Commander Precon Deck Set. This box has all 4 Commander decks released with the Fallout theme. Dragging out it's contents you will see each set individually with their own custom deckboxes. And inside each of those is a bag of gameplay tools, token cards, your Commander and the rest of the deck. 

![Fallout Commander Set](/images/falloutCommanderSet.png)
![Fallout Commander Decks](/images/falloutCommanderDecks.png)

If we put away the commander decks, you can continue to pull items out of the Complete Set box.

Next you will find the various Token cards you may need when playing with this set. 

Then, finally, you will pull out a stack of 1068 cards. These are all of the cards in the set. 

You can save the entire set, or a single Commander deck. It's up to you!


# Booster Boxes
I wanted to recreate the booster box experience as best as possible. So [I found a mod](https://steamcommunity.com/sharedfiles/filedetails/?id=3044444843) that had already created the model for a booster box. I then scoured the web for images and made some booster boxes for reach set. They are not 100% accurate, but I like how they came out. If you want to create your own boxes, the gimp template file can be found [here](/diffuseTemplates/Booster Box Template.xcf).

There are 2 different kinds of Deckboxes here. Most of them are completely randomized for each set. I used the script from the Mystery Booster Packs found in the "[Magic the gatherring Table - 4 Player Commander](https://steamcommunity.com/sharedfiles/filedetails/?id=2791750952)" mod. I modified the script to use a Booster Box model instead of a booster, and then also generate a booster pack with the appropriate diffuse image. I then changed the script to only pull from each particular set.

All you have to do is pull out a booster, wait a second, and then there will be 15 cards inside of the pack! Simply pull those out and see what you got!

![Modern Horizons III Boster Box](/images/boosterBoxMH3.png)


The other type of Deckbox is the Foundations Jumpstart. These are NOT randomly generated. There are 121 different 20 cards decks in this box. The difference here is that when you pull a deck out, it will be randomly selected for you. That pack will then be replaced inside of the box and then the box will be shuffled. 

You and a friend each pull 2 packs out, remove the face cards (the ones on top that show you the theme), shuffle the 2 decks together and play!

![Foundations Jumpstart Booster Box and Pack](/images/jumpstart.png)

I used the script from the [Infinite Random Bag](https://steamcommunity.com/sharedfiles/filedetails/?id=873630529) mod for this. I filled the booster box, and then applied this script to it. 


## Lessons Learned:

I learned a lot about how Tabletop Simulator uses objects and diffuse images. 

Despite using Gimp for over 15 years, every project like this teaches me something and makes me all the more proficient with it.

My favorite thing was learning how create an alpha selection of text and adding gradients to text layers! You can see this on the back of some of the commander deck boxes.

## Future Improvements:

Currently this project is still a WIP.

I need to add the Foundations Beginner Box and Starter Kit.

The script for the booster pack generation is throwing an error for Universe Beyond sets. So Assassin's Creed and Fallout both need to have the script modified and Booster Boxes made.

The booster pack script also needs to be modified to create a more accurate booster pack. Each pack should have a land included, but that is not always happening. I also need to verify that the cards are generating the proper number of cards based on rarity, and also putting them in the right order.  


## Other Projects
Also check out other projects of mine like this one!:

[Pokemon SV Tracker](https://github.com/ChrisThompsonDev/PokemonScarletVioletTools)
A tool to help you track your progress in Pokemon Scarlet and Violet!


 


