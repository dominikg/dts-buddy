# dts-buddy changelog

## 0.1.13

- Allow `modules` to be specified via the CLI ([#35](https://github.com/Rich-Harris/dts-buddy/pull/35))

## 0.1.12

- Remove `declare module` blocks ([#33](https://github.com/Rich-Harris/dts-buddy/pull/33))

## 0.1.11

- Handle default exports ([#32](https://github.com/Rich-Harris/dts-buddy/pull/32))

## 0.1.10

- Override `lib` option ([#31](https://github.com/Rich-Harris/dts-buddy/pull/31))

## 0.1.9

- Use reference directives for external ambient imports ([#29](https://github.com/Rich-Harris/dts-buddy/pull/29))

## 0.1.8

- Include external ambient imports ([#27](https://github.com/Rich-Harris/dts-buddy/pull/27))

## 0.1.7

- Bump `locate-character` dependency

## 0.1.6

- Preserve descriptions in JSDoc comments, remove brackets from parameters

## 0.1.5

- Always preserve JSDoc comments with `@default`, `@deprecated` and `@example` tags

## 0.1.4

- Prevent unnecessary `_1` suffixes

## 0.1.3

- Preserve `@deprecated` tags
- More forgiving `pkg.exports` parsing in CLI
- Use `ts-api-utils` instead of brittle `node.kind` checks

## 0.1.2

- Work on Windows

## 0.1.1

- Ensure inline dependencies are correctly marked

## 0.1.0

- Treeshaking
- Robust renaming

## 0.0.10

- Ignore `outDir` setting

## 0.0.9

- Warn instead of failing on invalid `pkg.exports` entries

## 0.0.8

- Preserve `@example` and `@default` tags

## 0.0.7

- Include `types` in `pkg.files`

## 0.0.6

- Tidier output

## 0.0.5

- Remove unwanted `declare` keywords from `.d.ts` output

## 0.0.4

- Add a CLI

## 0.0.3

- Generate declaration maps

## 0.0.2

- Only export things that are exported

## 0.0.1

- First release
