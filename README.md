# problem statement

posts a message to a public, private, or direct message/IM slack channel

# example usage

> note: in examples, VERSION represents a version of the slack.chat.post-message pkg

## install

```shell
opctl pkg install github.com/opspec-pkgs/slack.chat.post-message#VERSION
```

## run

```shell
opctl run github.com/opspec-pkgs/slack.chat.post-message#VERSION
```

## compose

```yaml
run:
  op:
    pkg: { ref: github.com/opspec-pkgs/slack.chat.post-message#VERSION }
    inputs: { msg, channelName, apiToken }
```
