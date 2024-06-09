# labset.org

build with [confluence-static-site](https://github.com/viqueen/confluence-static-site)

### install it

```bash
nvm install
yarn
```

### build it

- setup env vars

```bash
yarn site:env
```

- extract confluence content

```bash
yarn site:extract
```

- build site

```bash
yarn site:build
```

- firebase preview

```bash
yarn site:firebase:local
yarn site:firebase:preview
```

- firebase deploy

```bash
yarn site:firebase:deploy
```
