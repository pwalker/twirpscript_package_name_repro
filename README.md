# Repro steps

```sh
npx twirpscript
yarn build
```

If you rename the `Foo` message in `first.proto` to `Bar`, the protos compile, so I think this is just a name collision.
