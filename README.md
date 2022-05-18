# Haymaker

A quick card game for 2 players

## Set Up

1. Remove all face cards from the deck
2. Select a dealer randomly
3. The dealer shuffles the deck and deals a 10 card hand to each player. Players may look at their hands.
4. The dealer removes from the game (“burns”) the top four cards of the deck, face down.

## Objective

To force your opponent to run out of cards in hand before you do.

## Game Structure

One player is the Attacker and one is the Defender. Each turn, the attacker sets up an attack and the defender responds. Depending on what happens, the players may switch roles and play continues.

## Turn Structure

1. Check if the match is over
2. Attack
3. Defend
4. Resolution

## Turn Phases

### 1. Check if the match is over

At the beginning of each turn, so long as one player has cards in hand, the game continues. However, if neither player has any cards, the game goes to decision.

If the game goes to decision, each player counts up the cards in their discard piles. The player with the most cards wins by decision. If both players have the same number, the game ends in a draw.

### 2. Attack

The attacker starts by using one of the following moves. If the attacker cannot legally perform any of the moves, the defender wins by technical knockout.

- Normal Attack: The attacker chooses a single card from their hand and plays it face up. The strength of the attack is the number on the card (Ace = 1).
- Haymaker: The attacker chooses two or more cards from their hand with the same suit and plays them face up. The strength of the haymaker is the sum of the numbers on the cards (Ace = 1). There is no limit to the number of cards played for a haymaker so long as they are all the same suit.
- Pass: The attacker may only use this move if they attacked last turn (normal attack or haymaker). If the draw pile is not empty, the attacker draws two cards, chooses one to add to their hand, and gives the other to the defender. Finally, players switch roles and the next turn immediately begins.

### 3. Defend

The defender responds to the attack with one of the following options. If the defender has no cards in hand, they must take the hit.

- Block: The defender chooses any number of cards from their hand to block with and plays them face up. The sum of the numbers on the cards are the strength of the block (Ace = 1). In order to block, the defender’s block strength must be at least as high as the attack strength. A reversal is a special type of block that allows the defender to go on the offensive. It happens when the defender blocks and at least one of the following are true: (1) the strength of the block equals the strength of the attack, (2) the attack was a haymaker, or (3) the attacker has no cards left in their hand.
- Take the Hit: The defender gives a random card from their hand to the attacker. If the attack was a haymaker, they instead give two random cards from their hand to the attacker. If the defender does not have enough cards to give, the attacking player wins by knockout.

### 4. Resolve the Attack

Depending on how the defender responded to the attack, the turn resolves in one of 3 ways:

- If the defender got a reversal: The defender adds the played cards to their discard pile, then both players draw a card (if available). Finally, players switch roles and the next turn begins.
- If the defender blocked but did not get a reversal: The attacker adds the played cards to their discard pile and the next turn begins
- If the defender took the hit: The attacker adds the played cards to their discard pile and the next turn begins.
