_Following the guide [here](https://docs.github.com/en/actions/creating-actions/creating-a-javascript-action)_

# Hello world javascript action

This action prints "Hello World" or "Hello" + the name of the person to greet to the log.

## Inputs

## `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

## `time`

The time we greeted you.

## Example usage

```yml
uses: actions/hello-world-javascript-action@v1.1
with:
  who-to-greet: "Mona the Octocat"
```

# Links

- [Docs](https://docs.github.com/en/actions/creating-actions)
- [Github Actions Toolkit](https://github.com/actions/toolkit)

# Notes

- You actually have to commit the `node_modules` folder. More info [here](https://docs.github.com/en/actions/creating-actions/creating-a-javascript-action#commit-tag-and-push-your-action-to-github).
