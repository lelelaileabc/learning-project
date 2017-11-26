# learning-project

### npm install问题
1. gyp ERR! stack Error: Can't find Python executable "python", you can set the PYTHON env variable.

    原因看node-gyp的安装需求
    >Install Python 2.7 (v3.x.x is not supported), and run npm config set python python2.7 (or see below for further instructions on specifying the proper Python version and path.)
    >
    >https://github.com/nodejs/node-gyp

    下载安装python2.7 https://www.python.org/downloads/
    
1. Node Sass could not find a binding for your current environment: Windows 64-bit with Node.js 8.x

    执行
    npm rebuild node-sass
