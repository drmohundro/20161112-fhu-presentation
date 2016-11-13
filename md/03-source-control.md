# Source Control

<!-- .slide: data-background-image="/images/nes.gif" -->
<!-- .slide: class="shadowed-text" -->

<..>

## What is source control?

Also called version control, source control management (SCM), etc.

<..>

## College Experience

My experience with source control tools can be summed up in (almost) one word...

![Blocking](/images/nothing.gif) <!-- .element class="fragment" -->

Note:

* I literally didn't use source control for the first 3 years of college
  * I mostly just used floppy drives (yes, really)

<..>

## How I Managed Source in College

![Organization](/images/organization.png)

<..>

## At least until my Senior Project

* I was working with four people
* It was weeks to months of work
* Sounds more like the "real world" right?

<..>

## Demo

Let's look briefly at Git...

Note:

* Written to track source for Linux by Linus himself
* Has hundreds if not thousands of contributors
* Popularized by GitHub for OSS
* **NOTE** Use Fork or SourceTree for visual view
  * Plenty of GUIs, but many use the CLI with Git
  * GUI is just easier to visualize what is going on

<..>

## Why Source Control is so important

* Helps you answer "why", "who", "what", "when", etc.
* Why did someone do this?
* Who can I blame (or praise!) for this breaking?
* When did this break?
* What commit broke it?

Note:

* Have you ever written code and then come back the next day and you just **knew** it used to work?
  * Well that is why frequent commits are great
    * `got addition working, but multiplication doesn't`
    * `woo, multiply works!`
    * `adding is broken now?!?`
* I *literally* use SCM every day
  * Depending upon the day, I use it more than email or chat
* See examples
  * https://github.com/drmohundro/SWXMLHash/issues/33
    * links to https://github.com/drmohundro/SWXMLHash/commit/cf5e4ad936ad287f357872543c6178d3a39f8c4d
  * https://github.com/clearfunction/tapgive/pull/157
    * blame - https://github.com/clearfunction/tapgive/blame/a31dc2ea48912b3280b17bf9137d3fa0a89ce6da/gems/active_processor/app/models/active_processor/stripe_processor_gateway.rb#L40-L44
    * new blame - https://github.com/clearfunction/tapgive/blame/fbb0e6894ab0212d4e4389c3af0beca441b5a606/gems/active_processor/app/models/active_processor/stripe_processor_gateway.rb#L40-L44

<..>

## SCM is really just textual communication

![Doge](/images/doge.gif)

<..>

## Stats and Visualization Demo

* GitStats
* Gource

Note:

* http://gitstats.sourceforge.net/
* http://gource.io/