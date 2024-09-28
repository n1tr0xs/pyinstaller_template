# Pyinstaller template


## Mainloop:
1. Push commits
2. Push tag
```
git tag <tagname> && git push origin <tagname>
```
If u need rebuild tag:
```
git tag -d <tagname> & git push -d origin <tagname> & git tag <tagname> & git push origin v1.0
```