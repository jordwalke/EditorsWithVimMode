EditorsWithVimMode
==================

List and summary of all plugins that support a `Vim` keybinding mode. Please send pull requests when you discover a new project including a brief summary.

No Vim emulator perfectly recreates Vim's keybindings, except perhaps Emacs' vim bindings. Specifically, every other Vim emulator does not correctly recreate Vim's undo/redo editing experience which is just as much part of the Vim editing experience as movement commands. 



#####VisualStudio

- `ViEmu` provides excellent support http://www.viemu.com/blog/.

#####Atom

- [`vim-mode-plus`](https://github.com/t9md/atom-vim-mode-plus) is a very faithful recreation of the core Vim keybindings. At the time of writing, it has fewer bugs than the more popular Vim bindings for Atom.

#####Vico

- Extensive support of core Vim keymappings and commands.


#####IntelliJ IDEA

- Through `Ideavim` http://plugins.jetbrains.com/plugin/164?pr=phpStorm


#####Sublime

- `Vintageous` is well supported and is as close to `Vim`'s natural feel/feature as you can achieve in Sublime.
  - Only current issue is that `undo`/`redo` are [critically broken](https://github.com/SublimeText/Issues/issues/107) due to a bug in `Sublime`, not `Vintageous`.
  - Has a very dedicated/supportive developer.

- `Vintage` plugin is crtically broken and not well supported.

#####Vim

- Perfectly supports Vim's keyboard mappings and commands, but has obscure scripting language.

# Works In Progress

#####VSCodeVim

- [VSCodeVim](https://github.com/VSCodeVim/Vim) is just beginning development.
