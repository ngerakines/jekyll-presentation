# Jekyll Presentation

This is an outline for a presentation I'm giving to the office on Jekyll and how I'm using it for my personal blog. This might become a [showoff](https://github.com/schacon/showoff) kit, but no promises.

## Topics To Cover

### Jekyll

* What is Jekyll?
  * Config and directory structure
    * Git friendly, easy to take with you 
  * Templates
  * Blog posts
  * Misc files and pages
* How is Jekyll used?
  * Install
  * Build (`jekyll --no-auto`)
  * Preview (`jekyll --server --auto`)
* Why not XXX?
  * There are alot of features I don't use.
  * Static is simple (hat-tip MT)

### S3 and Cloudfront

* What is S3?
* What is Cloudfront?
* Cost?
* Tools
  * s3cmd

### ngerakines.me

* Build process
* Sync with s3
  * Ensure files are public
  * Create cloudfront invalidation
  * Refresh

### Errata

* Themes
  * https://github.com/holman/left
* Editors
  * http://prose.io/
* Plugins
  * https://github.com/mojombo/jekyll/wiki/Plugins
  * Add support for different template engines
  * Add support for different text processing
  * Add support for additional site content (localization, aggregate data, content types, etc)
  * Add support for build tools (less, minification, etc)

## More

Jekyll links:

* https://github.com/mojombo/jekyll
* http://jekyllrb.com/
* https://pinboard.in/t:jekyll/

S3 links:

* https://console.aws.amazon.com/s3/home?region=us-east-1
* https://console.aws.amazon.com/cloudfront/home?region=us-east-1

My blog and source:

* https://ngerakines.me/
* https://github.com/ngerakines/ngerakines.me
