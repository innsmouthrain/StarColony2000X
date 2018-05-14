# StarColony2000X
Sci-fi boardgame 

It is the year 2000X. You are a number of space ships on the search for a new home in the universe after your home star died. How will you deal with the new challenges faced on this unknown world?


# Rules and mechanics

Game pieces and functionality
----

- ### Player pieces
    - Ship board
        - The home board where a player keeps their personal items
    - Location marker
        - This piece shows where your ship is located
        - What is moved during the movement phase
        - Decides whether you can mine and which mine you will extract from during mining phase
    - Extraction marker
        - Marks your decision on how many units of power crystal you will extract at execution of mining phase
- ### Resources
    - Power crystals
      - The base natural resource
    - Intergalactic Space Dollars
      - Required for state interaction
    - Pen and paper
      - Up to player imagination
- ### Mines and mining
    - A player can extract resources at the mine they are located at
    - They can choose to mine 2, 4 or 6 crystals
    - Mining the same mine incurs an efficiency penalty
      - It is decided as follows:
        - Take the maximum amount any miner has chosen for extraction
        - Subtract by 1 and split the remaining crystals evenly amongst all active miners at the location
            - If even split is not possible, the player with the *most* crystals is prioritized
        - The subtracted crystal is destroyed
    - Mines regenerate faster the more crystals they have
      - How fast a mine regenerates is the product of their Regeneration Rate coefficient (RR) and the amount of crystals 
        - 0-4 crystals left: 0xRR
        - 5-9 crystals left: 1xRR
        - 10+ crystals left: 2xRR
    - Depleted mines collapse and can be turned upside down
- ### Robot Space Lord Council
    - Will buy crystals for Intergalactic Space Dollars
      - 2 crystals is 1 Intergalactic Space Dollar
      - No take-backs, no reverse trades
    - Will fire laser for laser tax
      - Intergalactic Space Dollars can be put into the laser tax pool at any point during the economic phase
      - Under no circumstance can a player pick up the Intergalactic Space Dollars they have put into the pool
      - If the total amount does not match or exceed the laser tax cost for the turn:
        - The laser will not be fired by the Robot Space Lord Council
        - The currency in the pool is destroyed (or kept by the Robot Space Lords as a fee)
    - Laser tax is calculated as follows
      - Take the cost of firing the lasers and convert it to Intergalactic Space Dollars, rounded up
      - Add 1 Intergalactic Space Dollar
    - Winning
      - At the end of the turn, a ceremony is held for the player with the most Intergalactic Space Dollars
      - It is customary to applaud this player and congratulate them on their victory
      - They will hold on to this medal until another player has more dollars at a turn end
- ### Laser
    - Can be fired by Robot Space Lord Council if enough tax has been collected
    - Can be fired by an individual player's one-time donation of the laser cost
    - Laser cost is calculated as follows
      - Starts at 7 crystals
      - For every victim the alien claims, it is increased by 2 crystals
- ### Alien
    - At the end of a turn, during the alien attack phase, any player with 0 power crystals will fall victim to the alien
    - Furthermore, if the laser is not fired, the player with the least amount of crystals will be claimed by the alien
    - With every kill, the alien grows stronger, requiring a higher laser cost to keep at bay
- ### Police
    - The loyal Robot Space Lord Police Force (the loyal RSLPF) will always protect its citizens when the activation fee is paid
      - The fee is 3 Intergalactic Space Dollars
    - The loyal RSLPF action is the following
      - The player with the most crystals are stripped of all but 1 of them
      - The stripped crystals are redistributed to the rest of the players
        - If even distribution is not possible the players with the least crystals are prioritized

A round of StarColony2000X
----
- ### Action phases
    - Movement phase
      - Discussion (possibly timed)
      - Non-reversible execution
    - Mining planning 
      - Discussion (possibly timed)
      - Non-reversible execution
    - Economic actions
        - Send crystals to player ships
        - Sell crystals to the Robot Space Lord Council
        - Put Intergalactic Space Dollars in *laser tax pool*
        - Put Intergalactic Space Dollars in *the bribe pool*
        - Individual laser activation
- ### End-of-turn events:
    - Police action
    - Laser firing
    - Life support cost
    - Alien attack
    - Mine regeneration


