---
layout: post
title: "Release 3.0 is out"
date: 2013-05-05 17:14
comments: true
categories: [ releases ]
---
Release 3.0 is out. This is a major release, which contains many key updates and renovations. The release contains [several bug fixes and loads of enhancements](https://github.com/crawljax/crawljax/issues?milestone=3&state=closed). The code base has been split up into modules, the API has changed a little, and the crawl overview plugin has been completely renovated.

### New overview plug-in

Most notable in the new release is the new overview plugin. The plugin shows an interactive state graph of the crawl and some statistics. Make sure you check out [a demo](http://crawls.crawljax.com) or try one of our [examples](https://github.com/crawljax/crawljax/tree/master/examples) yourself.

{% img /images/new-overview-plugin.png  "The new overview plugin" %}

### New command line interface

This release brings more support for command line configuration. Once you download the zip, running Crawljax can simply be done using the command:

	java -jar crawljax-cli-version.jar http://your.site.com outputfolder
	
Crawljax will Crawl that site with the new Crawl overview plugin enabled. You can run `java -jar crawljax-cli-version.jar` to see a list of possible configurations for the crawl.

The zip is downloadable from [the central Maven repository](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22com.crawljax%22%20AND%20a%3A%22crawljax-cli%22).

### Other important updates

* Crawljax is now configured using a configuration builder. You start your configuration using `CrawljaxConfiguration.builderFor("http://your.website.com");`.
* The project has been split up in three versions: *core*, *cli* and *examples*. The *cli* modules contains the command line interface. The *core* module can be included in any project as a jar to run Crawljax programmatically. The *examples* module is the easiest way to try out several configurations of Crawljax in your favorite IDE. Check out our updated documentation for more details. 
* You can configure the crawler to crawl all found `href` attributes. Even if the elements are not visible because they only show up when the crawler hovers on another element.
* You can now configure the crawler so that it does not click any children of a certain element using a short syntax like `dontClickChildrenOf("LI").withId("dontClickMe");`
* Major performance and stability improvements.

You can [view all closed issues](https://github.com/crawljax/crawljax/issues?milestone=3&page=1&state=closed) or [the full diff](https://github.com/crawljax/crawljax/compare/crawljax-2.2...crawljax-3.0) on Github.