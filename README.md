# FreeMarker for Visual Studio Code
FreeMarker language colorization extension for Visual Studio Code. You can read more about FreeMarker [here](http://freemarker.incubator.apache.org/).

## Usage
[Install](https://marketplace.visualstudio.com/items?itemName=dcortes92.FreeMarker) the extension and open any `.ftl` file.

![FreeMarker Syntax Highlight](/images/vscode-freemarker-syntax.png "FreeMarker Syntax Hightlight")

This is based on the TextMate bundle found on [this](https://github.com/bburbach/textmate-freemarker-bundle) repo.

Alternative FreeMarker syntax with square brackets is fully supported.

### Snippets
Type **#** followed by the first letters of a FreeMarker tag name and the editor will propose you all the available autocomplete options. Snippets are also available for alternative FreeMarker syntax. They will have the same shortcuts of regular ones, with an underscore \_ character at the end. For instance:
* with **#if** shortcut, you will get:
    ```
    <#if (condition)>
        
    </#if>
    ```
* while with **#if\_** shortcut the result will be:
    ```
    [#if (condition)]
        
    [/#if]
    ```

![FreeMarker Snippet Example](/images/vs-freemarker-snippet-example.gif "FreeMarker Snippet Example")

#### Snippets list

Shortcut | Description 
---------|---------
\#dir | Directive
\#d | Simple Directive
\#m | Macro definition
@ma | Macro
@m | Simple Macro
\#a | #assign short
\#assign | #assign long
\#l | #local short
\#local | #local long
\#g | #global short
\#global | #global long
\#set | #setting short
\#setting | #setting long
\#if | #if
\#e | #else
\#eif | #elseif
\#li | #list
\#include | #include
\#imp | #import
\#function | #function / #return
\#sw | #switch / #case / #default
\#ca | #case
\#att | #attempt / #recover

## Contributing

Contributions are welcome. Fork the repo and create a pull request with your changes.