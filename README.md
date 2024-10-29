# Turbo Repo Template

A default template for a monorepo. 

## Prerequisites

To get started install [Node version 20+](https://nodejs.org/en/download/package-manager), and [pnpm](https://pnpm.io/) (globally).

## Dependency Management

We use [pnpm](https://pnpm.io/), for [reasons mentioned here](https://pnpm.io/pnpm-vs-npm). Install all dependencies by running `pnpm i` in the root. 

## Project Structure

The template is configured as a pnpm workspace.
There are two subfolders for code: 

- `apps` which contains all the apps.
- `packages` which contains all shared code and configuration.

## Code Style

Code style is determined by [Biome](https://biomejs.dev/). There are three code style commands included:

- `check`: lints, formats, and fixes imports. This is run on committing the code.
- `format`: formats the code
- `lint`: lints code