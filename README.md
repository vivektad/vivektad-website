# Hosting a Notion Page on Github Pages

1. Create a Notion page to be your website. This can have subpages, databases, anything supported by [Loconotion](https://github.com/leoncvlt/loconotion).
1. Share your Notion page publicly, and update `site.toml` in your repo to point to it.
1. Run the `Publish Notion website to GitHub Pages` action under the Actions tab of your repo.
1. Update your repo's `Pages` settings to use the `gh-pages` branch, hit save, and voila!

To resync the website, simply run the GitHub action again. `site.toml` can be updated to use any of the settings specified in the [Loconotion README](https://github.com/leoncvlt/loconotion/blob/master/README.md).

## Acknowledgements

Thanks to:
- @leoncvt for creating the Loconotion script
- @X1011 for the original script used to deploy the website to GitHub pages
