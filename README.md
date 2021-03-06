quantgen.github.io
==================

This is the website of the QuantGen group.

Maintenance Instructions
------------------------

Click on one of the following links to change the page directly on GitHub:

- [Update introduction](https://github.com/QuantGen/quantgen.github.io/edit/master/_includes/introduction.md)
- [Update projects](https://github.com/QuantGen/quantgen.github.io/edit/master/_includes/projects.md)
- [Update software](https://github.com/QuantGen/quantgen.github.io/edit/master/_includes/software.md)
- Update team:
    - [Update existing team member](https://github.com/QuantGen/quantgen.github.io/tree/master/_team): pick member and click on the pencil icon to edit
    - [Add new team member](https://github.com/QuantGen/quantgen.github.io/new/master/_team?filename=firstname-lastname.md): replace `firstname` and `lastname` in the filename, copy and paste the following template at the top of the file, and replace all UPPERCASE placeholders (it is currently not possible to upload an image using GitHub):

        ```
        ---
        layout: team-member
        member_type: current, past, or visitor
        name: FIRSTNAME LASTNAME
        title: TITLE
        picture: IMAGE_PATH
        email: EMAIL
        year: YEAR (if member_type is one of past or visitor)
        ---
        ```

This website is built with [Jekyll](https://jekyllrb.com), which is supported
natively by [GitHub
Pages](https://help.github.com/en/github/working-with-github-pages/setting-up-a-github-pages-site-with-jekyll).
