# NodeJS Intro: Note Taking App

> Easy Note taking App with `fs` and `CLI` command. This is course exercise from `Introduction to Node.js, v3`

## Initialize

```
sudo npm link --force
```

### Open App

```
note web [port]
// it would appear in localhost:[port]
```

## CLI Command:

```
Commands:
  note new <note>     create a new note
  note all            get all notes
  note find <filter>  get matching notes
  note remove <id>    remove a note by id
  note web [port]     launch website to see notes
  note clean          remove all notes

Options:
      --help     Show help                                             [boolean]
      --version  Show version number                                   [boolean]
  -t, --tags     tags to add to the note                                [string]
```
