# eslint-config-adorsys

## Setup

npm install from this repo

```bash
npm i -D eslint git+ssh://git@git.adorsys.de:wow/eslint-config.git
```

Add .eslintrc file with following content

```bash
{
  "extends": "eslint-config-adorsys"
}

```

Add lint script task to package.json

```bash
"scripts": {
  "lint": "eslint ."
  ...
}
```

Run ```npm run lint``` from command line
