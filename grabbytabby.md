# super-octo-journey
publish
-c, --clone
Clone the new repository to the current directory
-d, --description <string>
Description of the repository
--disable-issues
Disable issues in the new repository
--disable-wiki
Disable wiki in the new repository
-g, --gitignore <string>
Specify a gitignore template for the repository
-h, --homepage <URL>
Repository home page URL
--internal
Make the new repository internal
-l, --license <string>
Specify an Open Source License for the repository
--private
Make the new repository private
--public
Make the new repository public
--push
Push local commits to the new repository
-r, --remote <string>
Specify remote name for the new repository
-s, --source <string>
Specify path to local repository to use as source
-t, --team <name>
The name of the organization team to be granted access
-p, --template <repository>
Make the new repository based on a template repository
Examples
# create a repository interactively
gh repo create

# create a new remote repository and clone it locally
gh repo create my-project --public --clone

# create a remote repository from the current directory
gh repo create my-project --private --source=. --remote=upstream
