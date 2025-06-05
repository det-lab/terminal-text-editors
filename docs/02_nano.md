# Nano
One of the main benefits to `nano` is the two help lines at the bottom of the window, showing you a list of commands that you can use. 

![nano window](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2a/GNU_nano-6.4_screenshot.png/800px-GNU_nano-6.4_screenshot.png)

Each of the `^` symbols is meant to be typed by the user as `CTRL`, so you can access `Help` as `CTRL+G`, `Exit` by typing `CTRL+X`, etc.

The latest version of `nano` can be downloaded by following [this link to the official site.](https://www.nano-editor.org/download.php)

## Basic Commands:
Here are the core actions that you'll use most often in `nano`.
### Open a File
```bash
nano filename.txt
```
* Opens the file if it exists, or creates a new one if it doesn't.

### Edit or Insert Text

* Simply start typing. `nano` is always in insert mode.

* Use arrow keys to move the cursor. 

### Save/Write Changes

* Press `CTRL+O` (`Write Out` option)

### Close the File

* Press `CTRL+X`

If you've made unsaved changes, `nano` will ask:
```java
Save modified buffer (ANSWERING "No" WILL DESTROY CHANGES)?
```

* Press `N` to **discard changes** and exit.

### Search for Text

* Press `CTRL+W`

* Type your search term and press `Enter`

* Press `CTRL+W` again and then `Enter` to find the next match.

By default, `nano` does not use regex. It instead searches using plain text. However, you can enable regex with the `-R` or `--regexp` option:
```bash
nano --regexp filename.txt
```
Now when you press `CTRL+W` to start a search you can type a regular expression pattern and then press `Enter` to find matches.

For further questions regarding `nano`, refer to the documentation by following [this link.](https://www.nano-editor.org/docs.php)

---

[Click here](03_vim.md) to continue on to the next section to learn the basics for `Vim`.