# CS50 Web: Lcture 1 Git 

## Outline 
* Git commands
* HTML basics 

### Version Control - Git 
1. Benefits of Git: 
	* Keep track of changes to code. 
	* synchronize code between diff people. 
	* test changes to code without losing the orignal. 
	* revert back to old version of code. 
2. `> git clone <url>`
3. `> git add <filename>`
4. `> git commit -m "message"`
5. `> git status` 
6. `> git push`
7. `> git pull` 
8. merge conflicts
	* git will try to do this whenever it can. 
	* but still it might not be able to resolve all conflicts. 
	* between "<<<<HEAD" and "=====" is your change. 
	* between "=====" and ">>>>> commit no." is the remote change. 
9. `> git log` 
10. `> git reset`
	* `> git reset --hard <commit no.>`: reset to that commit version (only the first few characters is sufficient for the commit no.). 
	* `> git reset --hard origin/master`: reset to the original copy from the remote (e.g. Github). 

### HTML
1. HTML tags
	* `<!DOCTYPE html>`: specify HTML5 version
	* `<html>`
	* `<head>`
	* `<title>`
	* `<body>`
	* `<h1>` .. `<h6>`
	* `<ul>` `<li>`
	* `<ol>` `<li>`
	* `<img src="url" height="num or percent" width="num or percent">`: no end tag
	* `<table>` `<tr>` `<th>` `<td>`
	* `<form>`
	* `<input type="" placeholder="" name="">`: text field - no end tag 
	* `<button>`
2. Document Object Model: a tree structure 
3. CSS options
	* add `style=""` to tags
	* add `<style>` tag to `<head>`
	* `<link rel="stylesheet" href="***.css">` and have a separte file `***.css`
