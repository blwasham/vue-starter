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

The Vue CLI supports several official Vue project templates.  To see a list of available templatesm

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
mkdir -p /path/to/your/project
yarn run vue init webpack /path/to/your/project/name 

# npm run vue init webpack /path/to/your/project/name
```

#### Development

Start your Vue project.

```bash
cd /path/to/your/project/name
yarn install
yarn run dev 

# npm install
# npm run dev
```

#### Development

Build your Vue project

```bash
cd /path/to/your/project/name
yarn install
yarn run build

# npm install
# npm run build
```

Here's the production distribution.

```bash
find dist -type f | sort
```


