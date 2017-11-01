# Details of this parody site:

After Benji Weber tweeted about acronyms 
being misappropriated and mentioning Continuous Isolation, a mischief-loving synapse in my head trigger, and 
I made this site. Continuous Isolation is an 'antithetic acronym' as Benji's follower Anthony Green 
pointed out (or coined). 

![google chromescreensnapz007](https://user-images.githubusercontent.com/82182/32221957-d69aca78-be0d-11e7-8faa-e8128bbc468e.png)

[Link to Tweet as can't embed in a README](https://twitter.com/benjiweber/status/831193574502961154)

Anyway, so here it is, a GitHub-backed parody site called [ContinuousIsolation.com](https://continuousisolation.com/).

<span style="background-color:yellow"><b>And this is a lesser part in of a community effort to get more traction for eXtreme Programming. Albeit one rooted in mischief</b></span>

# How to contribute:

Pull Requests welcome as you would expect.  But if you're super short on time, just raise a GitHub issue and 
type in your contrib/idea free-form. It'll make it to a source document soon after via good old copy/paste 
(one of the Continuous Isolation best practices no doubt).

If a markdown-editing and Hugo build toolchain is too much, then feel free to email me content - paul@hammant.org. I'll credit in the commit message of course (unless you say not to).

# Rules for participation:

1. This is a parody site of course. It is as if it was written in a parallel universe, where the **inverse** of all these are true:
* Agile generally, and eXtreme Programming specifically
* Continuous Integration in particular
* Continuous Delivery/Deployment
* DevOps
* Lean
* Critical path/chain concepts

In fact, those never happened in this universe, so cannot be mentioned. Source Control exists (a rich parody seam). Builds exist (but are only really important in the wind up to release every 18 months). 
Testing is better done manually of course, and as close to go-live as possible (just once)

2. Nothing snide or language dripping with sarcasm, please. No 'in jokes' please. Just use a matter-of-fact* or dead-pan style.

&ast; Matter-of-fact: ([thesaurus.com](http://www.thesaurus.com/browse/matter-of-fact), [dictionary.com](http://www.dictionary.com/browse/matter-of-fact))

# Technologies Used:

This is a [Hugo](https://gohugo.io/getting-started/installing/) site that auto-deploys on commit/push.

Articles are in the content/ folder.  You will need a TOML front-matter section (copy one of the others). 
Hugo uses [blackfriday](https://github.com/russross/blackfriday) markdown syntax.

The Hugo theme used [its own
shortcodes](https://themes.gohugo.io/theme/docdock/shortcodes/) if you wish to go beyond simple markdown, 
though I'm pretty sure you can past in integral HTML snippets if you want to. 

