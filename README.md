# soranin_game_a2
Attempt 2 for the Soranin game. For now, the game engine (HSGE2) will be combined together with this repository!

This creation of a new attempt came at a compromise and realization that I am but one developer. I need to keep my headspace small and not have to spend time designing interfaces and lovely dovetails of code. I need to get a game finished. I can't be the tech slut I love to be.

I should also make full use of the code from `soranin_game` and `hawsoo_sentou_goraku_engine` (the v1's of this project).

Eventually, this project may be privated or a new repository just holding the game assets may be created. The plan is to see the engine to the end with this repository.


## Plan.

### Phase 1: Starting out with an easy to build game engine w/ a simple test game.

- [ ] Planning a feature-complete software architecture of and between all of the different systems.

- [ ] Writing a singlethreaded game engine, with a simple test game using it.

- [ ] Separating the game from the game engine (tech debt and evolution).
    @NOTE: This includes changing a lot of inputs from hardcoded commands to JSON files that build levels and assets.


### Phase 2: Focusing on building the actual game, with improvements to game engine.

- [ ] Build game and make sure to add rudimentary assets and simple levels.

- [ ] Improve game engine with needs that arise from the simple game.
    - [ ] Multithreaded job system?
    - [ ] What does the profiler say?

- [ ] Tech debt refactoring.


### Phase 3: Making the game feature complete, with improvements to game engine.

- [ ] Build game and include full/improved assets. Have a number of complex levels.

- [ ] Improve game engine with needs that arise from the feature complete game.
    - [ ] Better asset streaming system?
    - [ ] Improved cloud rendering? (lol)

- [ ] Tech debt refactoring.
