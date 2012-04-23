z4y4ts.github.com
=================

So this is my résumé. Public version is [here][resume].

I maintain it in [markdown][mdown] -- nice and easy to read, edit & export language.

Export to HTML is provided by [github:pages][pages] via [Jekyll][jekyll].

Export to PDF I do by myself with help of [Gimli][gimli]

Now résumé update as simple as:

1. Edit ```index.md```.
2. Run simple command to export it to pdf. ```gimli -removefrontmatter -file index.md -outputfilename 'Alexander Zayats - resume'```. Well, actually there's a little trick I have to do before export to pdf -- add two headers (name & position) into ```index.md```. I'm going automate this in next iteration.
3. Push changes to github.
4. ...
5. PROFIT!

[resume]: http://z4y4ts.github.com/
[mdown]: http://en.wikipedia.org/wiki/Markdown
[pages]: http://pages.github.com/
[jekyll]: https://github.com/mojombo/jekyll
[gimli]: https://github.com/walle/gimli
