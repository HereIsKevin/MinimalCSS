# minimal.css

minimal.css is an easy to use, invasive, and simple minimal css framework. Unlike other minimal frameworks, minimal.css may seem quite large, but is extremely feature rich, with new features being implemented daily. If a large framework like Bootstrap is too heavy for your needs, while a small framework like Skeleton CSS is too basic, minimal.css may be perfect for you.

## A Warning to the User

minimal.css is a new creation, and currently under heavy development. Be warned that it is far from complete, and is subject to change often. It is licensed under AGPLv3, so USE AT YOUR OWN RISK. Bugs may occur throughout, and please report them on the [issue tracker](https://github.com/HereIsKevin/minimal.css/issues), so that they may be fixed.

## Using

To use minimal.css, copy `minimal.css` and `minimal.js` to wherever needed, and add this to your file's `<head>` include them in your files, replacing the `/path/to/`s with the actual path of the files:

```html
<link rel="stylesheet" type="text/css" href="/path/to/minimal.css">
<script type="text/javascript" src="/path/to/minimal.js"></script>
```

In production, it is preferable to use a minified version, so replace copy the `minimal.min.css` and `minimal.min.js` instead to wherever needed, and add this instead to your file's `<head>` to include them in your files, again replacing the `/path/to/`s with the actual path of the files:

```html
<link rel="stylesheet" type="text/css" href="/path/to/minimal.min.css">
<script type="text/javascript" src="/path/to/minimal.min.js"></script>
```

## Building

Building minimal.css is relatively easy, with prewritten build scripts, though every source release comes with everything prebuilt. Before doing anything, make sure [Node.js](https://nodejs.org/) is installed and on the path. On Windows, open PowerShell and issue the following commands:

```powershell
npm install # Installs the dependencies
npm run build-win # Runs the Windows build script
```

On Linux or macOS, open a shell and run:

```bash
npm install # Installs the dependencies
npm run build-nix # Runs the *nix build script
```

## Issues

Bugs are common, so please report them on the [issue tracker](https://github.com/HereIsKevin/minimal.css/issues).

## Licensing

I believe that a work of open source should stay open, so I decided to license this project under AGPLv3, which you can see the restrictions [here](https://choosealicense.com/licenses/agpl-3.0/).

---

This project Copyright &copy; 2019 Kevin Feng, licensed under AGPLv3, as free and open source software. All rights reserved. Note that all rights to relicense, the source code, and all intelectual property belongs to Kevin Feng.
