# ottawabaptist-association.github.io

## Reference

The following documents at a high level the steps taken to convert the [Sandbox - Tailwind CSS Modern & Multipurpose Template](https://themeforest.net/item/sandbox-modern-multipurpose-tailwind-css-template/51340309) into a Hugo theme and build this website from scratch.

- Create a hugo site
`hugo new site website --force`

- Create a theme
`cd website & hugo new theme oba`

- Configure site  to use the oba theme
`echo "theme = 'oba'" >> hugo.toml`

- Display the website locally
`hugo server --noHTTPCache -D`

- Create new content
`hugo new content content/home.md`

- Remove Zone Identifier files from content
`find . -name "*:Zone.Identifier" -type f -delete`

- Gettings started with Hugo
https://gohugo.io/getting-started/quick-start/

- Github Pages
https://pages.github.com/

- Creating a Hugo Theme from Scratch
https://retrolog.io/blog/creating-a-hugo-theme-from-scratch/