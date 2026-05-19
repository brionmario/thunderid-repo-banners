# ThunderID Repo Banners

Social preview banners for ThunderID repositories, generated as a single HTML file.

## Usage

Open `thunderid-banners.html` in a browser. Each banner is 1000×420px and designed to be screenshotted for use as a GitHub repository social preview image.

The first banner is the main ThunderID repo banner. The remaining banners cover each SDK and integration package.

## Adding a banner

Add an entry to the `sdks` array in `thunderid-banners.html`:

```js
{
  name: 'package-name',         // used in @thunderid/<name> and npm install command
  badge: 'OFFICIAL SDK',        // badge label
  desc: 'Description text.',
  tags: ['Tag1', 'Tag2'],
  fwStyle: 'background:...',    // inline style for the framework logo box
  icon: `<svg .../>`,           // SVG or <img> for the framework logo
  // installCmd: '...',         // optional: override the default npm install command
  // hideInstall: true,         // optional: hide the install box entirely
}
```

## Banners

| Banner | Type |
|---|---|
| ThunderID | Main repo |
| `@thunderid/browser` | Official SDK |
| `@thunderid/javascript` | Official SDK |
| `@thunderid/react` | Official SDK |
| `@thunderid/nextjs` | Official SDK |
| `@thunderid/node` | Official SDK |
| `@thunderid/express` | Official SDK |
| `@thunderid/vue` | Official SDK |
| `@thunderid/nuxt` | Official SDK |
| `@thunderid/react-router` | Official Integration |
| `@thunderid/tanstack-router` | Official Integration |
| `@thunderid/skills` | Official Skills |
