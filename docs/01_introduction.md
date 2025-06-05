# Introduction
From the top of this lesson it should be stated that terminal-based/command-line text editors are useful mainly for advanced programming. They definitely have their advantages over their GUI-based counterparts, such as being less memory intensive, more ubiquitous, and more efficient for experienced users, but their advantages are often outweighed by the entry-level useability of coding environments such as Visual Studio Code for more basic applications. 

In general, it's recommended to avoid terminal-based text editors unless you have to use them. There are a few times when command-line editing will pop-up automatically, but for the most part these can be rerouted to use GUI editors as well. For instance, here is a [tutorial for running SSH from Visual Studio Code](https://code.visualstudio.com/docs/remote/ssh), and here's another one for [making Visual Studio Code your default git editor](https://dev.to/deadlybyte/make-vs-code-your-default-git-editor-j6d) (although you can also avoid being in an editor for git by using an application such as Github Desktop or by using the command `git commit -m "commit message here"`).

All that being said: when utilized to their fullest, text editors can streamline several tasks in ways that GUIs would struggle to match. In this lesson, we're going to go over the bare-bones basics of terminal-based text editors for the three most common options: `Vim`, `Emacs`, and `nano`, with short instructions for each on how to:
* Open a file,
* Edit or insert text into a file,
* Save a file and keep your changes,
* Close a file and/or discard your changes, and
* Search for text within a file.
## Choosing an editor
When selecting an editor, the right choice for you will depend on your needs, experience level, and editing habits:

* `nano` is best for beginners or quick edits, with a simple interface that includes helpful commands at the bottom of the screen. If you're only intending on changing a config file or writing a short script without learning many commands, `nano` is ideal. 

* `Vim` offers speed and precision for experienced users. Once learned, `Vim` is extremely efficient for navigating and editing code or text at high speed. Choose `Vim` if you work frequently in the terminal and want a powerful, scriptable tool. 

* `Emacs` is a full-fledged programmable environment, not just an editor. It supports extensive customization, plugins, and even embedded shells or mail clients. It's a strong choice if you prefer a keyboard-driven workflow and want to integrate many tools into a single interface, but has a steeper learning curve than the other two editors. 

This lesson will be working under the assumption of a GNU/Linux installation, such as Ubuntu or Debian, which can be downloaded by following [this link to the official Linux download page.](https://www.linux.org/pages/download/)

---

Let's get started by learning the basics of the easiest of the three options: `nano`. [Click here](02_nano.md) to continue on to the next section.