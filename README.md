# 1.Crecte HTML and CSS file

- Your Folder
|-- index.html <-- New
|-- style.css  <-- New

# 2.Crecte Defaulf ``` package.json  ``` 

```bush
npm init -y
```

## now
- Your Folder
|-- index.html
|-- style.css
|-- package.json <-- New

# 3.Install node package in dependencies

-- dependencies is install in dev mode 

``` postcss ``` and  ``` postcss-cli ```  

```bush
npm i -d postcss postcss-cli
#OR
npm i --save-dev postcss postcss-cli
```

## now
- Your Folder
|-- node_modules <-- New
|-- index.html
|-- style.css
|-- package.json
|-- package-lock.json <-- New

# 4.Edit content in HTML and CSS file

> - Your Folder
> |-- index.html
> ```bush
> &#60;head>
>     &#60;link rel="stylesheet" href="style.css">
> &#60;/head>
> &#60;body>
>     &#60;p class= "color-5">lorem60 -- asdksjdoiwjoajsdsj</p>
> &#60;/body>
> ```