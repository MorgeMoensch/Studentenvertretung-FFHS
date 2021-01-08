# Website Studentenvertretung PiBS
This website gives PiBS-Students at FFHS useful information around their study.

If you think something lacks on the website, please open an issue, contribute it yourself or contact your class representative.

Currently the website is hosted on Github Pages and can be found [here](https://morgemoensch.github.io/Studentenvertretung-FFHS/).

## How To
### Add new post:
`hugo new post/my-great-post.md`
This will create a new file in `content/post/` which you can edit using VI or any other editor.
This is a markdown file, a cheatsheet can be found [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

### Run local:
`hugo server` will show what will get deployed, while with `hugo server -D` you can see your drafts as well.

### Deploy:
Change the parameter `draft` in the files you want to see deployed to `false`.

First, run `hugo`. Then create a commit and push it to Github. The master-branch is setup to be automatically deployed to Github-Pages.

### Prerequisites:
- Git
- [Hugo](https://gohugo.io/getting-started/installing/)

## To Do
- [x] About Page
- [x] Localization for Switzerland
- [ ] Custom Domain (WIP)
- [ ] Important Dates
- [ ] Link Repository on Website
- [ ] Testing on iOS/MacOS
- [ ] Add FAQ items
  - [x] Prüfungseinsicht
  - [x] Dozent antwortet nicht
  - [ ] Newrow Alternativen
  - [ ] Ausbildungsbestätigungen
  - [ ] Modulplan stimmt nicht mit Moodle überein
  - [ ] Kommunikationsgefässe (Roundtable, Bila)
  - [ ] Transferarbeiten
