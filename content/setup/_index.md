+++
date = '2026-04-05T19:16:50+02:00'
title = 'Setup'
+++

## Install Elixir

On _Arch Linux_:

```bash
sudo pacman -S elixir
```

On _Debian GNU/Linux_:

```bash
sudo apt install -y elixir
```

On _OpenBSD_:

```bash
doas pkg_add elixir
```

## Check Versions

Of the interpreter `elixir`:

```bash
elixir --version
```

Of the compiler `elixirc`:

```bash
elixirc --version
```

Of the interactive shell `iex`:

```bash
iex --version
```

Of the build tool `mix`:

```bash
mix --version
```

## Using Mix

Create a project called `scratch`:

```bash
mix new scratch
```

Run IEx for the `scratch` project:

```bash
cd scratch
iex -S mix
```

Recompile the `Scratch` module in `lib/scratch.ex`:

```elixir
> r Scratch
```
