# Bludgeons and Braggings
All that is needed is a deck of cards, two dice, a piece of paper, and of course players.
Players will battle each other with cards of different stats and abilities. There are four classes to choose from: Warrior (Spades),
Berserker (Clubs), Gambler (Diamonds) and Paladin (Hearts). Two players compete in a series of 1v1 battles and only one player will remain victorious.

## Rules
Two players take turns drawing a card from the deck, totaling to 5 cards per player. Then, players roll a die to determine
who goes first. The highest number rolled wins, but if there is a tie, then reroll until there is a winner.
The player who gets the highest number gets to decide if they want to go first or let their opponent go first.
The person who goes first has the advantage of attacking first, but the person going second has the advantage of picking a card
to counter their opponent. Player 1 chooses an action, then Player 2 chooses an action. The results are calculated after both players have
chosen their actions. Afterwards, the Players alternate who chooses an action first until the battle is done.
The battle is done once a player's card's health reaches 0.
The game is decided by a best of 5 match. However, if a quicker game is needed, then it can be a best of 3 match with 3 cards per player.

### Actions
Four types of actions: Attack, Defend, Dodge, Ability
  * Attack: Does damage to the opponent based on their opponent's defense
		Damage calculations: Attack is subtracted by the defense of the opponents. If the the attack is equal or lower than the opponents defense
		then the base damage is 0. Two dice are rolled to determined for additional damage.

  * Defend: Halves the damage taken, if the damage ends in a decimal, then round up or down to the nearest number.

  * Dodge: Chance to complete avoid damage by rolling a single die, dependent on the speed stat. For every increment of 10 in the speed stat, the chances of dodging is more successful.
		Ex: Speed stat of 10 must roll a 6 to dodge, a speed stat of 20 must roll 6 or 5 to dodge, a speed stat of 30 must roll between 6-4 to dodge. 0 speed cannot dodge.

  * Ability: Every class has their own unique ability that can change the tide of battle, but that ability can only be used once per battle.
		 More details in the Class Descriptions
### Class Descriptions
Four type of stats: Health, Attack, Defense, Speed
Total Stats: 120

#### \[Warrior\] Health: 50, Attack: 30, Defense: 20, Speed: 20
	  Ability: [Dual Strike] Attacks twice in one turn. If opponent uses defend or dodge, only the first attack is affected.

#### \[Paladin\] Health: 60, Attack: 20, Defense: 30, Speed: 10
	  Ability: [War Prayer] Heal for 15 Health and an additional action is taken. Cannot heal above max health.

#### \[Berserker\] Health: 80, Attack: 40, Defense: 0, Speed: 0
	  Ability: [Bloodlust] Survive a fatal attack and perform a counter-attack at half damage.
		   
#### \[Gambler\] Health: 50, Attack 30, Defense: 10, Speed: 30
	  Ability: [All-in] Ignore opponent's defend or dodge action. Perform a normal attack action and afterwards, roll two dice again. If the total is less than 7, deal 15 damage.
		   If the total is 7 or greater, deal 30 damage
