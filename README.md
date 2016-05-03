Code Navigation for Bitbucket
--------------------------------
### Description
This plugin enables you to jump to definitions in your source right in the browser, just hold CTRL! It does this by indexing all of your repositories using **ctags**. Any language supported by ctags is supported.

### Installation

1. Install exuberant-ctags and make sure it's in your path. Most linux distributions come with it installed but if not, you can find the most recent version [here](http://ctags.sourceforge.net/).
2. Download and install Code Navigation for Bitbucket.
3. Go to `Code Navigation for Bitbucket Settings` page for the repository you want to see tag jumps in.
4. Enable `Indexing` by clicking the check box.
5. Click `Save and Reindex` to save the settings and subsequently reindex all repositories.

### Repository Settings

By default, only master and develop are indexed. Individual repo admins may modify these settings as follows:

- Go to the `Code Navigation for Bitbucket Repository Settings` page in your repository settings panel.
- Change the ref regex to match your desired branches.
- Click `Save` or  `Save and Reindex` to save the settings and subsequently reindex all repositories.

For example if we wanted to add the branch `my-branch`, we would modify the regex to look like :

    HEAD|(refs/heads/(master|develop|my-branch))

### Contact Us

If you want to get help, request a feature or report a bug, please email us at  [contact us](mailto:mohammed@mohamicorp.com) or open an issue. **We'd love to hear from you!**

