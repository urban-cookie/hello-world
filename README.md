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

This branch is supposed to contain attachments only---so please do not merge this branch to `master` since it does not contain any project files anymore.

It is save to delete the branch, though, without actually breaking links in issues because the attachments remain under version control and are still accessible from the repository's commit history. However, it is important to reference files using permanent links including the commit number (as decribed above).
