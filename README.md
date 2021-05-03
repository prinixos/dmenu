# dmenu

## What is dmenu?

dmenu is a dynamic menu for X, originally designed for dwm. It manages large numbers of user-defined menu items efficiently. It is a very powerful tool that allows you to pipe information into it. This makes dmenu a perfect utility to incorporate into your scripting.

## Why this repository

Well the answer is really simple because I have really customized the hell out of this dmenu I have added many patched to it which let me tell you is not a raelly pleasent experience I have to compile it multiple time. So yes if you don't want to go through that much of troble you can use this.

## How to install dmenu

Run the following commands

```bash
    git clone https://github.com/prinixos/dmenu.git
    cd dmenu
    sudo make install
```

### How to run it

```bash
    dmenu_run
```

## Available flags

- [-l lines]
- [-p prompt]
- [-fn font]
- [-m monitor]
- [-h height]
- [-nb color]
- [-nf color]
- [-sb color]
- [-sf color]
- [-nhb color]
- [-nhf color]
- [-shb color]
- [-shf color]
- [-w windowid]

This launches dmenu_run will automatically run with all my configuration No need to add any flags.

### The flags I recommend

```bash
    dmenu_run -h 30 -nb "#323A46" -sb "#B14438" -p "Run: "
```

