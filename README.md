# Website Studentenvertretung PiBS

## Add new post:
`hugo new post/my-great-post.md`
This will create a new file in `content/post/` which you can edit using VI or any other editor.
This is a markdown file, a cheatsheet can be found [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

## Run local:
`hugo server` will show what will get deployed, while with `hugo server -D` you can see your drafts as well.

## Deploy:
Change the parameter `draft` in the files you want to see deployed to `false`.

First, run `hugo`. Then create a commit and push it to Github. The master-branch is setup to be automatically deployed to Github-Pages.

## Prerequisites:
- Git
- [Hugo](https://gohugo.io/getting-started/installing/)
