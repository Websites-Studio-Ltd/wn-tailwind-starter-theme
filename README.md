# Tailwind Starter Theme for WinterCMS

Preconfigured with TailwindCSS v3.0.16 + Plugins (Typography, Forms) + AlpineJS

### Tailwind CLI

This setup is based on Tailwind CLI with a Linux x64 server. This should work on most LAMP Stack environments.

**Not using Linux server?**

The Tailwind CLI is also available for Windows and Mac environments. Please see official documentation from Tailwind:

[Standalone CLI: Use Tailwind CSS without Node.js – Tailwind CSS](https://tailwindcss.com/blog/standalone-cli)

## How to use

Open a terminal in the root directory of the theme

**Important! Make sure the tailwindcss file has permissions to execute**

`chmod +x tailwindcss`

(Alternatively, open in a file browser and set permissions to 0755)

## Dev/Staging Environment

To watch for changes on the fly during development run the following command.

```bash
./tailwindcss -i ./assets/style/src/theme.css -o ./assets/style/dist/theme.css --watch
```

## Production Environment

To generate a minified css file for production

```bash
./tailwindcss build -i ./assets/style/src/theme.css -o ./assets/style/dist/theme.css --minify
```
# wn-tailwind-starter-theme
