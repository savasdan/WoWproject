# This project is a turn-based battle simulator between two teams: Orcs and Night Elves. Each character has:
  100 health
  An attack speed that controls how often they attack
  A delay timer before they can attack again
# During the battle:
  Characters whose delay is 0 attack a random enemy.
  Each attack deals 3 to 10 damage.
  If a character’s health drops to 0 or less, they are removed from the team.
  After each round, characters heal +1 health (up to 100) and their delay goes down by 1.
  The fight continues until one team has no characters left.
