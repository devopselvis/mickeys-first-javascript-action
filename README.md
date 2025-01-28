# mickeys-first-javascript-action
I am a javascript action build by following the documentation from github

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
uses: devopselvis/mickeys-first-javascript-action@v1
with:
  who-to-greet: 'The King of Rock and Roll'
```
