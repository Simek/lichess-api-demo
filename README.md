# Lichess OAuth app demo

This is an example for a fully client side OAuth app that uses various APIs.

## Features

- Fully client side, no server needed
- Login with Lichess (OAuth2 PKCE)
- View ongoing games
- Play games
- Challenge the AI opponent
- Challenge a player
- Create a game seek
- Watch Lichess TV

## Try it out

[The demo app is hosted on GitHub Pages](https://lichess-org.github.io/api-demo/)

## Run it on your machine

1. `pnpm install`
1. `pnpm run dev` for local development, or `pnpm run build` for production output
1. `pnpm run serve` to preview the production build on http://localhost:4173

## Points of interest

- [ND-JSON stream reader](https://github.com/lichess-org/api-demo/blob/master/src/ndJsonStream.ts)
- [OAuth "Login with Lichess"](https://github.com/lichess-org/api-demo/blob/master/src/auth.ts)
- [Read the main event stream](https://github.com/lichess-org/api-demo/blob/master/src/ctrl.ts)
- [Game play](https://github.com/lichess-org/api-demo/blob/master/src/game.ts)
- [Create a seek and await a game](https://github.com/lichess-org/api-demo/blob/master/src/seek.ts)
- [Challenge a player](https://github.com/lichess-org/api-demo/blob/master/src/challenge.ts)
- [Watch Lichess TV](https://github.com/lichess-org/api-demo/blob/master/src/tv.ts)

Feel free to reuse and learn from this code when building your own Lichess API app.
