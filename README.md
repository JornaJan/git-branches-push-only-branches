### Test Git

#### Git Branches Commands 

- mkdir project/

- cd project/

- mkdir main-branch/
- mkdir test-1/
- mkdir test-2/

> touch main-branch/README.md

> touch test-1/test-1.js

```js
console.log('test js')
```

> touch test/test-2.html

```html
<div>test html</div>
```

#### cd main-branch/

- git init
- git remote add origin git@github.com:JornaJan/git-demo-test.git
- git add .
- git commit -m 'test'
- git branch -M main
- git push -u origin main

--

- cd ..
- cd test-1/
- git init
- git remote add origin git@github.com:JornaJan/git-demo-test.git
- git add .
- git commit -m 'test-1'
- git checkout -b test-1
- git push origin test-1

--

- cd ..
- cd test-2/
- git init
- git remote add origin git@github.com:JornaJan/git-demo-test.git
- git add .
- git commit -m 'test-2'
- git checkout -b test-2
- git push origin test-2


