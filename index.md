# SP Portal API Client Reference

## Introduction
This documentation provides the guide on how to use the API for your sportsbook data needs.
Please contact us if you have any problem.


## Authentication

<!-- HTTP Authentication -->
API uses HTTP Bearer access authentication. You need to send the Authorization HTTP Request header:

```markdown
Authorization: Basic <Base64 value of UTF-8 encoded "username:password">
```
<!-- End of HTTP Authentication -->


To authorize, use this code:

    curl "api_endpoint_here?token=YOUR-TOKEN"

Make sure replace YOUR-TOKEN with your real token.



<!-- You can use the [editor on GitHub](https://github.com/isystem20/sp-portal-api/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/isystem20/sp-portal-api/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
 -->