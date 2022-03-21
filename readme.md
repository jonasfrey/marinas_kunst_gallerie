# vscode setup for threejs 

Make sure you’ve installed node.js and run:

  npm install typings --global
Go to your project directory, run:

  typings init
There will be a typings.json file generated.

Now search for the three.js syntax file in DefinitelyTyped:

  typings search three
It will show all matched results. Find the one we need, the name is three

Install three

  typings install three --save --global
If this doesn’t work, try specify a domain for the typings, use this:
  typings install dt~three --save --global
Now with 1.x.x VSCode, we need to generate a jsconfig.json file in the root of the project folder by clicking the light bulb button at the bottom right.

## src 


 http://shrekshao.github.io/2016/06/20/vscode-01/
