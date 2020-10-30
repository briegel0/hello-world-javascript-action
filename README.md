# Hello world javascript action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

### 'timeZone'

The desired output Time Zone ( 'UTC' or 'Local'). Default '"UTC"'.

## Outputs

### `time`

The time we greeted you.

## Example usage

uses: briegel/hello-world-javascript-action@v2
with:
  who-to-greet: 'Mona the Octocat'