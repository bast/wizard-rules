

# Wizard game rules

## Game and goal

- 3-6 players
- We start with one card per player
- Each round a player gets one card more
- In the last round all cards are distributed and no cards left
- At the beginning of each round, the goal is to predict the number
  of tricks you will collect in the current round


## Value of cards

- Higher number is stronger than lower number
- Trump color is stronger than "normal" color
- Z (Zauberer = wizard) is stronger than any card (except if **first** color card played is trump)
- First Z played in a trick wins the trick (except if first color card played is trump)
- N (Narr = fool) is the weakest card, weaker than any other card
- If the first color card played in a trick is a trump color,
  then Z is without value ("turns it into an N") for the time of this trick
- If the first card played is trump 13, no card can beat it in this trick
- If all cards in a trick are N, the person who played the first card takes the trick
- Examples (we assume four players and that trump is red):
  - (Z, yellow 7, N, red 8): first card wins, remaining 3 players can play any card
  - (red 8, yellow 7, N, Z): first card wins since
    first color card is trump which devaluates Z
  - (yellow 7, red 8, N, Z): last card wins
  - (N, red 8, yellow 7, Z): second card wins since
    first color card is trump which devaluates Z)
  - (N, red 8, red 11, Z): third card wins since Z is here without value
  - (green 11, green 12, N, green 5): second card wins
  - (green 13, green 2, red 1, green 5): third card wins
  - (N, green 2, green 1, blue 13): second card wins
  - (green 13, red 1, green 1, red 3): last card wins, players 2 and 4 have no green cards
  - (green 13, red 1, Z, blue 3): third card wins, players 2 and 4 have no green cards


## Distributing and prediction

- Person to the left of the dealer predicts first and will start first
- Dealer announces as last and will be the last to play in the first trick
- Number of prediction must not sum up to the number of cards (to avoid that everybody is correct)
- ... except that the last person is always allowed to predict zero - this means
  that it is possible that everybody predicts correctly


## Trump color

- In each round there is a trump color (unless there isn't, see below)
- When distributing cards the remaining cards are placed hidden in a deck and the first card
  of the remaining deck is turned which determines the trump color
- If the card turned around is N, there is no trump in this round
- If the card turned around is Z, the trump color is set by the dealer (but the dealer still announces
  number of tricks last)
- In the last round there is no trump since there is no card left - all cards are on the table


## Color restrictions

- You **have to honor the color** of the first card played: if first card is yellow
  and you have yellow, you have to play yellow with the following exception:
- You can **always** play Z or N, even if you have the current color
- If first card is N and second card has a color, then it is the second card which determines the color
  to be honored
- If first card is Z then the player who played it wins the trick, other players can play (throw away)
  any cards in any color
- Examples:
  - trump is blue, first card is red, and you have blue, red, but also Z: you can play either red or Z,
    but you cannot play blue
  - trump is blue, first card is red, and you have blue but no red: you can play blue or something else
  - trump is blue, first card is red, and you have neither blue nor red, nor Z: you can play anything but you
    will lose the trick


## Counting points

- Correct prediction gives 20 points
- For correct prediction each trick gives 10 points
- For incorrect prediction minus 10 points for each card off
- Examples:
  - predicted 0 and got 0: 20 points
  - predicted 1 and got 1: 20 + 10 = 30 points
  - predicted 3 and got 3: 20 + 30 = 50 points
  - predicted 7 and got 6: -10 points
  - predicted 7 and got 5: -20 points
  - predicted 5 and got 6: -10 points


## Recommendations/strategies

- It helps to miss a color or two completely, try to get rid of a color early
- N is a surprisingly valuable card, keep it as long as possible
- Play Z and N late but not too late
- If you don't know which card to play, play a "middle range" number but keep small and high numbers
- If the sum of predictions is less than number of cards,
  expect that at least one person gets too many tricks: don't be too greedy, throw cards away
- If the sum is of predictions higher than number of cards,
  expect that at least one person will get too few cards: be greedy
- Only way to get rid of excess Z is on top of another Z of if the current trick color is trump color
