# canirly

Command line tool for caniuse database.

## Features

* Uses [caniuse-db](https://github.com/Fyrd/caniuse) internally, so results are displayed instantly.
* Supports tab autocompletion in **zsh**, **bash** and **fish**.

## Installation

```
# ...
```

## Usage

```bash
$ canirly webrtc
```

Now you have an autocompletion system.

## Possible issues

### Missing `bash-completion` package
```
bash: _get_comp_words_by_ref: command not found
bash: __ltrim_colon_completions: command not found
bash: _get_comp_words_by_ref: command not found
bash: __ltrim_colon_completions: command not found
```

Solution: install `bash-completion` package
