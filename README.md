# StarColony2000X
Sci-fi boardgame 

It is the year 2000X. You are a number of space ships on the search for a new home in the universe after your home star died. How will you deal with the new challenges faced on this unknown world?


# Rules and mechanics

Game pieces and their function
====

- Player pieces
    - Ship board
        - The home board where a player keeps their personal items
    - Location marker
        - This piece shows where your ship is located
        - What is moved during the movement phase
        - Decides whether you can mine and where you can mine during the mining phase
- Resources
    - Power crystals
      - the base natural resource
    - Intergalactic Dollars
      - required for state interaction
    - Pen and paper
      - up to player imagination
- Mines and mining
    - A player can extract resources at the mine they are located at
    - Mining the same mine incurs an efficiency penalty
      - It is decided as follows:
        - Take the maximum amount any miner has chosen for extraction
        - Subtract by 1 and split the remaining crystals evenly amongst all active miners at the location
        - The subtracted crystal is destroyed
    - Mines regenerate faster the more crystals they have
      - How fast a mine regenerates is the product of their Regeneration Rate coefficient (RR) and the amount of crystals 
        - 0-4 crystals left: 0xRR
        - 5-9 crystals left: 1xRR
        - 10+ crystals left: 2xRR
    - Depleted mines collapse and can be turned upside down
- Robot Space Lord Council
    - Will buy crystals for Intergalactic Dollars
      - 2 crystals is 1 Intergalactic Dollar
      - No take-backs
    - Will fire laser for laser tax
      - Intergalactic Dollars can be put into the laser tax pool at any point during the economic phase
      - Under no circumstance can a player pick up the Intergalactic Dollars they have put into the pool
      - If the total amount does not match or exceed the laser tax cost for the turn:
        - The laser will not be fired
        - The currency in the pool is destroyed (or kept by the Robot Space Lords as a fee)
    - Laser tax is calculated as follows
      - Take the cost of firing the lasers and convert it to Intergalactic Dollars
      - Add 1 Intergalactic Dollar
    - Winning
      - At the end of the turn, a ceremony is held for the player with the most Intergalactic Dollars
      - It is customary to applaud this player and congratulate them on their victory
      - They will hold on to this medal until another player has more dollars at the turn end
- Laser
    - Can be fired by Robot Space Lord Council if enough tax has been collected
    - Can be fired by an individual player's one-time donation of the laser cost
    - Laser cost is calculated as follows
      - Starts at 7 crystals
      - For every victim the alien claims, it is increased by 2 crystals
- Alien
    - At the end of a turn, during the alien attack phase, any player with 0 power crystals will fall victim to the alien
    - Furthermore, if the laser is not fired, the player with the least amount of crystals will be claimed by the alien
    - With every kill, the alien grows stronger, requiring a higher laser cost to keep at bay
- Police
    - The loyal Robot Space Lord Police Force (the loyal RSLPF) will always protect its citizens when the activation fee is paid
      - The fee is 3 Intergalactic Dollars
    - The loyal RSLPF action is the following
      - The player with the most crystals are stripped of all but 1 of them
      - The stripped crystals are redistributed to the rest of the players
        - If even distribution is not possible the players with the least crystals are prioritized
One turn of the game
====

A round of StarColony2000X
----
- Action phases
    - Movement planning -> execute
    - Mining planning -> execute
    - Economic actions
        - Send crystals to players
        - Sell crystals to the Robot Space Lord Council
        - Put Intergalactic Dollars in *laser tax pool*
        - Put Intergalactic Dollars in the bribe pool
        - Individual laser activation
- End-of-turn events:
    - Police action
    - Laser firing
    - Life support cost
    - Alien attack
    - Mine regeneration


