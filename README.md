# haskell-hello-world

This is a hello world project for using haskell with the [yesod](https://www.yesodweb.com/) web frame work
to make a minimal webpage.

## How to run locally 

This project uses [stack](https://docs.haskellstack.org/en/stable/README/) to manage it's dependencies.

Assuming that you've already installed stack, the app can be launched locally using

``` bash
stack run app/Main.hs
```

This will start the local warp server. To see the webpage visit `localhost:3000`

## improvements down the line

Should be able to run the webpage using a development server so that changes can be experimented with live!
