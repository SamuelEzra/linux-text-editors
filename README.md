# Linux Text Editors (Vim & Nano)
This project explores two essential **Linux text editors**: **Vim** and **Nano**. These editors are used to manage configuration files, write scripts, and modify system settings directly from the terminal.

### Getting Started
#### Installing Vim & Nano
Most Linux distributions include **Nano** by default. To install both editors:

```sh
sudo apt update && sudo apt install vim nano
```

For **RHEL-based systems**:

```sh
sudo yum install vim nano
```


### Basic Vim Commands
#### Opening a File in Vim

```sh
vim filename.txt
```

- If the file doesn't exist, Vim creates it.

#### Entering Insert Mode (Editing Text)
Press `i` to start editing the file.
#### Saving & Exiting
- Save and exit: `ESC` → :`wq` → `Enter`
- Exit without saving: `ESC` → `:q!` → `Enter`

#### Navigation in Vim
- Move one character left (`h`), right (`l`), up (`k`), down (`j`).
- Move to the beginning of a line (`0`).
- Move to the end of a line (`$`).

#### Undo & Redo
- Undo: `u`
- Redo: `CTRL + R`

####Search in a File

```sh
/keyword
```

Press `n` to jump to the next match.

### Basic Nano Commands
#### Opening a File in Nano

```sh
nano filename.txt
```

### Editing & Saving Changes
- **Edit** the file directly after opening.
- **Save** changes: `CTRL + X`, then `Y`, then `Enter`.

### Navigation & Editing in Nano
- Move the cursor using `arrow keys`.
- Cut a line: `CTRL + K`
- Paste a line: `CTRL + U`
- Search for text: `CTRL + W`, enter search term, then press `Enter`.
- Exit without saving: `CTRL + X`, then `N`.


Choosing Between Vim & Nano

✅ **Nano** → Simple, beginner-friendly editor.

✅ **Vim** → Powerful, advanced with extensive features.

### Security Considerations

- Use **sudo** when modifying system files (`sudo vim /etc/hosts`).
- Always **backup** critical configuration files before editing.



