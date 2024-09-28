# Pyinstaller template

## How to use:
1. Set `env.app_name`.
2. Specify pyinstaller options.
3. `requirements.txt`(either empty or not) must be in repo root directory.

## Mainloop:
1. Push commits
2. Create and push tag
```
git tag -f <tagname> && git push origin <tagname>
```
3. Fast tag repush:
```
git push origin :<tagname> & git tag -f <tagname> & git push -f origin <tagname>
```
