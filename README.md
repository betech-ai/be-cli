# ddd-generate

## Usage

Install from git:
```
$ npm i -g git@github.com:BB-Today/be-cli.git
```

Or install from local git repo to debug/develop new features
```
$ git clone git@github.com:BB-Today/be-cli.git
$ cd ddd-generate && npm i -g .
```

Then, use cli in DDD project root:
```
$ cd DDD-Project
$ ddd-generate --name SomeEntity --dir some-entity
$ OR ddd-generate -n SomeEntity -d some-entity
```

##### Don't forget to build after update some code!
```
$ pnpm build
```
