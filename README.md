# Lambda (Mod) ZSH Theme

A ZSH theme optimized for people who use:
- Git
- Unicode-compatible fonts and terminals

---

![Screenshot](https://raw.githubusercontent.com/halfo/lambda-mod-zsh-theme/master/screenshot.png)

## Configuring the amount of dir levels

By default only the last three directories are shown in the prompt. The amount of
levels can be configured by setting `LAMBDA_MOD_N_DIR_LEVELS` before loading the prompt:

``` zsh
# ~/.zshrc
export LAMBDA_MOD_N_DIR_LEVELS=10

# load `lambda-mod` and `oh-my-zsh`
```
