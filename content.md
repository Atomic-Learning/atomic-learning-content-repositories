Each page of content in the Atomic Learning platform is stored in its own GitHub repository. For example, this page is stored in [this repository](https://github.com/Atomic-Learning/atomic-learning-content-repositories). When creating a Github repository for a new piece of content it should use [this template](https://github.com/Atomic-Learning/content-template) and should be a part of the [Atomic Learning organization](https://github.com/Atomic-Learning). If you do not have the privileges required to do this, contact the Atomic Learning team to request access or to have them create the repository for you.

# Structure of the Repository

The basic structure of the repository is determined by the content template used when creating the repository. Its major components are:

- `content.md`: The main Markdown file containing the content for the page.
- `metadata.json`: The JSON file containing metadata specific to this content page.
- `resources/`: A directory which should be used to contain any additional resources, such as images, used in the content. This initially contains an empty file named `.gitkeep` which exists to ensure the directory is included in version control and can be ignored.
- `license.md`: A file specifying the license of the document. Should not normally be modified.
