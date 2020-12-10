# PLANNING

This is an [Advent of Code](https://adventofcode.com) runner for Deno.

## Directory structure

```
- aoc (executable, you can check this into vcs)
- data/ (could be a git submodule)
  - 2020/
    - code/
    - input/
- src/
  - cli.js
  - lib/
    - mod.ts
```

## Installation Process

1. [Create a repository from this template](https://docs.github.com/en/free-pro-team@latest/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template#creating-a-repository-from-a-template)

2. Clone your repo:

```bash
$ git@github.com:YOUR_USERNAME/aoc-deno.git
```
3. Install the executable:

```bash
$ deno install --name=aoc --root=./ --allow-read=./ ./src/cli.js
```

## Usage

### Setup year data

```bash
$ ./aoc setup <YEAR>
```

### Setup day data

```bash
$ ./aoc setup <YEAR> <DAY>
```

### Run specific day

```bash
$ ./aoc run <YEAR> <DAY>
```

### Run latest day for a specific year

```bash
$ ./aoc run <YEAR>
```

### Run all days for a specific year

```bash
$ ./aoc run <YEAR> all
```
