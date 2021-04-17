<div align="center">
<h1><code>Conway's Game of Life</code></h1>
<sub>Built with 🦀 Rust and 🕸 WebAssembly</a></sub>

</div>

## About

This game is written in Rust and compiled into WebAssembly.

### 🛠️ Build the rust code with `wasm-pack build`

```
wasm-pack build
```

### 🛠️ Run the WebAssembly in your browser

```
cd www
npm install
npm run start
```

https://user-images.githubusercontent.com/14112830/115125311-7efde500-9f84-11eb-87ef-fb84d594b1b5.mov

      "The universe of the Game of Life is an infinite two-dimensional orthogonal grid of square cells, each of which is in one of two possible states, alive or dead, or "populated" or "unpopulated". Every cell interacts with its eight neighbours, which are the cells that are horizontally, vertically, or diagonally adjacent. At each step in time, the following transitions occur:

      1. Any live cell with fewer than two live neighbours dies, as if caused by underpopulation.

      2. Any live cell with two or three live neighbours lives on to the next generation.

      3. Any live cell with more than three live neighbours dies, as if by overpopulation.

      4. Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.

      The initial pattern constitutes the seed of the system. The first generation is created by applying the above rules simultaneously to every cell in the seed—births and deaths occur simultaneously, and the discrete moment at which this happens is sometimes called a tick (in other words, each generation is a pure function of the preceding one). The rules continue to be applied repeatedly to create further generations." - Quote source below

[Quote source][excerpt]

[excerpt]: https://rustwasm.github.io/docs/book/game-of-life/rules.html

[Read the tutorial][tutorial]

[tutorial]: https://rustwasm.github.io/docs/book/game-of-life/introduction.html
