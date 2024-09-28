# Pyinstaller template

## How to use:
1. Copy tag_release.yml to your repo.
3. All source code files must be in src directory.
2. `build.spec`, `requirements.txt`(either empty or not) must be in repo root directory.

## Mainloop:
1. Push commits
2. Push tag
```
git tag <tagname> && git push origin <tagname>
```
Fast tag repush:
```
git push origin :<tagname> & git tag -f <tagname> & git push -f origin <tagname>

git tag -d <tagname> & git push -d origin <tagname> & git tag <tagname> & git push origin v1.0
```