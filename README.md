# Meow-core

Front door for the Puppy Kitty Non-Aggression Pact (PKNAP).

- `index.html` is a joke gate page that sits in front of the Claude sign-in. It has three "desks"
  (treaty, border checkpoint, hotline) and shows a different one on every reload.
  Force one with `?desk=treaty`, `?desk=checkpoint` or `?desk=hotline`.
- `logo.svg` is the PKNAP mark: Nova and Iggy asleep in a yin-yang.

The page collects nothing and asks for no password. Its buttons link to the real Claude sign-in;
change `CLAUDE_LOGIN` near the bottom of `index.html` to point somewhere else.

It is a single static file, so any static host works (GitHub Pages included).
