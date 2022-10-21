# @vercel/edge-config

## 0.1.0-canary.2

### Minor Changes

- edf1cc9: Add getAll() method

  - `getAll()` allows fetching all items of an Edge Config
  - `getAll(keys: string[])` allows fetching a subset of the Edge Config's items

### Patch Changes

- 264ab8d: Throw when attempting to read value of non-existing Edge Config

## 0.1.0-canary.1

### Minor Changes

- Allow reading embedded edge configs