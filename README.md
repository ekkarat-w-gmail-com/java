# Hello world JavaScript action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log. To learn how this action was built, see "[Creating a JavaScript action](https://help.github.com/en/articles/creating-a-javascript-action)" in the GitHub Help documentation.

## Ekkarat

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## ekkarat.w-gmail.com.git

### `time`

The time we greeted you.

## Example usage

```yaml
uses: actions/hello-world-javascript-action@master
with:
  who-to-greet: 'Mona the Octocat'
```
