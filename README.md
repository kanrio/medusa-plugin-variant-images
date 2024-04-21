# Medusa-Plugin-Variant-Images

Adding possibility to add images to the product variants.

# Getting started

Installation

```bash
yarn add medusa-plugin-variant-images
```

# Usage

## Configuration

```
### Add to medusa-config.js

add to your plugins list

```

///...other plugins
{
resolve: 'medusa-plugin-variant-images',
options: {
enableUI: true,
},
},

```

### Update database schema

Run the following command from the root of the project to udpate database with a new table required for storing product variant

```

npx medusa migrations run

```

### How to get images from variant

After enabling this plugin, each variant will contains `images` and `thumbnail` fields.
```
