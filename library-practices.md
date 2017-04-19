# Library Practices

Best practices/norms for writing a small js library/widget/framework, so far as I can figure it out.


* Separate JS and CSS: Several have separate CSS and JS files.
* Comments: Some are really well commented, some are very sparse or not at all.
* Minification: Most offer it.
* How to put my thing in your project: Offer a download of files to put in your project however you like. Give a CDN link. Give the name of the npm package to install.
* Dependencies: Some tout "zero dependencies" as a feature and light-weight-ness is good in general. Some do instruct users to include script tag references to other things, sometimes specifying that they are optional (like if the additional dependency will enable features of the library that won't work otherwise, but it still has some dependency-free features).
* Options: There are libraries that have option files of some manner. (Like in a package.json? I don't know how that works. That is more than I need for what I plan to do.)
* Documentation: Some are very brief and sort of leave you to figure it out yourself. (But maybe there are some standards and expectations that I am missing from lack of experience?) Others are very very explicit. Bootstrap's is explicit. As another smallish library documentation example, [Slick's](http://kenwheeler.github.io/slick/) documentation is very nice and explicit.
