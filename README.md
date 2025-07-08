# SBI tutorial at [AI+Science Summer School 2025](https://aissai.cnrs.fr/en/aiscience-summer-school-2025-university-of-chicago-center-in-paris/)

A simple sbi tutorial

## Prerequisite Software

### Pixi

To install Pixi follow [the installation instructions](https://pixi.sh/latest/#installation) for your particular machine and then restart your shell.

#### Unix (Linux and macOS) and Windows Terminal

```bash
curl -fsSL https://pixi.sh/install.sh | sh
```

#### Windows PowerShell

```powershell
powershell -ExecutionPolicy ByPass -c "irm -useb https://pixi.sh/install.ps1 | iex"
```

#### Pixi Shell completions

Additionally, install the [Pixi shell completions](https://pixi.sh/latest/advanced/installation/#autocompletion) for your particular shell choice.

### Git

You probably already have Git installed on your machine.
You can check (on a Unix machine) with

```bash
command -v git
```

If the command doesn't return a filepath to the `git` executable, first make sure you have Pixi installed, as described above, and then run

```bash
pixi global install git
```

You can now use Git anywhere on your machine.

## Setup

1. Ensure all prerequisite software on your machine as described above
2. Clone this repository and navigate to it on your machine

```bash
git clone https://github.com/cranmer/sbi-tutorial.git
cd sbi-tutorial
```

3. Run the notebook

```
pixi run start
```

which will install all the software for the tutorial and launch a Jupyter Lab interface to the tutorial notebooks.
