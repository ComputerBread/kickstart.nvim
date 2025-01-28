# about the branch mine

mine, is the branch with my own stuff, 

why? ok neovim updated to 0.10, I installed a bunch of things, and started
breaking, so I updated to 0.10, because I did little modif, I was too lazy to
update that shit myself, so I wanted to benefit from the kickstart repo,

so the idea is: keep the master branch in sync with kickstart, then merge master
with mine

```bash
git co master
git fetch upstream
git reset --hard upstream/master
git co mine
git merge master
git push

# git remote add upstream git@github.com-cb:nvim-lua/kickstart.nvim.git
```

