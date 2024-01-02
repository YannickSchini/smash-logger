# smash-logger

Side-project to log the results of my Smash Ultimate games and training sessions.
Please do not use this project for anything as I have no clue about Frontend Development and generally don't know what I'm doing.

I'm using VueJS 3 (scaffolded the project with vue-create), and will code it as an SPA.
My aim is to host it with GitHub Pages, and use this app from my phone when I play.

## Target description

Basically, there'll be two main "pages":
- One that lets my input information for each match I play online (opponent character, date, win/loss, optional notes, etc)
- One that lets me track my progress in different exercices I'll do to improve specific aspects of my gameplay

At first, all data will be stored locally on the device (using a JSON or CSV file I suppose).
Then, I'll see how I can sync this data somewhere I can easily reach it from a computer (Google Drive ?) to play around with it: add graphs, get statistics, etc.

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```
