---
title: Bookshelf Shortcode Demo
summary: 
date: 2024-03-11

authors:
  - admin

tags:
  - Hugo Blox
  - Markdown
  - shortcode

image:
  caption: 'Hugo Shortcode Front Bookshelf'

bookshelf_item:
  - title: Dune
    cover_img: https://m.media-amazon.com/images/I/81TmnPZWb0L._SL200_.jpg
    cover_link: "https://www.amazon.com/Dune-Chronicles-Book-1/dp/0441013597"
    author: Frank Herbert
  - title: 1984
    cover_img: https://m.media-amazon.com/images/I/71rpa1-kyvL._SL200_.jpg
    cover_link: "https://www.amazon.com/1984-Signet-Classics-George-Orwell/dp/0451524934"
    author: George Orwell
  - title: To Kill a Mockingbird
    cover_img: https://m.media-amazon.com/images/I/81aY1lxk+9L._SL200_.jpg
    cover_link: "https://www.amazon.com/To-Kill-Mockingbird-Harper-Lee/dp/0060935464"
    author: Harper Lee
  - title: The Lord of the Rings
    cover_img: https://m.media-amazon.com/images/I/7125+5E40JL._SL200_.jpg
    cover_link: "https://www.amazon.com/Lord-Rings-J-R-R-Tolkien/dp/0544003411"
    author: J.R.R. Tolkien
  - title: Harry Potter and the Sorcerer's Stone
    cover_img: https://m.media-amazon.com/images/I/91wKDODkgWL._SL200_.jpg
    cover_link: "https://www.amazon.com/Harry-Potter-Sorcerers-Stone-Rowling/dp/059035342X"
    author: J.K. Rowling
  - title: Catch-22
    cover_img: https://m.media-amazon.com/images/I/61gaZF+DIHL._SL200_.jpg
    cover_link: "https://www.amazon.com/Catch-22-50th-Anniversary-Joseph-Heller/dp/1451621175"
    author: Joseph Heller
  - title: The Great Gatsby
    cover_img: https://m.media-amazon.com/images/I/81QuEGw8VPL._SL200_.jpg
    cover_link: "https://www.amazon.com/Great-Gatsby-F-Scott-Fitzgerald/dp/0743273567"
    author: F. Scott Fitzgerald
  - title: Brave New World
    cover_img: https://m.media-amazon.com/images/I/81zE42gT3xL._SL200_.jpg
    cover_link: "https://www.amazon.com/Brave-New-World-Aldous-Huxley/dp/0060850523"
    author: Aldous Huxley
--- 
 
This is a bookshelf shortcode available for use with HugoBlox. 

The shortcode's repository can be found at this [repository](https://github.com/kjrstory/hugo-shortcode-bookshelf). 
 
This shortcode is inspired by the petargyurov's [project](https://github.com/petargyurov/virtual-bookshelf).

0. If the layout/shortcodes folder does not exist in your project, you should create it first 

1. To use it, you should copy the layout/shortcodes/bookshelf.html file.

2. For Tailwind templates, copy the custom.css file into the assets/css folder, and for Bootstrap templates, copy the custom.scss file into the assets/scss folder.

3. Copy the bookshelf.js file into the assets/js folder.

4. Then, insert the following into the front matter of your blog post:

```markdown
bookshelf_item:
  - title: Dune
    cover_img: https://m.media-amazon.com/images/I/81TmnPZWb0L._SL200_.jpg
    cover_link: "https://www.amazon.com/Dune-Chronicles-Book-1/dp/0441013597"
    author: Frank Herbert
  - title: 1984
    cover_img: https://m.media-amazon.com/images/I/91Mv6oCERWL._SL200_.jpg
    cover_link: "https://www.amazon.com/1984-Signet-Classics-George-Orwell/dp/0451524934"
    author: George Orwell   
```
{{< front-bookshelf  >}}

This will enable you to display a virtual bookshelf on your Hugo-Blox site, leveraging the visually appealing bookshelf design.
