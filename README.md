# README

## Extension Pack Code Generation

```
npm install -g yo generator-code
```


Run the following command and follow the prompt to fill in desired values:

```
yo code

> New Extension Pack

Add the currently installed extensions to the extension pack? (Y/n) Y 
What's the name of your extension? Dev - Extensions Pack 
What's the identifier of your extension? dev-extensions-pack 

```


Choose **“New Extension Pack”** from the list to proceed. Select *Yes* if you want to include your currently installed extensions to the extension pack. Here, I’m going to select *No* and add the extensions later.


After the process is complete, change the directory to the extension pack `myfirstextensionpackand` open it on VSCode editor by entering `code .` on the console. Once on the editor, open` package.json` and you will find a section to enter your favorite extensions Ids to include in your extension pack.

## Packaging

Make sure you have Node.js installed. Then run:

`npm install -g vsce`

You can use vsce to easily package and publish your extensions:

```
vsce package

vsce publish <version>
```
