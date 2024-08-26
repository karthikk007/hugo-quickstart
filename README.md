# install HUGO

brew install hugo

# checking HUGO version

hugo version

# quick start HUGO

[Refer the doc](https://gohugo.io/getting-started/quick-start/)

```shell
hugo new site quickstart
cd quickstart
git init
git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke
echo "theme = 'ananke'" >> hugo.toml
hugo server
```


# add your first content

```sh
hugo new content content/posts/my-first-post.md
```

# to include draft content

Run either of the following

```sh
hugo server --buildDrafts
hugo server -D
```

# copy content from the themes folder

Changes will be reflected


# External links

> [HUGO Docs](https://gohugo.io/documentation/)

> [Markdown Guide](https://www.markdownguide.org/cheat-sheet/)
