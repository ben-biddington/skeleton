```sh
$ npm run build && node dist/adapters/cli.js 

> skeleton@1.0.0 build
> npx babel src --out-dir dist --extensions .'ts'

Successfully compiled 2 files with Babel (382ms).
skeleton

```

<dl>  
  <dt>
    chalk v4
  </dt>
  <dd>IMPORTANT: Chalk 5 is ESM. If you want to use Chalk with TypeScript or a build tool, you will probably want to use Chalk 4 for now.
  [Read more](https://github.com/chalk/chalk/releases/tag/v5.0.0)
  </dd>
</dl> 