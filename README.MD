# Pyinstaller template

## How to use:
1. Copy tag_release.yml to your repo.
2. `build.spec` must be in repo root directory.
3. `requirements.txt` must be in repo root directory (either empty or not).

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