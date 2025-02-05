# win2xcur
This is a shell script to convert windows cursor theme to linux x11 cursor theme.

## depend
python package `win2xcur`

## install depend
```bash
pip install win2xcur
win2xcur
```

More infomation about `win2xcur` in [here](https://github.com/quantum5/win2xcur)

## how to use
```bash
cd path_to_your_windows_cursors
git clone 
./win2xcur.sh <input_dir> <output_dir>
```

## make sure it's right
Your must write the `index.theme`.
```txt
[Icon Theme]
Name=your cursor theme name
Comment=yout cursor theme descriptor
```
## install your cursor theme
Move or copy your cursors to `~/.icons` or `/usr/share/icons`.
See your desktop manual.
