# react-simplemde-editor - Agent Guide

This is the agent-facing guide for working in this repository.

## Project Context
- React wrapper for simplemde (easymde) markdown editor

## Setup
See [`agents.yaml`](./agents.yaml) for prerequisites, commands, and ports.

### Setup Hints
- `nvm` may not be loaded in your shell. If `nvm: command not found`, source it first.
- `yarn dev` runs in the foreground — background it the same way.

## Running the App
- Clone the repo
- Install: `yarn install`
- Dev: `yarn dev &`
- Access: `http://localhost:8080`

## Architecture
- React wrapper for SimpleMDE/EasyMDE markdown editor
- Webpack for bundling
- Entry point: `src/index.js`

## Working Agreement
- Write modular code
- Keep testable
- Incremental validation
- Commit meaningful checkpoints
- Write tests
- Validate before handoff
