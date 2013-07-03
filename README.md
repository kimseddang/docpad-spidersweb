# [MARKQUERY SKELETON](http://markquery.github.io) 

##  Spider's Web v1.0.0 for docpad

Customize your contents. Markquery is markup library for web contents.

* Homepage [http://markquery.github.io](http://markquery.github.io)
* Korean page: [http://markquery.kr](http://markquery.kr)
* Twitter: [@markquery](http://twitter.com/markquery)

### Getting Started

1. [Install DocPad](https://github.com/bevry/docpad)

1. Clone the project and run the server

	``` bash
	git clone https://github.com/markquery/docpad-spidersweb.git
	cd docpad-spidersweb
	npm install
	docpad run
	```

1. [Open http://localhost:9778/](http://localhost:9778/)

1. Start hacking away by modifying the `src` directory

### I'm getting EMFILE errors

[See here for the reason why and the solution](http://docpad.org/docs/troubleshoot#i-m-getting-emfile-too-many-open-files)

### File structure

``` 
docpad-spidersweb/
├── docpad.coffee
├── history.md
├── LICENSE.md
├── package.json
├── README.md
├── node_modules/ (plugins) 
├── out/ (output directory) 
└── src/ 
    ├── *documents/
        ├── 404.html.eco
        ├── 500.html. eco
        ├── atom.xml.coffee
        └── index.html
    ├── *files/
        ├── images/
        ├── scripts/
        └── style/
            ├── crossdomain.xml
            ├── humans.txt
            └── robots.txt
    ├── layouts/
        ├── default.html.eco
        ├── page.html.eco
        └── post.html.eco
    └── partials/
        └──footer.html

*files/
└── images/
    ├── apple-touch-icon.png
    ├── apple-touch-icon-57x57-precomposed.png
    ├── apple-touch-icon-72x72-precomposed.png
    ├── apple-touch-icon-114x114-precomposed.png
    ├── apple-touch-icon-144x144-precomposed.png
    ├── docs-icon-64.png
    ├── favicon.ico
    ├── fontsize-d.png
    ├── fontsize-minus.png
    ├── fontsize-plus.png
    ├── footer.png
    ├── github-icon-64.png
    ├── glyphicons-halflings.png
    ├── glyphicons-halflings-white.png
    ├── hollys.png
    ├── markquery-icon-64
    ├── markquery-slide.png
    ├── status-icon-64
    └── topscroll-icon
└── scripts/
    ├── bootstrap-v2.js
    ├── fontsize.js
    ├── jquery-version.min.js
    ├── modernizr-version.min.js
    ├── prettify.js
    └── rss.js
└── styles/
    ├── bootstrap-v2.min.css
    ├── main.css (site design css file)
    └── prettify.css

*document/
    ├── scritps/script.js.coffee
    └── styles/markquery.css (user css file, http://markquery.github.io/reference)
```

### Versioning

`<major>.<minor>.<patch>`

### Features

* Supports [bootstrap v2.x](https://github.com/twitter/bootstrap) and bootstpra 3 mobile first.
* The latest [jQuery](http://jquery.com/) via CDN, with a local fallback.
* The latest [Modernizr](http://modernizr.com/) build for feature detection.
* Includes [HTML5 Boilerplate](http://html5boilerplate.com/)
* Includes [Normalize.css](http://necolas.github.com/normalize.css/) 
* Includes [microformat](http://microformats.org/)
* Includes [humans.txt](http://humanstxt.org/)
* [CSSO](https://github.com/css/csso)
* [less](http://lesscss.org/)
* [docpad](https://github.com/bevry/docpad)
* [nodejs](https://github.com/joyent/node)
* [roots](https://github.com/retlehs/roots) theme for wordpress
* more...

### Previews

* `DocPad` **Spider's Web** for docpad - [preview](http://markquery.github.io/docpad-spidersweb)
* `DocPad` **Doo Be Doo** for docpad - [preview](http://markquery.github.io/docpad-doobedoo)
* `Tistory` **Spider's Web** for tistory - [preview](http://markquery-spidersweb.tistory.com)
* `Tistory` **Doo Be Doo** for tistory - [preview](http://markquery-doobedoo.tistory.com)

### All sources

* `WordPress` Spider's Web - centered layout [source](https://github.com/markquery/wp-spidersweb)
* `DocPad` Spider's web - centered layout [source](https://github.com/markquery/docpad-spidersweb)
* `DocPad` Doo Be Doo - fullscreen layout [source](https://github.com/markquery/docpad-doobedoo)
* `Tistory` Spider's web - centered layout [source](https://github.com/markquery/tistory-spidersweb) (Korean only)
* `Tistory` Doo Be Doo - fullscreen layout [source](https://github.com/markquery/docpad-doobedoo) (Korean only)

### Skeleton License

This skeleton is made ["public domain"](http://en.wikipedia.org/wiki/Public_domain) using the [Creative Commons Zero](http://creativecommons.org/publicdomain/zero/1.0/), as such before you publish your website you should place your desired license here and within the `LICENSE.md` file.

If you are wanting to open-source your website, we suggest using the [Creative Commons Attribution License](http://creativecommons.org/licenses/by/3.0/) for content and the [MIT License](http://creativecommons.org/licenses/MIT/) for code. In which case you'd probably want to use the following as your license:

    Unless stated otherwise, all content is licensed under the [Creative Commons Attribution License](http://creativecommons.org/licenses/by/3.0/) and code licensed under the [MIT License](http://creativecommons.org/licenses/MIT/), © [Your Name](http://your.website)

If you are wanting to close-source your website, we'd suggest using the following:

    Copyright [Your Name](http://your.website). All rights reserved.

Other included things such as themes and libraries are likely already licensed by their own invidual licenses, so be sure to respect their licenses too.

### Contributing

submit your contents and needs your help!

- GitHub : [http://github.com/markquery](https://github.com/markquery)
- email : ungki.h@gmail.com
- twitter : [@markquery](https://twitter.com/markquery)

### Copyright and License

* Copyright 2013 markquery project maintained by Ungki, H
* Licensed under the incredibly permissive [MIT License](http://markquery.github.io/license)
* Documentations under [Creative Commons Attribution 3.0](http://creativecommons.org/licenses/by/3.0/)
* Open sources are copyright of their respective owners

Thanks.