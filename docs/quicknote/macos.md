# macOS Frequent Commands

# 1. Paste & Copy

## 1.1 Clip Board

You can use pbcopy & pbpaste with other commands to process result, such as grep.

## Copy something to clip board:

```shell
ls -ahl | pbcopy
```

## 1.2 Paste something from clip board:
```shell
pbpaste | grep 'Hello'
```

# 2. Execute Applescript

```shell
osascript -e 'quit app "Docker"'

osascript -e 'tell app "Terminal" to display dialog "Times up!"'
```

