## lerna starter

### install lerna

```bash
yarn init -y

yarn add lerna -D
```

### init

```bash
# https://github.com/lerna/lerna/tree/main/commands/init#readme
# init project
npx lerna init

# init help
npx lerna init --help
```

### create

```bash
# https://github.com/lerna/lerna/tree/main/commands/create#readme
# create package
npx lerna create <name> [loc]

```

###  add 
```bash
# https://github.com/lerna/lerna/tree/main/commands/add#readme
npx lerna add <package>[@version] [--dev] [--exact] [--peer]

npx lerna add react [packages/dirname]

# eg.
npx lerna add rxjs packages/utils
```

### link

```bash
npx lerna link
```


### clean

```bash
# clean all node_modules
npx lerna clean
```

### bootstrap

```bash
# reinstall dependencies
npx lerna bootstrap
```

### exec

```bash
npx lerna exec -- [command]
```

### run

```bash
npx lerna run test
```

### version


### publish





