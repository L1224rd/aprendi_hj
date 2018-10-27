# 02/08

**Ubuntu** - `sudo -s`: loga no terminal como root, não precisa usar sudo antes de cada comando, Ctrl-c para sair.

**JS** - Immediately Invoked Function Expressions (IIFEs)
```
(() => {
  console.log('hey');
})();

// hey
```

**JS** - Diferença entre `var` e `let`: `let` faz tudo que `var` faz, mas `let` só pode ser declarada uma vez e está restrita ao seu escopo ({})

**Boas Práticas** - [eslint](https://eslint.org/), [husky](https://github.com/typicode/husky) e `npm scripts`

**JS** - `eval()`: roda o código passado como função em forma de string. Ex. `eval('console.log(\'hey\')')`

# 03/08

**GitHub** - a extensão `.md` representa arquivos de documentação Markdown

**Ngrok** - Acessar localhost através de um link

# 22/08

**Debugging in Chrome** - $ `node --inspect-brk` then access [chrome://inspect/#devices](chrome://inspect/#devices)

**Lodash** - Easy way of working with arrays, numbers, objects, strings, etc.

**Batch at Ubuntu startup** - Search for Startup Aplications

# 01/09

**not function jquery** - Excludes passed jquery selector

**jquery delegated event handlers** - To bind events to elements created by jquery

# 02/09

**JSON Viewer** - Maravilha!!! Prettifies json raw data at the browser [JSON Viwer](https://chrome.google.com/webstore/detail/json-viewer/gbmdgpbipfallnflgajpaliibnhdgobh/related?hl=pt-BR)

**JSON at console** - `JSON.stringify(object, undefined, 2)` to see it pretty at the console

**encodeURIComponent** - to format stings into valid URL format. (%20, etc)

# 03/09

**GitLens** - See who coded each line

# 05/09

**Annyang** - [JS SpeechRecognition](https://www.talater.com/annyang/)

# 26/10

**Node duplicate request** - If 2 requests are being sent to `*` route, it's because of `/favicon`

# 27/10

**Delete all branches but master** - `git branch | grep -v "master" | xargs git branch -D`

