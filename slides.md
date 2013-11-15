# Schema.org

!SLIDE title

# Schema.org
## Rich snippets FTW!

!SLIDE

# What is schema.org?

* Shared guidelines by "the search engines"
* (Including Google)
* Guidelines for semantic markup

!SLIDE

# Why bother?

* Allows search engines to **understand** content better
* Used by Google to **enhance** search engine results

!SLIDE

# So what?

!SLIDE

* Better listing / more info for users
    * &raquo; Increased clickthroughs
* Better understanding of relevance
    * &raquo; Better ranking?

!SLIDE

### Before
![Without rich snippets](images/ecom-without.png)

!SLIDE 
### After
![With rich snippets](images/ecom-with.png)

!SLIDE

# Enhanced SERP listings for
* Breadcrumb navigation
* Products&nbsp;&nbsp;&nbsp;Reviews
* Events&nbsp;&nbsp;&nbsp;&nbsp;People&nbsp;&nbsp;&nbsp;&nbsp;Recipes

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
# Go forth, and
# mark up your metadata
## [http://schema.org](http://schema.org)