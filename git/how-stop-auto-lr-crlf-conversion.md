# How to stop auto LR to CRLF conversions in windows

## While cloning

```sh
git -c core.autocrlf=false <url to clone>
```

## After cloning

```sh
git config --global core.autocrlf false
```
