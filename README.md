# Browser Games

A collection of games to play in a web browser. See the full list of games in the [games.md](games.md) file.

## Installation and Setup

Clone the repo, install npm dependencies, and start the server:

```shell-session
$ git clone git@github.com:GuildCrafts/browser-games.git
$ cd browser-games
$ npm install

...

$ npm start
...
Starting up http-server, serving ./public
Available on:
  http://127.0.0.1:4321
  http://10.0.1.11:4321
```

Then open `http://localhost:4321/` in your browser of choice and play away!

## Specifications

#### General

- [X] Artifact produced is a fork of the [browser-games][browser-games] repo.
- [X] Variables, functions, files, etc. have appropriate and meaningful names.
- [X] HTML, CSS, and JS files are well formatted with proper spacing and indentation.
- [X] There is a clear separation of game logic code from view/rendering code.
- [X] All major features are added via pull requests with a clear description and concise commit messages.
- [X] The artifact produced is properly licensed, preferably with the [MIT license][mit-license].

#### Tetris

- [X] [User stories](http://searchsoftwarequality.techtarget.com/definition/user-story) and features for the game are added as issues to your repo with the label `feature` or `user-story`
  <br>_You'll have to define these yourself by looking at the rules of the game and coming up with the right user stories & features_
- [ ] jQuery is used for DOM manipulation code
- [X] Tetris game can be found at `public/tetris.html`
- [X] Tetris game is playable
- [X] Players have a score
- [X] Game page is linked from `public/index.html`

### Stretch

- [ ] Players can configure the key mapping (e.g. change the "drop" key to the space bar)
- [ ] Game follows object-oriented patterns using ES6 classes
