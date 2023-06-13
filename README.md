# dpp_docs
A new template for the Design for Physical Prototyping project documentation. 
It uses the static site generator [Hugo](https://gohugo.io/) to generate a web pages from Markdown files with the [Hugo Book Theme](https://github.com/alex-shpak/hugo-book) and the theme component [hugo-video](https://github.com/martignoni/hugo-video).

To get started with your documentation, generate your own repository by clicking "[use this template]" or clone this repository.
Using GitHub pages you can access your documentation via [https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPO-NAME](https://pretoms.github.io/dpp_docs/).

# Quickstart

For working on your documentation it is recommended to host your local Hugo instance and to use a text editor of your choice to edit the Markdown files. 

First install Hugo.
## Windows
Use PowerShell to install the extended version of Hugo with winget. Add %localappdata%\microsoft\winget\packages to your [path variable](https://windowsloop.com/how-to-add-to-windows-path/).
```bash
winget install Hugo.Hugo.Extended
```

## Linux
```bash
sudo apt install hugo
```

## Mac OS
Install Hugo using the free and open source package manager [Homebrew](https://brew.sh/). This will install the extended edition of Hugo.

```bash
brew install hugo
```

# Clone

Make sure you have [Git](https://git-scm.com/) installed on your system.
[use this template] and share it with your team.
Change active directory to the cloned repository and run the Hugo server.

```bash
cd C:\your\local\repository\path
hugo server --minify
```

Then visit http://localhost:1313 to view the documentation.

[use this template]: https://github.com/pretoms/dpp_docs/generate

