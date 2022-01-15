# Basic NPM Commands [:house:](../README.md)

### Development

#### Check NPM version

```console
npm -v
```

#### Create new project

```console
npm init
```

#### Add dependency to project

```console
npm i <package-name> -S
```

#### Add a development dependency to project

```console
npm i <package-name> -SD
```

#### Install all project dependencies

```console
npm i 
```

#### Execute a script configured in package.json

```console
npm run <script-name>
```

### Testing

#### Execute tests

```console
npm test
```

### Security

#### Scan project for vulnerabilities and list those

```console
npm audit
```

#### Scan project for vulnerabilities and compatible  updates to fix those

```console
npm audit fix
```
