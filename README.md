# pisound-docs
If your are looking for pisound documentation, head straight to the [Wiki page!](https://github.com/BlokasLabs/pisound-docs/wiki)

# Contribution guide
Everyone can contribute through GitHub Wiki UI or cloning repo `git clone http://github.com/BlokasLabs/pisound-docs.wiki.git`.

## Uploading images

`git clone http://github.com/BlokasLabs/pisound-docs.wiki.git`
`cd ./pisound-docs.wiki/images`

## Displaying images
`![name](https://raw.githubusercontent.com/wiki/BlokasLabs/pisound-docs/images/{name}.png)`

## Linking to a section

To create an anchor to a heading in github flavored markdown. Add - characters between each word in the heading and wrap the value in parens (#some-markdown-heading) so your link should look like so:

`[Linking to a section](#section-name)`
`[Linking to a section in another page](page-name#section-name)`

# Docs page generation

```
pip install mkdocs
```

1. Rename `.\pisound-docs\docs\Home.md` to `.\pisound-docs\docs\index.md`
1. When in `.\pisound-docs\` run `mkdocs build`
1. For preview run `mkdocs serve`
1. Rename `.\pisound-docs\docs\index.md` to `.\pisound-docs\docs\Home.md`
1. Upload `.\pisound-docs\site\` folder to the server
