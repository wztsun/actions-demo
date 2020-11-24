# action-demo

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**必填** 要问候的人员的姓名。 默认值为 `"World"`。

## Outputs

### `time`

我们问候您的时间。

## Example usage

uses: wztsun/action-demo@v1
with:
  who-to-greet: 'Mona the Octocat'