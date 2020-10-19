# @tivac/stylelint-config

## Installation

```bash
npm install @tivac/stylelint-config --save-dev
```

## Usage

If you've installed locally within your project, add to your `stylelint` config:

```json
{
  "extends": "@tivac/stylelint-config"
}
```

There is also another entrypoint you can use to mix in config options for the `stylelint-order` plugin:

```json
{
    "extends": [ "@tivac/stylelint-config", "@tivac/stylelint-config/order" ]
}
```

### Extending the config

Add a `"rules"` key to your config, then add your overrides and additions there.
