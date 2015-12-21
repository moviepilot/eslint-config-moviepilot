# eslint-config-moviepilot
Moviepilot's ESLint config

## Integration

- `npm install --save-dev eslint babel-eslint eslint-config-moviepilot eslint-plugin-react`
- Use the following `.eslintrc` if it's not in the repo (it should!)

```
{
  "extends": "moviepilot"
}
```

Some editors (vim) won't find the local eslint binary, since it will be located under `node_modules`. There's a [nice workaround](http://blog.pixelastic.com/2015/10/05/use-local-eslint-in-syntastic/) for that.
