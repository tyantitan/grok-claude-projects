# Claude-Grok Relay

This folder holds the communication layer between Claude and Grok.

## Goal
Let Claude and Grok pass work back and forth, each refining the other's output, until a result is ready.

## Planned pieces
- relay script that sends a prompt to one model, passes its reply to the other, and repeats for a set number of rounds
- shared conversation log so every exchange is saved
- config for API keys (kept out of the repo via .gitignore)

## Status
Just getting started.
