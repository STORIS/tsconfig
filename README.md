# @storis/tsconfig

This package contains the standard TypeScript configurations for packages used by [STORIS](https://www.storis.com).

## Installation
`@storis/tsconfig` is available as an [npm package](https://www.npmjs.org/package/@storis/tsconfig).

```sh
npm install @storis/tsconfig
```

## Usage

### Peer dependencies

The package relies on the following peer dependencies:

- `typescript`

### Configuration

#### Node 16
Add the following to your typescript configuration file (e.g. `tsconfig.json`):
```
{
  "extends": "@storis/tsconfig/node16/tsconfig.json",
}
```

#### React
Add the following to your typescript configuration file (e.g. `tsconfig.json`):
```
{
  "extends": "@storis/tsconfig/react/tsconfig.json",
}
```

## License
This project is licensed under the terms of the [MIT license](/LICENSE).
