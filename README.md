# WordPress Code Examples Starter

This template repository is pre-configured to provide all of the tools to format code to match the WordPress coding standards.


## What does it provide?

1. Linting and formatting tools for PHP, JavaScript, CSS and package.json files.
2. A GitHub action to that runs linting on PRs and merged to trunk.
3. Build process provided by `@wordpress/scripts`

## How do I use it?
1. Start by clicking the `Use this template` to use this as a starting point for your project.
2. Run `npm run setup` to install everything.
3. If using VSCode add the following to your settings.json
```json
"editor.codeActionsOnSave": {
	"source.fixAll.eslint": true
},
```

