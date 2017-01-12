# jekyll-relative-links
liquid macros to ease using relative paths with Jekyll. Your site working anywhere (including 
a disk folder).

## Usage

Save the file `relative-links` in your project's `_include` folder.

Add this where you need it, usually in the `_include/header.html` file.

    {% include relative-links %}

That's it!, now you can:

    [home]({{ rbaseurl }}index.html)

If you need to use it in your page/post you'll have to include it again, as liquid variables 
are not passed from one include to another
