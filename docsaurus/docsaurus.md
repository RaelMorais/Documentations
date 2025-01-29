<h1>Docsaurus Commands</h1>

<h1>Using CMD</h1>

1. ```winget install Schniz.fnm`` 

2. ```fnm install 22``

3. ```node -v``` Check Node version

4. ```npm -v``` Check Npm version

or

```https://nodejs.org/en/download```

<h1>Docsaurus Initial Commands<h1>

<p>Init and installing Docsaurus</p>

``` npx @docusaurus/init@latest init <nome> classic```

You can use ```--javascript``` or ```--typescript``` to define the language of you preference

Later you use ```cd <nome>``` to nav for you directory

in your directory use ```code .``` to open VSCODE, in VSCODE terminal, use ```npm run start``` for start docsaurus

<h1>Create files or docs</h1>

To create a page in Markdown, simply create a .md or .mdx file inside the docs/ folder (for documentation) or the src/pages/ folder (for custom pages).

    1. Inside the docs/ folder, create a new Markdown file. 
    /docs/exemple.md
    
    In example.md uses 

    id: my-home-doc > id for you page 
    title: Teste > title for you page

    It creates the routes automatically, but you can use

        module.exports = {
    sidebar: [
        "my-home-doc",
    ],
    };

    in sidebars.js


