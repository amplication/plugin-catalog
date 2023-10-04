<h3 align="center">
    <a href="https://amplication.com/#gh-light-mode-only">
    <img src="https://github.com/amplication/amplication/blob/master/.github/assets/amplication-logo-dark-mode.svg">
    </a>
    <a href="https://amplication.com/#gh-dark-mode-only">
    <img src="https://github.com/amplication/amplication/blob/master/.github/assets/amplication-logo-dark-mode.svg">
    </a>
</h3>

---

After publishing the plugin to NPM from the GitHub the plugin will not be visible in the Amplication plugin settings/list immediately. This works by adding your plugin to the [amplication/plugin-catalog](https://github.com/amplication/plugin-catalog), where the `plugin-catalog` is indexed by amplication. Adding the new plugin here will add it to the list of plugins in amplication. Any subsequent version that is released to NPM, will be updated automatically - this can take about 5-10 minutes to propagate.

## Adding a new plugin to the catalog

When adding a new plugin to the catalog, two files must be created in this repository. First a icon to represent the plugin should be created under the `assets/icons/` folder. Second the metadata for the plugin should be provided under the `plugins/` directory.

## Documentation

- [How to create a plugin](https://docs.amplication.com/plugins/how-to-create-plugin/)
- [How to test a plugin](https://docs.amplication.com/plugins/how-to-test-plugin/)
- [How to publish a plugin](https://docs.amplication.com/plugins/publish-plugin/)