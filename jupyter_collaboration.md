### Using jupyter notebooks for collaboration

Challenges:
- git design doesn't offer good support for jupter notebooks
- disconnect between jupyter and git

#### Techniques
`git add -p` - stage only the relevant data, ignore metadata
`Cell -> All Output -> Clear` - to clean jupyter metadata

#### Tools
- pre save jupyter notebook hook to clear the cells
- smudge filter (eg. convert tab to spaces when checking out .txt files)
- clean filter (eg. the other way around)
- `pip install nbstripout` - adding filters by default
- `nbdime.readthedocks.io` - diffing and merging jupyter notebooks, comes with git integration off the shelf. 
- 

```
pip install nbdime
nbdime config-git --enable
git diff # renders diff in terminal
git merge # insert conflict markers
```
Uses `nbdime` for jupyter related changes and git for python, r and code. 

Guy works at [SherlockML](https://shcerlockml.com)