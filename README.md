# Quarto Book Template

## Render Locally

To render the Quarto book locally, follow these steps:

-   Open the folder in RStudio as a project by opening the file ending with `.proj`
-   From the *Build* pane --\> click *Render Book*

## Publish on GitHub Pages

To publish the Quarto book on GitHub Pages there are two approaches: manual (easy) or automatic (more involved).  For further details and comparison between these two approaches and other, see [this GSheet](https://docs.google.com/spreadsheets/d/1efz-KlHgNicp8T8Kzt5ELlX6i0pvwFerosTHLgGwW_Y/preview)

### Manual Approach

In RStudio command window, issue the following command to render the website locally then push it to GitHub Pages to get published.

`quarto publish gh-pages --no-browser`

### Automatic Approach

-   Rename the `.github\workflows\publish.yml.VOID` file to `.github\workflows\publish.yml`
-   Edit `.github\workflows\publish.yml` as needed. The file links to webpages for helpful information
-   Customize `.github\issue_template.md` as needed

