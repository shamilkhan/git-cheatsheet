# ⚒ 🐻‍❄️ Git Cheatsheet

## 🐯🧛‍ Branches
### 🧟 Move branch to commit `hash`
#### checkout master to commit hash:
```sh
git branch master hash/branch name -f
git checkout -B master
```
### 👯‍♀️ Show commit changes
#### By default show current commit changes:
```
git show
```
##### output: 
```js
+const foo = () => {
+ return "bar";
+ }
- cosnt deletedFn = () => "deleted"
- const deletedLine = "deletedLine";
```
#### Get changes by hash/baranchName
```
git show hash
git show development
```
### Show changes N commits back
#### one commit back
```
  git show HEAD~
```
#### two commits back
```
  git show HEAD~~
  git show HEAD~2
```
#### N commits back
```
  git show HEAD~~~(N count)
  git show HEAD~N
```


