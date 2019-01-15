# bthpug

Övning på Pug, https://pugjs.org/api/getting-started.html 
anv. pug-cli https://www.npmjs.com/package/pug-cli
https://www.npmjs.com/package/pug

## Installera först Node.js https://nodejs.org/en/

Se till att ni har NPM i path så ni kan köra det i powershell.
För att installera pug globalt med npm kör.  
  `npm install -g pug-cli`

### Om du klonar detta repo så...
Strukturen har 2 mappar för filerna.
* src/ mapp med templater
* dist/ output mapp med/för html

Kör `npm install`

För att skapa html kör, du kommer då hitta din genererade html i dist mappen.
`pug src --pretty --out dist`

Jag har tagit viss text/information from orginalsidan, lagt till bootstrap och utgått från exempel-layouterna.
Du kan använda detta som en grund för ditt arbete.

Om du skapar ett repo för ditt arbete så kolla in .gitignore för detta projekt.
