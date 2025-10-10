# Meetings
Team Meeting 10/10/2025 Agenda:

Intro
Team introduction (background, strengths, things you want to learn?)
Team meeting schedule: https://www.when2meet.com/?32908074-u2Rw9 
Team name? 
Meeting notes will be posted to the team slack

The project 🙂
Timeline:
EOD Mon 10/13: Sub-teams finish implementing their pieces
EOD Tues 10/14: Debugging, cross-testing, all code implementation finished
EOD Wed 10/15: Padding, create demo (working demo + video backup)
Setting up
Github org: https://github.com/orgs/CSE210-fa25-team07 
everything will be on this repo, including code, documentation, and meetNotes.
Github Usernames
Gaurav17Joshi
ezh247467
Yuribz
sree-teja
Jialuohu
Braxton203
Emma77017
Will7I1Am3
alien-traveler
Git practices!
1. Everything on Github 
Code and Documentation
Scope the project [Product.md]
What will our demo look like? 
Feature (e.g. do we allow input multiple words at same time -> output emoji)
Interaction
Clarification questions for the prof:
Can we use external APIs?
What should inputs look like?
Technical Design (Technical.md)
	- Serverless ?
	- feature -> technical 
	e.g english -> emoji is probably 1 vs many
but emoji -> english word is probably 1 vs 1
data design requires some fix

Small team split (self assigned)
Frontend:
Yuri
Will
Gaurav Joshi
Emoji Matching:
Luting
Rhea
Braxton Conley
Jialuo
Backend 
Win
Emma
Sree Teja
Testing/DevOps
Ethan
Wayne [writer]

For the rockstar ninja if we have time: (Potential external AI service usage?)

Extra tasks
Things to add/delete from readings on 10/9 class (https://houses-pay-526.craft.me/fWTsrhQJjFDYl7, https://houses-pay-526.craft.me/22hg03hlJlPkBG )

Assigned To Dos:








Examples:

I am very happy -> I am very 😀
The match was tough but our team won. -> The match was tough but our team won 🥳🔥🔥
My Aws bill is over 2000 $ ->  My Aws bill is over 2000 $ 💀

# Emoji-Product Deisgn
## 1. Goal
Create a simple, intuitive tool for a user to translate English vocabs to corresponding emoji and emoji to English vocabs.

## 2. User Story
User input an iOS default emoji, output an vocab describing the emoji
User input a vocabulary (not phrase), output an emoji
Optionally, we can predefine some phrases that people often use
Paragraph input (a lot of vocab) -> emoji of the vocabs that we do have mapping for
Multiple emoji -> multiple vocab
Button for mood (advanced feature)
Multiple inputs
Input Separation: anything not english or emoji
Output separation: follow the user 


Emoji vocab mapping relation. A button for mode
1 emoji -> many vocab


## Interface
Layout: looks like google translator
A reverse button, to change mode from “english -> emoji” to “emoji -> english”, vice versa
Input field （text/emoji)
Sample emoji/text (depending on mode) 
Mood 

Examples: 

Input:
I like to drink milk and coffee.

Output [emoji];
MILK  COFFEE

Output [emoji]:
I LIKE DRINK MILK and COFFEE.

Summarize 

1. Text -> emoji 1 - many
2. Emoji -> text 1 - 1
3. Paragraph -> we translate without choice
4. Reverse button 


# Emoji-Techincal Design
# Requirement
No framework, Pure, Javascript, html, and css only.

# Layers
The project has two major layers:
1. Frontend: everything the user sees and interacts with. Html, css, js, all this part. Design
2. Backend: just for the dictionary; communicate with frontend + data 
2. Data Storage: dictionaries keep track of emoji <-> vocab matching

# Components
Each Layers contains multiple major components:
## Frontend Layer
Frontend Layer contains 
…….
## Data Layer
Data Layer contains
……


