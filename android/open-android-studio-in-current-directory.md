# Open Android Studio in current directory

There is no command in Android Studio similar to Xcode's `xed .`.
Do the following:

```sh
open -a "Android Studio" .
```

I defined an alias in `~/.zshrc`:

```zsh
alias aed='open -a "Android Studio"'
```
