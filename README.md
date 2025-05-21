# nb-plugins

A collection of plugins that can be used with the note taking tool nb.

## 📦 Installation

Plugins can be installed independently.

```
nb plugin install https://github.com/austinkmassey/nb-today.nb/blob/main/today.nb-plugin
```

## 🛠️ Requirements

    nb installed and configured.

## **today** - Daily journal plugin for nb

**today** is a simple plugin that helps you create and manage daily journal notes with nb.

It opens today's journal note if it exists, or creates a new one tagged with:

**task-count** - a task counter for

```
#journal #YYYY-MM-DD (today’s date)
```

### 🚀 Usage

```
nb today
```

If today's note exists, it will be opened for editing.

If not, a new note will be created automatically with today's date.

Each note is tagged like:

```
#journal #2025-04-14
```

and titled:

```
# Journal - 2025-04-14
```

### 📋 Example

```
$ nb today
# (opens today's journal note, creating it if needed)
```
