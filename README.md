# Checkers AI Game
Like chess, checkers has always been interesting to computer programmers because it is a game of mathematical possibilities. The very first computer program built to play Checkers was created in 1952 by programmer Arthur L. Samuel. Since then, many more advanced and complex Checkers programs have been developed; some have defeated even very advanced players.

## Game Basic
Checkers is played by two players. Each player begins the game with 12 colored discs. (Typically, one set of pieces is black and the other red.) Each player places his or her pieces on the 12 dark squares closest to him or her. Black moves first. Players then alternate moves.

The board consists of 64 squares, alternating between 32 dark and 32 light squares. It is positioned so that each player has a light square on the right side corner closest to him or her.

A player wins the game when the opponent cannot make a move. In most cases, this is because all of the opponent's pieces have been captured, but it could also be because all of his pieces are blocked in.

## Rules of game
<ul>
  <li>Moves are allowed only on the dark squares, so pieces always move diagonally. Single pieces are always limited to forward moves (toward the opponent).</li>
  <li>A piece making a non-capturing move (not involving a jump) may move only one square.</li>
  <li>A piece making a capturing move (a jump) leaps over one of the opponent's pieces, landing in a straight diagonal line on the other side. Only one piece may be captured in a single jump; however, multiple jumps are allowed during a single turn.</li>
  <li>When a piece is captured, it is removed from the board.</li>
  <li>If a player is able to make a capture, there is no option; the jump must be made. If more than one capture is available, the player is free to choose whichever he or she prefers.</li>
  <li>When a piece reaches the furthest row from the player who controls that piece, it is crowned and becomes a king. One of the pieces which had been captured is placed on top of the king so that it is twice as high as a single piece.</li>
  <li>Kings are limited to moving diagonally but may move both forward and backward. (Remember that single pieces, i.e. non-kings, are always limited to forward moves.)</li>
  <li>Kings may combine jumps in several directions, forward and backward, on the same turn. Single pieces may shift direction diagonally during a multiple capture turn, but must always jump forward (toward the opponent).</li>
</ul>

## Installation and use

```
$ git clone https://github.com/amirooz/checkers-ai-react.git
```
```
$ cd checkers-ai-react
```
### Unix / Linux
```
$ yarn install
```
```
$ yarn start
```
### Windows
```
$ npm install
```
```
$ npm start
```
Runs the app in the development mode.<br>
**  http://localhost:3000 **

## Screenshots
<img src="public/screenshots/checkers-1.png" alt="">
<img src="public/screenshots/checkers-2.png" alt="">

## License
Checkers AI game is permissive software licensed under the [MIT license](https://opensource.org/licenses/MIT).
Frameworks and libraries has it own licensed
