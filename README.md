# problem statement

posts a message to a public, private, or direct message/IM slack channel

# example usage

> note: in examples, VERSION represents a version of the slack.msg-chan pkg

## install

```shell
opctl pkg install github.com/opspec-pkgs/slack.msg-chan#VERSION
```

## run

```shell
opctl run github.com/opspec-pkgs/slack.msg-chan#VERSION
```

## compose

```yaml
run:
  op:
    pkg: { ref: github.com/opspec-pkgs/slack.msg-chan#VERSION }
    inputs: { msg, channelName, apiToken }
```
