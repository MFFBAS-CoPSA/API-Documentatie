## Adding to the document

First, create a branch off of the develop branch called 'feature/*my_change*'. Update the documentation and push. Then, create a pull request and inform the team.

Publications are configured in the `.github/jekyll-gh-pages.yml`. Currently it runs using the 'develop' branch. The standard process for pages currenty generates from the main branch. Do not edit the main or publication branch directly.

For updating the document, see for an extensive description the [Getting start pages](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github) or dive directly into the [flavoured specification](https://github.github.com/gfm/).

Each document has its own source, configured in the workflow file (see above). Adding a document means changing this file. All source files are concatenated using all files in sort order.

See here for configuration on Jekyll: https://jekyllrb.com/docs/configuration/default/. Update the _config.yml file accordingly. A valuable source is also: https://docs.github.com/en/pages/quickstart (see section on Jekyll).


