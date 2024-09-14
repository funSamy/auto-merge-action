<!-- # auto-merge-action
This action helps automatically merging pull request when all the checks have passed -->

# Hello world javascript action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
uses: funSamy/auto-merge-action@v1.1
with:
  who-to-greet: 'Mona the Octocat'
```
