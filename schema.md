title: "Schema.org : Structured data FTW"
style: schema.css
output: schema.html

--
# Schema.org
## Structured data FTW!
<hr>  
## @leewillis77
## Freelance software developer
## <small>(WordPress / Laravel / Drupal)</small>
##[www.ademti-software.co.uk](https://www.ademti-software.co.uk) / [plugins.leewillis.co.uk](https://plugins.leewillis.co.uk)

--
### Before we start &hellip;
* This is an SEO-related talk *but* I am not an SEO "expert"
* I am a backend developer *but* this is not a "dev" talk
* It's also not WordPress-specific &hellip;

--
### What is schema.org ?

* Shared guidelines for **semantic** markup
* How to mark-up / tag certain content
* Needed because HTML doesn't give enough context

--
### But HTML5 is semantic ?
* Sort of ... we have
    * <code>&lt;nav&gt;</code>
    * <code>&lt;article&gt;</code>
    * <code>&lt;section&gt;</code>

--
### However ...
* We don't have
    * <code>&lt;product&gt;</code>
    * <code>&lt;event&gt;</code>
    * <code>&lt;rating&gt;</code>
    * <code>&lt;mountain&gt;</code>

--
# So what ?

--
### #theory
* Semantic markup helps search engines **understand**
* Can do smarter stuff with it

--
### #reallife
* Used by Google to enhance search results
* Better listing &#8674; better for users &#8674; more clicks
* Better ranking?

--
# Better listings ?

--
# Before
![Without rich snippets](images/before.png)

--  
# Products & reviews
![With rich snippets](images/after.png)

--

# Recipes
![Recipes](images/recipes.png)

--

# Events
![Events](images/events.png)

--

### Let's get semantic &hellip;
* 583 data types defined at schema.org
    * CreativeWork <small>(Article, Book, Movie, Episode)</small>
    * Event <small>(BusinessEvent, ComedyEvent, Festival)</small>
    * Organization
    * Place <small>(Accommodation, Museum, Mountain & Volcano!)</small>

--
# No idea if they'll do anything interesting
--

### The &ldquo;How-to&rdquo;
* Confusingly, 3 different ways to do it
    * JSON-LD<sup>*</sup>, Microdata, RDF-a
* All just markup changes - nothing *&ldquo;difficult&rdquo;*

<small><sup>*</sup> Google's preferred option</small>

--

# A worked example
## [https://myhill.blog/](https://myhill.blog/)

--

![MyHillBlog example](images/mhb.png)

--

![MyHillBlog annotated](images/mhb-annotated.png)

--

## Basic markup
![Simple JSON](images/json-1.png)

--


## Enrich it with more info
![More markup](images/json-2.png)

--
## Add as little, or as much as you like
## <a href="mhb.json" target="_blank">&laquo;mhb.json&raquo;</a>

--

# But, but &hellip; what about WordPress ?

--
* There are a few plugins around
* Do the basic things, WebSite, Article, BlogPost etc.
    * [wordpress.org/plugins/wp-structuring-markup](https://wordpress.org/plugins/wp-structuring-markup/)
    * [wordpress.org/plugins/schema](https://wordpress.org/plugins/schema/)
* Probably recommend hand-rolling, or hand-customising
* Build data structure as an array, then `json_encode()`

--
* Test your markup : [Structured data testing tool](https://search.google.com/structured-data/testing-tool/)
    * Show what items have been picked up
    * Suggest missing attributes
    * Show errors with data

--
<img style="margin-top: -4em;" alt="Screenshot of structured data testing tool output" src="images/structured-testing.png">

--

* Track Google's crawling of it in [Google Search Console](https://www.google.com/webmasters/)

--
<img style="margin-top: -4em;" alt="Screenshot of search console tracking information" src="images/search-console.png">
--
# Questions?
<hr>
## [leewillis77.github.io/schema.org](http://leewillis77.github.io/schema.org)
<hr>
##[www.ademti-software.co.uk](https://www.ademti-software.co.uk)
##[plugins.leewillis.co.uk](https://plugins.leewillis.co.uk)
##@leewillis77
--
