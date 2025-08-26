# Mintlify Starter Kit

Click on `Use this template` to copy the Mintlify starter kit. The starter kit contains examples including

- Guide pages
- Navigation
- Customizations
- API Reference pages
- Use of popular components

### Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```
npm i -g mint
```

Run the following command at the root of your documentation (where docs.json is)

```
mint dev
```

### Upgrading from mint.json

If you have an existing project with `mint.json`, follow these steps to upgrade:

1. Update or install the latest CLI:
```
npm i -g mint
```

2. Automatically convert your configuration:
```
mint upgrade
```

3. Verify the generated `docs.json` file and delete the old `mint.json`

### Publishing Changes

Install our Github App to auto propagate changes from your repo to your deployment. Changes will be deployed to production automatically after pushing to the default branch. Find the link to install on your dashboard. 

#### Troubleshooting

- Mintlify dev isn't running - Run `mint update` to update the CLI or reinstall dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `docs.json` (or `mint.json` for older versions)
- For one-time preview without global installation: `npx mint dev`
