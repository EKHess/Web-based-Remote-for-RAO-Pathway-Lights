# Web-based Remote for Eco-friendly Pathway Lights at the Rothney Astrophysical Observatory

This remote is the front-end component used by the user to control the entire RAO Smart Pathway Light array. These lights feature eco-friendly, warm colour temperature lighting that is friendly for local wildlife, and reduces light pollution. Under the hood, this HTML file lives inside the Arduino code that runs the entire network. The Arduino Wemos D1 Mini that runs the server and client machines currently only accomodates one HTML file, hence the one-file-structure of the current remote's front-end. 

## Features
Javascript dynamically renders the interface, informing the user of which buttons may be actively pushed (in orange) and which feature is already in use, and therefore can't be selected (in grey). Within the code, Javascript calls functions activating each of the current 4 modes which interfaces with the Arduino code to control the lighting array. 

Since the remote is web-based, it's compatible with any mobile device. 

### Planned Upgrades
Improved dynamic styling would improve the aesthetic of the remote on smaller smart phones. 

## How To Use
Try out a copy of the project here: [ekhess.github.io/Web-based-Remote-for-RAO-Pathway-Lights](ekhess.github.io/Web-based-Remote-for-RAO-Pathway-Lights)

## Technologies
- HTML5
- CSS3
- JavaScript ES6

## Collaborators
A successful front-end design involves integrating with the back-end, in this case designed by UCalgary Engineering Students which has since been updated and modifed by RAO Chief of Technical Operations, Jim Pake. 
