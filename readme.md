# node js

- [why node?](#why-node?)
- [USEFUL LIBS](#USEFUL-LIBS)
- [install modules ](#install-modules )
- [installing cli modules](#installing-cli-modules)
- [Creating a package.json file](#Creating-a-package.json-file)
- [](#)
- [](#)

## why node?
- built on top of chromes js runtime v8 engine. 
- write fe and be in same language
    - share code and data structures
    - `share libraries`
    - a game you can use the same algo
    - same encryption libs
    - same `data models` 
    - js is a dynamic language type is determined by value
    - i.e. loosely typed not strongly
    - works well with json


# USEFUL LIBS

**nodemon** install globally.
it continuously runs your program, no need to execute each time .

`nodemon myprogram.js`

**lodash**  
Has math functions. 



# chat app 

- features `http` requests from front end to backend
- as well as `web sockets` through `socket.io`
    - allows auto push notifications

- Using mongo db and mlabs 

# async vs sync

- sync is blocking
- networking/file system access are both slow 

# callback

- for async functions
- `they call you back` once they are available
- basically callback func executes when primary fun complete

# install modules 

`use npm` just like pip
but installs it in root dir

as `node_modules`

**referencing node modules** if installed using npm you don't need to use path ref. 


## installing cli modules

just use global flag

```
npm install -g nodemon
```


# Creating a package.json file  
  
- run npm init 
- pick defaults 

```js
npm init
```  
  
- Fast all defaults

```
npm init --yes
```