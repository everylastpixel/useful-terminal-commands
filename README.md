# useful-terminal-commands

## Vue/Nuxt workflow terminal commands for day-to-day use

**Install latest version of node:**  
nvm install --lts

**Things I need on every machine:**

- Node
- npm
- @vue/cli

## npm/node

**To check global installed packages:**  
`npm ls -g --depth=0`

That lists all global installed packages with depth=0. That mean that it doesn't output dependencies of the packages.

**To uninstall global packages:**  
npm uninstall -g package-name

**_Do not uninstall the npm package itself..._**  
**But you can update your npm version with npm:**  
npm install npm -g

**You can get the installed versions with these commands:**
node -v
npm -v

npm outdated
then:
npm update <package>
or:
npm update - to update everything

## Vue.js

**Install the CLI**  
npm install -g @vue/cli

**Create a Vue project**  
vue create <name-of-project>

**Start up development server**  
cd into project folder  
npm run serve

**Start the UI dashboard**  
vue ui

**Buidl the Vue app**  
npm run build

## Nuxt.js

**Create a Nuxt App**  
npx create-nuxt-app <project-name>

**To use css pre-processors:**  
npm install --save-dev sass sass-loader@10 fibers

**To use Global sass variables:**  
npm install --save-dev @nuxtjs/style-resources  
(See https://github.com/nuxt-community/style-resources-module for more)

**Start up the Nuxt dev server**  
cd into project folder  
npm run dev

**Build project**
(set target in nuxt.config.js)
npx nuxt build

**generate static site in dist directory**
npx nuxt generate

**start dev server for static site**
npx nuxt start
