# Minesweeper in Haskell

Simplified version of the actual Minesweeper game. The game is played on a *2-D grid* containing cells that contains mines. It's a *1-player* game. If the player reveals a **mine** cell, game is over. Alternatively, if the player reveals all the non-mine cells, the player wins. Revealing the non-mine cells, will reveal the number of neighbouring mine cells.

Tasks involved:
- [ ] Randomnly generate 2-D grid containing random number of mines
- [ ] Populate grid with numbers - number of neighbouring mines
- [ ] Game console
- [ ] Game logic

Game logic:
- [ ] Determine chosen cell is mine or not
- [ ] If chosen cell = mine, then <span style="color:red">__*Lose*__</span> & *Game Over*
- [ ] If chosen cell = **not mine** & **not the last not mine cell**, then *Continue*
- [ ] If chosen cell = **not mine** & **last not mine cell**, then <span style="color:green">__*Win*__</span> & *Game Over*