# web-editor-template

This repo is a template for following along with the Lisp tutorial I am writing. It is based on [mal](https://github.com/kanaka/mal), the Make a Lisp process, but instead of typing code into a REPL prompt, forms are evaluated in a web editor so we'll have things like syntax highlighting, bracket matching, use of the browser console for debugging, and access to the following commands for live evaluation:

1. Shift+Enter = Eval cell
2. Alt+Enter = Eval top-level form
3. Ctrl/Cmd+Enter = Eval at cursor

## Running

In the project root, run:

```
npm install
npm run dev
```
