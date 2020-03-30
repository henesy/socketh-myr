# SocketH - Myrddin

An implementation of [SocketH](https://github.com/henesy/SocketH) in [Myrddin](https://myrlang.org).

## Requirements

The server is broken on Linux/amd64, I don't know why. Patches and insight are welcome.

This seems to work fine on 9front/amd64.

## Build

To build a given project:

	mbld

## Run

From a built project:

	./obj/$binary

where `$binary` is the project name.

## Usage

Shclient on unix might be best paired with a wrapper like `rlwrap(1)`:

	rlwrap shclient -a 'tcp!plan9.postnix.pw!9090'

## Special commands

| `!quit` | clean disconnect |
