### Installation
Clone the parent repo 

`git clone github.com/jeygith/git-subtrees`

Add child repo subtree remote
`git add remote -f git-subtrees-lib git@github.com:jeygith/git-subtrees-lib`

To pull in the latest changes from the remote:
`git subtree pull --prefix git-subtree-lib git-subtree-lib master --squash`

To push in the latest changes from the remote:
`git subtree push --prefix git-subtree-lib git-subtree-lib master --squash`



