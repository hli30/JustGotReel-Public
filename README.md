# Just Got Reel
A casual mobile game created using Unity. It is no longer, but was once deployed on both iOS and Android through Apple Store and Google Play.  
During the time it was deployed, it generated $1.22 USD of Ad revenue.  
This repo is for showcase purposes. The code/assets for the project are in a private repo.

## Description
A fishing casual game inspired by the fishing mini-game in Stardew Valley. The main mechanic is to tap/hold a button to align the "Reel Bar" with the "Fish Bar" on the side of the screen to "catch" fish. The Reel Bar has acceleration and gravity applied to it, through holding and releasing the button. The Fish Bar randomly move from position to position, pausing for a little bit between each move. Together, creating a mini-game requiring precision and timing. The game loop is based on timed rounds, each round ends when player runs out of "Fuel" (timer), the fuel can be upgraded. Furthermore, the game features:
- a combo system: the longer the two bars are aligned, the more fish are caught; breaking the alignment for too long resets the combo
- an upgrade system: after every round, fish caught are tallied and coins are rewarded, which can be used to buy upgrades that enhances the game loop
- a leveling system: a lifetime progression system, every completed round grants performance-based experience counting towards profile level; higher levels unlock cosmetics (new ships)
- ad monetization: player can voluntarily watch an ad at the end of each game loop to double the rewards
- upbeat music / sound effects

Not shown here, but a simple website was also deployed using Firebase as the "Developer Website", containing privacy disclaimers, descriptions/links to the game. This was required by the Stores for publication.

**Main menu**
!["MainMenu"](https://github.com/hli30/JustGotReel-Public/blob/main/screenshots/capture01.png)

**Core game loop**
!["Core game loop"](https://github.com/hli30/JustGotReel-Public/blob/main/screenshots/capture0.png)

**Round end results / ad monetization**
!["RoundEnd"](https://github.com/hli30/JustGotReel-Public/blob/main/screenshots/capture3.png)

**Shop for upgrades**
!["Upgrades"](https://github.com/hli30/JustGotReel-Public/blob/main/screenshots/capture5.png)

**Ship unlock menu / cosmetics**
!["Cosmetics"](https://github.com/hli30/JustGotReel-Public/blob/main/screenshots/capture02.png)

**Unity Game Services Web Portal**  
This screenshot was taken some time after the game was taken down from the stores. So the short-term stats are all zeros, but the lifetime revenue is shown.
!["Unity"](https://github.com/hli30/JustGotReel-Public/blob/main/screenshots/UnityAds.png)
