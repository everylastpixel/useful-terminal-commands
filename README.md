# useful-terminal-commands

## Commands I always need!

**Install latest version of node:**
nvm install --lts

NEED:
Node
npm 6.14.11
@vue/cli

**To check your global installed packages you can type:**
npm ls -g --depth=0

That lists all global installed packages with depth=0. That mean that it doesn't output dependencies of the packages.
You can uninstall global packages with:
npm uninstall -g package-name

Please do not uninstall the npm package itself...
But you can update your npm version with npm:
npm install npm -g

You can get the installed versions with these commands:
node -v
npm -v

npm outdated
then:
npm update <package>
or:
npm update - to update everything

vue
npm install -g @vue/cli

vue create <name-of-project>

npm run serve (to start up development server)
cd into project directory first

vue ui - to start the UI

npm run build - build the app

Nuxt
npx create-nuxt-app <project-name> - create the app

To use css pre-processors:
npm install --save-dev sass sass-loader@10 fibers

To use Global sass variables:
npm install --save-dev @nuxtjs/style-resources
See https://github.com/nuxt-community/style-resources-module for more

cd <project-name>
npm run dev - run dev server

npx nuxt build (set target in nuxt.config.js)

npx nuxt generate (generate static site in dist directory)

npx nuxt start (start dev server for static site
