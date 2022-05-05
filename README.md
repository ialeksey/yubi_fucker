# yubi_fucker

```
git clone https://github.com/ialeksey/yubi_fucker.git
cp yubi_fucker/yubi_fucker /usr/local/bin
chmod +x /usr/local/bin/yubi_fucker
```

```
alias yb='yubi_fucker -r'
alias ybd='nohup yubi_fucker -l 2>&1 >/dev/null &'
alias ybk='ps aux | grep yubi_fucker | awk '\''{print $2}'\'' | xargs kill -9 >/dev/null 2>&1'
```


