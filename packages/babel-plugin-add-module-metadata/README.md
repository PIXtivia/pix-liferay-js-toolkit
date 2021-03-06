# babel-plugin-add-module-metadata

> Add AMD modules' metadata to the manifest.json file.

## Installation

```sh
npm install --save-dev babel-plugin-add-module-metadata
```

## Usage

Add the following to your `.babelrc` file:

**Without options:**

```json
{
	"plugins": ["add-module-metadata"]
}
```

## Technical Details and Options

This plugin scans JS modules for certain patterns of code and adds metadata to
the `manifest.json` file generated by the `liferay-npm-bundler`.

Such metadata may be used to describe the module prior to its load or parse.
