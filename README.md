# Jekyll-Author
Author page generator, including pagination and rss feeds.

This generator also mimicks Jekyll's paginator, so it can reuse both its settings and `_include` files.

# Usage

* `_includes\custom\author_feed.xml` is set up in advance. Adjust if needed.
* Set up `_layouts\author_index.html` with your customized layout.

The following variables are available:

## Page
* slug
* author 
    * author object taken from _data/authors.yml
    * slug is the key
* dir
* title (author name)
* subscriptionUrl (rss feed url)

## Context
* paginator
    * page
    * per_page
    * posts
    * total_posts
    * total_pages
    * previous_page
    * previous_page_path
    * next_page
    * next_page_path
    
    
## _config.yml
* author_dir
* paginate