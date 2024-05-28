# Just Got Reel
A casual mobile game created using Unity. It was once deployed on both iOS and Android through Apple Store and Google Play. During the time it was deployed, it <ins>generated $1.22 USD of Ad revenue</ins>. This repo is for showcase purposes. The code/assets for the project are in a private repo.

## Description
A fishing casual game inspired by the fishing mini-game in Stardew Valley. The main mechanic is to tap/hold a button to align the "Reel Bar" with the "Fish Bar" on the side of the screen to "catch" fish. The Reel Bar has acceleration and gravity applied to it through holding and releasing the button. The Fish Bar moves randomly, pausing for a little bit between each move. Put together, creating a mini-game requiring precision and timing. The game has timed rounds, each round ends when player runs out of "Fuel" (timer). The fuel, and many other aspects can be upgraded. Furthermore, the game features:
- a combo system: the longer the two bars are aligned, the more fish are caught; breaking the alignment for too long resets the combo
- an upgrade system: after every round, fish caught are tallied and coins are rewarded; coins are used to buy upgrades that enhances the subsequent games
- a leveling system: lifetime progression; every completed round grants performance-based experience counting towards profile level; higher levels unlock cosmetics (new ships)
- ad monetization: player can voluntarily watch an ad at the end of each round to double the rewards
- upbeat music / sound effects

Not shown here, but a simple website was also deployed using Firebase as the "Developer Website", containing privacy disclaimers, descriptions/links to the game. This was required by the Stores for publication.  

### Main menu
<img src="https://github.com/hli30/JustGotReel-Public/blob/main/screenshots/capture01.png" width="300">

### Core game loop
<img src="https://github.com/hli30/JustGotReel-Public/blob/main/screenshots/capture0.png" width="300">

### Round end results / ad monetization
<img src="https://github.com/hli30/JustGotReel-Public/blob/main/screenshots/capture3.png" width="300">

### Shop for upgrades
<img src="https://github.com/hli30/JustGotReel-Public/blob/main/screenshots/capture5.png" width="300">

### Ship unlock menu / cosmetics
<img src="https://github.com/hli30/JustGotReel-Public/blob/main/screenshots/capture02.png" width="300">

### Unity Game Services Web Portal
This screenshot was taken some time after the game was taken down from the stores. So the short-term stats are all zeros, but the lifetime revenue is shown.  
!["unity"](https://github.com/hli30/JustGotReel-Public/blob/main/screenshots/UnityAds.png)
