# nb-plugins

A collection of plugins that can be used with the note taking tool nb.

## 📦 Installation

Plugins can be installed independently.

```
#Install today
nb plugin install https://github.com/austinkmassey/nb-today.nb/blob/main/today.nb-plugin

#Install dash
nb plugin install https://github.com/austinkmassey/nb-today.nb/blob/main/dash.nb-plugin
```

## 🛠️ Requirements

    - nb installed and configured
    - awk (for task-count)

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

## **dash** - dashboard for tasks and other items

**dash** summarizes usage and object count data to give an overview of notes

When called, it presents a text based description of measurements it takes of notes.

### 🚀 Usage

```
nb dash
```

Returns a count of open and completed tasks for each directory in the current notebook.

```
Directory                                 Completed  Incomplete
./projects/notes                              12         3
./projects/todo                               8          5
```
