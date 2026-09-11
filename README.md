# Omarchy Todo

A tiny local GTK 4 todo app made for Omarchy.

## Features

- Add tasks
- Check tasks off
- Delete tasks
- Clear completed tasks
- Stores todos locally at `~/.local/share/omarchy-todo/todos.json`

## Run

```bash
./omarchy-todo
```

## Install locally

```bash
install -Dm755 omarchy-todo ~/.local/bin/omarchy-todo
install -Dm644 omarchy-todo.desktop ~/.local/share/applications/omarchy-todo.desktop
update-desktop-database ~/.local/share/applications 2>/dev/null || true
```

Then launch **Todo** from the app menu.
