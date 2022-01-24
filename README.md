# useful-terminal-commands

## My go-to terminal commands for day-to-day use

**Install latest version of node:**  
nvm install --lts

**Things I need very machine:**

- Node
- npm 6.14.11
- @vue/cli

## npm/node

**To check your global installed packages you can type:**  
npm ls -g --depth=0

That lists all global installed packages with depth=0. That mean that it doesn't output dependencies of the packages.

**You can uninstall global packages with:**  
npm uninstall -g package-name

Please do not uninstall the npm package itself...  
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

## vue

**Install the CLI**  
npm install -g @vue/cli

**Create a Vue project**  
vue create <name-of-project>

**Run the Vue server**  
npm run serve (to start up development server)
cd into project directory first

**Start the UI dashboard**  
vue ui

**Buidl the Vue app**  
npm run build

##Nuxt

**Create a Nuxt App**  
npx create-nuxt-app <project-name>

**To use css pre-processors:**  
npm install --save-dev sass sass-loader@10 fibers

To use Global sass variables:
npm install --save-dev @nuxtjs/style-resources
See https://github.com/nuxt-community/style-resources-module for more

cd <project-name>
npm run dev - run dev server

npx nuxt build (set target in nuxt.config.js)

npx nuxt generate (generate static site in dist directory)

npx nuxt start (start dev server for static site
