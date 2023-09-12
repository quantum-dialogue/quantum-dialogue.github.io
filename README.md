# Atul Mantri's Personal Webpage

Welcome to my personal webpage repository! This webpage serves as a platform for sharing my academic and research work, as well as insights into the fascinating world of quantum computing and cryptography.

## Table of Contents
- [About](#about)
- [Teaching](#teaching)
- [Publications](#publications)
- [Awards and Honors](#awards-and-honors)
- [Contact](#contact)

## About
Explore my background, academic journey, and research interests. Learn more about the mentors and advisors who have guided me throughout my career.

## Teaching
Discover the courses I've taught, including course descriptions, syllabi, and resources. Explore topics in quantum computing and cryptography and gain valuable insights into cutting-edge research in these fields.

## Publications
Access my research papers, publications, and contributions to the field of quantum computing and cryptography. Stay updated with the latest developments in quantum technology.

## Awards and Honors
Learn about the recognition and awards I've received for my contributions to the field. Celebrate the achievements and milestones in my academic journey.

## Contact
Connect with me via email or on academic and professional platforms such as Google Scholar and GitHub. I'm always open to collaborations and discussions in the field of quantum science.

## License
This project is licensed under the [MIT License](LICENSE) - feel free to use, modify, and share this content as long as you provide proper attribution.

Thank you for visiting my webpage! Feel free to explore the various sections and get in touch if you have any questions or opportunities for collaboration.









------------- 


# al-folio
A simple and clean [Jekyll](https://jekyllrb.com/) theme for academics.

**al-folio** is based on [\*folio theme](https://github.com/bogoli/-folio).
The original theme was published by [Lia Bogoev](http://liabogoev.com) and copyrighted under the MIT license.

## Getting started

For more about how to use Jekyll, check out [this tutorial](https://www.taniarascia.com/make-a-static-website-with-jekyll/).
Why Jekyll? Read this [blog post](https://karpathy.github.io/2014/07/01/switching-to-jekyll/)!

### Installation

Assuming you have [Ruby](https://www.ruby-lang.org/en/downloads/) and [Bundler](https://bundler.io/) installed on your system (*hint: for ease of managing ruby gems, consider using [rbenv](https://github.com/rbenv/rbenv)*), first fork the theme from `github.com:alshedivat/al-folio` to `github.com:<your-username>/<your-repo-name>` and do the following:

```bash
$ git clone git@github.com:<your-username>/<your-repo-name>.git
$ cd <your-repo-name>
$ bundle install
$ bundle exec jekyll serve
```

Now, feel free to customize the theme however you like (don't forget to change the name!).
After you are done, you can deploy it to [GitHub Pages](https://pages.github.com/) by running the deploy script:

```bash
$ ./bin/deploy
```

## Features

Emphasis on whitespace, transparency, and academic usage: [theme demo](https://alshedivat.github.io/al-folio/).

To learn more on how to use Jekyll, you can refer to, e.g., [this tutorial](https://www.taniarascia.com/make-a-static-website-with-jekyll/).
To know *why Jekyll*, you can read this [blog post](https://karpathy.github.io/2014/07/01/switching-to-jekyll/).

### Ergonomic Publications

Your publications page is generated automatically from your BibTex bibliography.
Simply edit `_bibliography/papers.bib`.
You can also add new `*.bib` files and customize the look of your publications however you like by editing `_pages/publications.md`.

Keep meta-information about your co-authors in `_data/coauthors.yml` and Jekyll will insert links to their webpages automatically.

### Collections
This Jekyll theme implements collections to let you break up your work into categories.
The example is divided into news, poetry, and projects, but easily revamp this into apps, short stories, courses, or whatever your creative work is.
> To do this, edit the collections in the config file, create a corresponding folder, and update the portfolio and poetry source files.

Three different layouts are included—the poetry layout, for a simple list of entries, the blog layout (`blog/index.html`), for more detailed descriptive list of entries, and the portfolio layout.
The projects layout overlays a descriptive hoverover on a background image.
If no image is provided, the square is auto-filled with the chosen theme color.
Thumbnail sizing is not necessary, as the grid crops images perfectly.

### Theming
Six beautiful theme colors have been selected to choose from.
The default is purple, but quickly change it by editing the `_sass/base.scss` file in line 40.
The color variable are listed there, as well.

### Photos
Photo formatting is made simple using rows of a 3-column system.
Make photos 1/3, 2/3, or full width.
Easily create beautiful grids within your blog posts and projects pages.

### Code Highlighting
This theme implements Jekyll's built in code syntax highlighting with Pygments.
Just use a liquid tag to delineate your code:
{% highlight python %} code code code {% endhighlight %}

## Contributing

Feel free to contribute new features and theme improvements by sending a pull request.
Style improvements and bug fixes are especially welcome.

## License

MIT
