# Convert Adobe Color Book files (.acb) into JSON

## Usage

```
npm i
coffee index.coffee
```

Alternatively for MacOs / Homebrew:

```
brew install coffeescript
coffee index.coffee
```

This will convert all `color-books/*.acb` files into `converted/*.json`.

## `.acb` files

You will need to copy your Adobe Color Book `.acb` files into `color-books` first before converting.

## `.acb` file format

Please refer to http://magnetiq.com/pages/acb-spec/.

## Adobe Color Books

Since the details of the license for Adobe Color Books are unclear, it is very likely that is has limited rights. Due to this decided to remove all `.acb` files from this fork.
