# hello-world `attachments`

This is a dummy branch to be able to commit files and reference them in issues.
This is a workaround for GitHub's limitation to add attachments to issues.

## Usage

- Checkout / switch to this branch
- Add / commit / push a file for attachment
- Navigate to the file on GitHub
- Press `y` to generate a permalink to the file
- Copy / paste the link from the browser's address bar to your issue description (plain or in markdown with `[title](url)`)
 
## Notes

This branch is supposed to contain attachments only—so please do not merge this branch to `master` since it does not contain any project files anymore.

It is save to delete the branch, though, without actually breaking links in issues because the attachments remain under version control and are still accessible from the repository's commit history. However, it is important to reference files using permanent links including the commit number (as decribed above).

## Motivation

As already mentioned, GitHub does not offer a way to attach files to issues (only images).
There are various workarounds to this limitation:
- **Separate Directory:** Add a separate `attachments` directory to the project and commit the files there. This clutters the history with commits that are not relevant for the project / code itself.
- **Separate Repository:** Create a separate (private) repository just for attachments. The drawback is that all users of this repository have to be added to the new `attachments` repository (if it is private) in order to grant access to the attachments (maintanance overhead).
- **Separate Dummy Branch:** This solution (as described above). Seems to be the best workaround, IMO. The only drawback I can see is that it might be confusing to have a dummy branch wihtout real project files and that the attachments incl. history might need to be downloaded when this project is cloned.
- **Gist:** Post file (snippets) on GitHub Gist and reference them from issues. Not preferred because I don't want to clutter my Gists with log files, etc. In addition, references are broken if I choose to delete the Gists (even when referenced with permalink).
- **Cloud:** Store attachments in cloud and reference via link. Nope, not really...
