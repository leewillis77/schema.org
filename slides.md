# Schema.org

!SLIDE title

## Structured data FTW!

![](https://secure.gravatar.com/avatar/2e1cc93e1c8d7f61ca97433e520901d7?s=96&d=mm&r=g)
@leewillis77

!SLIDE

# What is schema.org?

* Shared (open) guidelines by "the search engines"
* (including Google)

!SLIDE 

# What is schema.org?

* Guidelines for semantic markup
* Semantic in the real-world sense

!SLIDE
# HTML
## "This is a paragraph"
## &nbsp;

!SLIDE
# HTML + schema.org markup
## "This is a paragraph
## **and** it is a product description"

!SLIDE

# So why bother?

!SLIDE

* Allows search engines to **understand** content better

!SLIDE

* Used by Google (and Bing) to **enhance** search engine results

!SLIDE

## Better listing
<i class="fa fa-arrow-circle-down" aria-hidden="true"></i>
## More information for users
<i class="fa fa-arrow-circle-down" aria-hidden="true"></i>
## More clickthroughs

!SLIDE

* Better understanding of relevance » Better ranking?

!SLIDE

### Before
![Without rich snippets](images/ecom-without.png)

!SLIDE 
### After
![With rich snippets](images/ecom-with.png)

!SLIDE

# Enhanced SERP listings for
* Breadcrumb navigation
* Products
* Reviews
* Events
* People
* Recipes

!SLIDE

* Many other types defined at schema.org
* Not clear if/when they'll do anything interesting

!SLIDE

# The good part?

!SLIDE

* It's a "zero-cost" feature if you build it in by default
* Just simple changes to the markup

!SLIDE

# A worked example
[http://www.tulliehouse.co.uk/events/winter-wedding-offer](http://www.tulliehouse.co.uk/events/winter-wedding-offer)

!SLIDE

## Data to be marked up

![Tullie house events page](images/tullie-page.png)

!SLIDE

## Mapped to schema.org

![Annotated screenshot showing schema.org mappings](images/tullie-page-markedup.png)

!SLIDE

## Normal markup
![HTML source before schema.org markup](images/before.png)

!SLIDE

## The task

* Wrap entities (Event, Place, Postal Address)
* &lt;div itemscope itemtype="http://schema.org/Event"&gt;

!SLIDE

* Wrap properties
* &lt;h1 itemprop="name"&gt; 

!SLIDE
* Add a (Hidden) address 

!SLIDE
* Entities can be nested
* Event &raquo; Place &raquo; Postal address
* Sub-entities can occur more than once per-item
* Entities can occur more than once per page

!SLIDE
## From this
![HTML source before schema.org markup](images/before.png)

!SLIDE
## To this
![HTML source with schema.org markup](images/after.png)

!SLIDE
## From this
![Results - before](images/results-before.png)

!SLIDE
## To this
![Results - after](images/results-after.png)

!SLIDE
## And this
![Results - after (single event)](images/results-after-single.png)

!SLIDE
# Go forth, and
# mark up your metadata
## [http://schema.org](http://schema.org)

https://developers.google.com/search/docs/guides/search-gallery