# Vue Starter


#### Clone the repo

```bash
mkdir -p  ~/GitHub/rkiel & cd $_
git clone git@github.com:rkiel/vue-starter.git
```

#### Install packages

```bash
cd ~/GitHub/rkiel/vue-starter
yarn install
```

#### Atom

```bash
apm install language-vue
```

#### Create a sample project

List available templates

```bash
yarn run vue list
```

Create a new Vue project (using webpack template)

```bash
mkdir -p ~/GitHub/yourstuff
yarn run vue init webpack $_/sample
```

Start your Vue project (development)

```bash
cd ~/GitHub/yourstuff/sample
yarn install
yarn run dev
```

Build your Vue project (production)

```bash
cd ~/GitHub/yourstuff/sample
yarn install
yarn run build
find dist -type f | sort
```
