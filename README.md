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

Similar projects
----------------

Just found [benbalter](https://github.com/benbalter)/[jekyll-relative-links](https://github.com/benbalter/jekyll-relative-links)

My project has the same intention but no relation to it. I'll look at it to get ideas,
but my intention was to make a really easy to use "plugin", even if that means less 
features.
