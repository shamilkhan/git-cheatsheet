# ⚒ 🐻‍❄️ Git Cheatsheet

## 🐯 Branches
### Move branch to commit `hash`
#### checkout master to commit hash:
```sh
git branch master hash/branch name -f
git checkout -B master
```
### Show commit changes
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





