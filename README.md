# Vue Starter


#### Clone the repo

```bash
mkdir -p  ~/GitHub/rkiel && cd $_
git clone git@github.com:rkiel/vue-starter.git
```

#### Install packages

```bash
cd ~/GitHub/rkiel/vue-starter
yarn install

# npm install
```

#### Atom

Install Atom language support for the `.vue` file type.

```bash
apm install language-vue
```

#### Project Templates

The Vue CLI supports several official Vue project templates.  To see a list of available templates,

```bash
yarn run vue list

# npm run vue list
```

For example, the available official templates:

* browserify - A full-featured Browserify + vueify setup with hot-reload, linting & unit testing.
* browserify-simple - A simple Browserify + vueify setup for quick prototyping.
* pwa - PWA template for vue-cli based on the webpack template
* simple - The simplest possible Vue setup in a single HTML file
* webpack - A full-featured Webpack + vue-loader setup with hot reload, linting, testing & css extraction.
* webpack-simple - A simple Webpack + vue-loader setup for quick prototyping.

#### Create A Vue Project

Let's choose to use the webpack template.

```bash
mkdir -p /path/to/your/project/name
yarn run vue init webpack /path/to/your/project/name 

# npm run vue init webpack /path/to/your/project/name
```

The Vue CLI will prompt you.  Click **Enter** to select defaults.  For prompts with multiple options, use arrow keys to change.
* Target directory exists. Continue? **Yes**
* Project name **replace project path name with just your project name**
* Project description **enter a simple description**
* Author **should default to your GitHub config user name and email**
* Vue build
    * **Runtime + Compiler**: recommended for most users 
    * Runtime-only: about 6KB lighter min+gzip, but templates (or any Vue-specific HTML) are ONLY allowed in .vue files - render functions are required elsewhere 
* Install vue-router? **Y**
* Use ESLint to lint your code? **Y**
    * **Standard** (https://github.com/standard/standard) 
    * Airbnb (https://github.com/airbnb/javascript) 
    * none (configure it yourself) 
* Set up unit tests **Y**
    * Jest 
    * **Karma and Mocha**
    * none (configure it yourself) 
* Setup e2e tests with Nightwatch? **n**


#### Development

Start your Vue project.

```bash
cd /path/to/your/project/name
yarn install
yarn run dev 

# npm install
# npm run dev
```

Open your browser to view the home page.

* [http://localhost:8080](http://localhost:8080)

To see live reload in action

* Edit `src/components/HelloWorld.vue`
* In the `script` section, change the value of `msg`
* Save the file and see the browser page automatically update

Put project under source control.

```bash
git init
git add .
git commit  -m "Initial commit"
```

#### Production

Build your Vue project

```bash
cd /path/to/your/project/name
yarn install
yarn run build

# npm install
# npm run build
```

Here's what the production distribution (`dist`) looks like.

```bash
find dist -type f | sort
```


