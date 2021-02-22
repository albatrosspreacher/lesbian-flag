# lesbian-flag

### A simple hack that shows lesbian flag colours in the Languages bar on GitHub

Inspired by this [repository](https://github.com/chrisnager/pride)🏳️‍🌈

## How to change the colours for any repository

Follow these steps: 

1. Add a `.gitattributes` file to your repository
2. Modify and add the following code <br>

```
*.c linguist-language=Postscript
*.css linguist-language=RenPy
*.js linguist-language=EmberScript
*.py linguist-language=Sass
*.rb linguist-language=ECL
```

Replace the extensions ".c" ".css" etc with the file extensions used in your project

3. Push the changes and refresh your GitHub page
