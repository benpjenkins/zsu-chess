# Initial Repo Creation

## Status

Proposed

## Context

Before writing any code I want to take some time to thinking through what sort of tools and structure I would like for this repo.  I am imagining that there will be multiple components that I might want to build as part of this process.

- A UI for actually playing a chess game.
- A server to manage the chess games being played through the UI.
- A core chess engine for evaluating/picking moves.

My assumption is that these components, and potentially others, may be optimally built using different technologies.  A web app would make sense to build using any number of javascript libraries for example.  A chess engine on the other hand would benefit greatly from multi threading and being able to use whatever resources are provided to quickly calculate many different lines of moves.

## Decision

All that I'm thinking at the moment is that I would like to use nx to manage this repo as a monorepo for all the components of this software which I may or may not build in the future

## Consequences

Better organization, tech agnostic workspaces and task running, potential cloud integrations in the future.