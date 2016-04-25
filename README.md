JS dotfiles
-----------

Quick setup for new Node.js projects

```
git clone git@github.com:Xiphe/js-dotfiles.git my-project-name &&
cd my-project-name &&
rm -rf .git &&
rm README.md &&
git init &&
git add . &&
git commit -m'chore(js-dotfiles): initiate dotfiles' -m'https://github.com/Xiphe/js-dotfiles' &&
npm init &&
npm install --save-dev --save-exact eslint-config-airbnb-base eslint-plugin-import eslint &&
git add . &&
git commit -m'chore(package): add package.json'
```

### Old custom eslint Version

_deprecated_

```
git clone git@github.com:Xiphe/js-dotfiles.git js-dotfiles-tmp
cd js-dotfiles-tmp
git reset d3702c42ce4c591047cc35553ae5a31918ff0ab1 --hard
rm -rf .git
rm README.md
git init
git add .
git commit -m'initiate dotfiles' -m'https://github.com/Xiphe/js-dotfiles'
cd ..
mv js-dotfiles-tmp my-project-name
```

### Old JSHint + JSCS Version

_deprecated_

```
git clone git@github.com:Xiphe/js-dotfiles.git js-dotfiles-tmp
cd js-dotfiles-tmp
git reset 408b27a6696662a221537496ef7f208c9c6bf241 --hard
rm -rf .git
rm README.md
git init
git add .
git commit -m'initiate dotfiles' -m'https://github.com/Xiphe/js-dotfiles'
cd ..
mv js-dotfiles-tmp my-project-name
```


LICENSE
-------

> The MIT License
> 
> Copyright (c) 2015 Hannes Diercks
> 
> Permission is hereby granted, free of charge, to any person obtaining a copy
> of this software and associated documentation files (the "Software"), to deal
> in the Software without restriction, including without limitation the rights
> to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
> copies of the Software, and to permit persons to whom the Software is
> furnished to do so, subject to the following conditions:
> 
> The above copyright notice and this permission notice shall be included in
> all copies or substantial portions of the Software.
> 
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
> IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
> FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
> AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
> LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
> OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
> THE SOFTWARE.
