When I first started using vim I don't know what to do, all I did was to just use it to edit files, while vimscript, basic keybinds, modals in vim is used in my workflow, most of the features are underutilized or used inefficiently. 

So I relearn VIM, so I actually started using VIM somewhere in early 2021 and stopped at late 2022 while only knowing the basics.

Now I use Neovim, and here are the things that I learned along the way.

I hesitate using lua in neovim cuz I don't know lua (lazy to learn another programming language), and I got used to vimscript. I'm only using nvim for now because of its core features and more plugins support.
# Good Learning materials

The best and official learning materials for beginners is `nvim +Tutor` and `:help` for references how to use specific commands or features.

But there are other good learning materials and its part:
* [Learn VIM Progressively](https://yannesposito.com/Scratch/en/blog/Learn-Vim-Progressively/) - Probably a good start and reference to learn vim for beginners.
- [Learn VIMScript the hardway](https://learnvimscriptthehardway.stevelosh.com/) - Pretty good if learning vim commands syntax.
- [Difference between map and noremap](https://stackoverflow.com/questions/3776117/what-is-the-difference-between-the-remap-noremap-nnoremap-and-vnoremap-mapping) - I got pretty confused here but `noremap` is objectively the best since I can be specific at keybinds and not to recursively remap keybinds from mapped keybinds, mostly I don't want that to happen and to minimize the complexity of my vimscript.
- [X vs WQ](https://www.reddit.com/r/vim/comments/sftrw5/x_vs_wq/) - I keep using X because it preserves timestamp if the file wasn't changed, while WQ saves and changes timestamp no matter what, but both does its similar main purpose

