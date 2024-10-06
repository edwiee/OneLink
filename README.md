# Onelink

Onelink is an experimental link-in-bio tool, where the data lives in the URL. 

![Screenshot2023-01-30 at 00 40 04@2x](https://user-images.githubusercontent.com/15716057/215350057-5fbf81f5-5f33-4cbe-98ba-0ced8b3c09c8.jpg)

> **Note**
> Since the URL can become very long, it's better to use a link shortener like https://dub.co

Here's a demo page
https://onelinkbyedwin.vercel.app/1?data=eyJuIjoiRWR3aW4gViBTIiwiZCI6IkZ1bGwgU3RhY2sgRGV2ZWxvcGVyIiwiaSI6Imh0dHBzOi8vYXZhdGFycy5naXRodWJ1c2VyY29udGVudC5jb20vdS8xODAxNzA3NDY/dj00IiwiZiI6IiIsInQiOiJodHRwczovL3guY29tL2Vkd2lpeSIsImlnIjoiIiwiZ2giOiJodHRwczovL2dpdGh1Yi5jb20vZWR3aWVlIiwidGciOiIiLCJsIjoiaHR0cHM6Ly93d3cubGlua2VkaW4uY29tL2luL2Vkd2ludnMvIiwiZSI6IiIsInciOiIiLCJ5IjoiIiwibHMiOlt7ImkiOiIiLCJsIjoiT25lTGluayIsInUiOiJodHRwczovL2dpdGh1Yi5jb20vZWR3aWVlL09uZUxpbmsifSx7ImkiOiIiLCJsIjoiUG9ydEZvbGlvIFdlYnNpdGUiLCJ1IjoiaHR0cHM6Ly9lZHdpLnZlcmNlbC5hcHAifV19

The data is converted to a base 64 string which we onelink uses as a query parameter. I have tried to reduce the json keys to be as small as possible

Roadmap.
1. Templates - make different templates, the `/1` after the host is basically a template here.
2. Refactor code - a lot of repeated boilerplate code is added here - refactor it properly.

## Setup locally

Make sure to install the dependencies:

```bash
# yarn
yarn install

# npm
npm install

# pnpm
pnpm install --shamefully-hoist
```

## Development Server

Start the development server on http://localhost:3000

```bash
npm run dev
```

## Production

Build the application for production:

```bash
npm run build
```

Locally preview production build:

```bash
npm run preview
```

Checkout the [deployment documentation](https://v3.nuxtjs.org/guide/deploy/presets) for more information.

----
<p align = "center"><samp>Made with ❤️ - <a href = "https://github.com/edwiee">edwiee</a></samp></p>

