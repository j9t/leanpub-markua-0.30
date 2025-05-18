# meiert.com Test

<p class=note>This and many other posts are also available as a pretty, well-behaved ebook: <a href="https://www.amazon.com/dp/B010PQPT90/?tag=meiert-20"><cite>On Web Development</cite>.</a>

“1 + 1 = 3 (or more)” is an important design effect described by Josef Albers and [Edward Tufte](https://www.edwardtufte.com/). It means that two elements in close proximity cause a visible interaction:

<figure>
	<img src="https://d3rdtowr0c5lpf.cloudfront.net/media/2007/1+1=3.gif" alt="Two parallel bars that appear to create a third element." loading=lazy>
	<figcaption>1 + 1 = 3. (Copyright Al Globus.)</figcaption>
</figure>

This interaction can result in perceiving _information that is not there_. Beside having a negative because distracting and distorting impact on charts and graphics it can also, to use [Steve Krug’s](https://sensible.com/) words, cause undesirable “busyness” and “background noise” on websites.

Therefore, “1 + 1 = 3” is one of the effects you want to avoid, at least be aware of, when creating graphs and designing websites. (Of course, a designer always wants to keep information design principles in mind.) [Edward Tufte’s books](https://www.amazon.com/gp/search?ie=UTF8&camp=1789&creative=9325&index=books&keywords=edward+tufte&linkCode=ur2&tag=meiert-20&linkId=KSL5KZCJ42GG6GV3) are invaluable resources in this regard, and I recommend checking out the following excellent articles:

* Al Globus on [<cite>Principles of Information Display for Visualization Practitioners</cite>](https://web.archive.org/web/20070111090247/http://www2.cs.uregina.ca/~rbm/cs100/notes/spreadsheets/tufte_paper.html) ([German](/de/publications/translations/uregina.ca/tufte/)), and
* Waynes Smith on [<cite>Graphics and Web Design Based on Edward Tufte’s Principles</cite>](https://web.archive.org/web/20070105162518/http://www.washington.edu/computing/training/561/zz-tufte.html) ([German](/de/publications/translations/washington.edu/tufte/)).

* * *

<p class=note>This and many other posts are also available as a pretty, well-behaved ebook: <a href="https://www.amazon.com/dp/B010PQPT90/?tag=meiert-20"><cite>On Web Development</cite>.</a>

An important finding of Stanford University’s work regarding [web credibility](http://credibility.stanford.edu/) is that photos can make websites more credible. A study by B.J. Fogg et al., [<cite>Web Credibility Research: A Method for Online Experiments and Early Study Results</cite> (PDF, 25 KB)](https://web.archive.org/web/20060718034129/http://captology.stanford.edu/pdf/WebCred%20Fogg%20CHI%202001%20short%20paper.PDF), showed how “a photograph of an author had significant effects on how people perceived <ins>[credibility]</ins>”:

<table>
	<thead>
		<tr>
			<th scope=col style="width: 32%;">Credibility measure
			<th scope=col style="width: 17%;">No author photo (mean)
			<th scope=col style="width: 17%;">Casual author photo (mean)
			<th scope=col style="width: 17%;">Formal author photo (mean)
			<th scope=col style="width: 17%;">Statistically significant? (between groups)
	<tbody>
		<tr>
			<th scope=row>How believable is article?
			<td>.70
			<td>.41
			<td>.92
			<td>p = .03
		<tr>
			<th scope=row>How trustworthy is article?
			<td>.17
			<td>–.17
			<td>.41
			<td>p = .003
		<tr>
			<th scope=row>How competent is article?
			<td>.35
			<td>.15
			<td>.67
			<td>p = .02
		<tr>
			<th scope=row>How credible is article?
			<td>.34
			<td>.15
			<td>.47
			<td>NS
		<tr>
			<th scope=row>How unbiased is article?
			<td>.76
			<td>.58
			<td>.63
			<td>NS
		<tr>
			<th scope=row>How expert is article?
			<td>.27
			<td>–.09
			<td>.47
			<td>p = .009
		<tr>
			<th scope=row>Composite measure (combining all six items)
			<td>.42
			<td>.17
			<td>.60
			<td>p = .02
</table>

Though this is just one out of a number of aspects of web credibility—the [Stanford-Makovsky Web Credibility Study 2002 (PDF, 461 KB)](https://web.archive.org/web/20060718122114/http://captology.stanford.edu/pdf/Stanford-MakovskyWebCredStudy2002-prelim.pdf) is still a highly recommendable read—it is an important one, and eventually still surprising. As _professional sites should consider all [major credibility factors](http://credibility.stanford.edu/guidelines/)_ it’s interesting to note the potential of many sites. It’s no rocket science to create credible, trustworthy offers of information ([no, MySpace](/blog/definition-of-the-dark-side-myspace/)), and we shouldn’t get tired to work on that aim.

* * *

<p class=note>This and many other posts are also available as a pretty, well-behaved ebook: <a href="https://www.amazon.com/dp/B010PQPT90/?tag=meiert-20"><cite>On Web Development</cite>.</a>

The Web Dev Report, issue #2, this time featuring a classic situation.

<figure>
	<a href="/media/2008/wdr-2.png"><img src="https://d3rdtowr0c5lpf.cloudfront.net/media/2008/wdr-2.png" alt="The Web Dev Report: Web developers needed for a website." loading=lazy></a>
</figure>

<details>
	<summary>Transcript.</summary>
	<dl>
		<dt>(Back in 2005.)</dt>
		<dt>Guy 2:</dt>
		<dd>How many web developers does it take to build a website?</dd>
		<dt>Guy 1:</dt>
		<dd>…?</dd>
		<dt>Guy 2:</dt>
		<dd>Two.</dd>
		<dd>One to build the tables. Another one to calculate the values of the <code>colspan</code> and <code>rowspan</code> attributes.</dd>
		<dt>Guy 1 and Guy 2:</dt>
		<dd><strong>Muahahahahahahahahahahahahahahahahaha.</strong></dd>
	</dl>
</details>

* * *

HTML conformance data for 2024 are in, and the good news first: There’s an increase in the number of valid website [home pages](https://webglossary.info/terms/home-page/), going from 0 to 1.

The flip side: **199 of 200 of the most popular websites use HTML that’s faulty, that doesn’t exist, and/or that doesn’t work.**

<p class=note>The usual disclaimer: The following data gives an impression of precision that is greater than warranted. The point of this annual analysis is to check on full HTML conformance—absence of markup errors—on home pages; that is, the specific error counts don’t matter for the purpose of telling conformance or non-conformance, and other pages aren’t being checked. I’m providing the data for further study and for comparability to previous years.

<p class=note>Also, before we begin: Where’s CSS? I took CSS validation out because 1) HTML quality is much more important than CSS quality (cf. <a href="/blog/get-the-html-right/"><cite>The Most Important Thing Is to Get the HTML Right</cite></a>, though it could be clearer), and 2) the W3C CSS validator seems understandably but chronically behind the specifications, with false positives and false negatives (my experience thus far, which carries no judgment).

### [Contents](#toc) {id:#toc}

1. [Analysis](#toc-analysis)
2. [HTML Conformance in 2024](#toc-conformance-2024)
3. [HTML Conformance over Time](#toc-conformance-over-time)
4. [Notes and Observations](#toc-notes)
5. [Interpretation](#toc-interpretation)

### Analysis {id:#toc-analysis}

Like every year since [2021](/blog/valid-html-2021/) (cf. [2022](/blog/valid-html-2022/), [2023](/blog/html-conformance-2023/)) I used the annual update of [the Ahrefs Top 1,000 websites](https://ahrefs.com/top/) to check the home pages of the first now 200 websites on HTML conformance. [<sup>*</sup>](#note-ahrefs)

For this purpose I took all the respective URLs, prepared HTML validation URLs, [validated](https://validator.w3.org/) the respective pages, and documented the error counts of the 200 tests in [a spreadsheet](https://docs.google.com/spreadsheets/d/1Qw1lUBmuOT1T7ekfTym0zpFpOXkOyd5zCjPUqO4Bk-k/edit):

<figure>
	<a href="https://docs.google.com/spreadsheets/d/1Qw1lUBmuOT1T7ekfTym0zpFpOXkOyd5zCjPUqO4Bk-k/edit"><img src=https://d3rdtowr0c5lpf.cloudfront.net/media/2024/conformance.png alt="Top 200 websites conformance data spreadsheet teaser." loading=lazy></a>
	<figcaption>The most-frequented websites and their use of HTML according to the specification.</figcaption>
</figure>

### HTML Conformance in 2024 {id:#toc-conformance-2024}

“Improved”: 1 of the 200 home pages have 0 HTML conformance errors—a [splash screen of the Unique Identification Authority of India](https://uidai.gov.in/).

Improved: 5 home pages (of Adobe, Speedtest, Poki, the NHS, and Gramedia) were super-close to conformance, with 1 error each.

The issues—error messages—on these single-error home pages?

* “An `img` element must have an `alt` attribute, except under certain conditions.”
* “Bad value `true` for attribute `async` on element `script`.”
* “No `li` element in scope but a `li` end tag seen.”
* “Bad value `tel: 111` for attribute `href` on element `a`: Illegal character in scheme data: space is not allowed.”
* “Element `head` is missing a required instance of child element `title`.”

Improved: 44 more home pages had a single-digit number of issues.

Degraded: 56 were far away from conformance with any specification (100 or more errors).

Improved: The average number of HTML errors is 99.34.

Improved: The HTML errors median is 35.5.

(Improved: The mode is 5.)

### HTML Conformance over Time {id:#toc-conformance-over-time}

We need to test more websites for this to be significant, but after this new analysis, here is how error counts developed over the years:

<table>
	<thead>
		<tr>
			<th scope=col style="width: 40%;">
			<th scope=col style="width: 15%;">2021
			<th scope=col style="width: 15%;">2022
			<th scope=col style="width: 15%;">2023
			<th scope=col style="width: 15%;">2024
	<tbody>
		<tr>
			<th scope=row>Average number of HTML errors on home page
			<td>125.22
			<td>125.63 →
			<td>132.14 ↗
			<td>99.34 ↘
		<tr>
			<th scope=row>Home pages without errors
			<td>2%
			<td>0% ↘
			<td>0% →
			<td>0.5% ↗
</table>

### Notes and Observations {id:#toc-notes}

First, the W3C HTML validator (i.e., the “Nu” portion handling living HTML) is _too_ helpful and makes work on fixing and analyzing HTML unnecessarily difficult. If you’re using it, too, you’ll know how it mixes HTML errors with CSS and other errors. This has significantly slowed down the work on this analysis, and introduced a potential error source by requiring to manually deduct non-HTML errors from the error counts. This is a design and usability issue, though, so I hope the team can improve this—for example, by grouping and counting errors by language and topic, or by making this configurable. (Subscribe to and chime in on [Nu Validator issue #940](https://github.com/validator/validator/issues/940) if you like to see this improved, too.)

Many more companies and organizations than ever block the W3C HTML validator. In 2023, [12 of 100 websites](https://docs.google.com/spreadsheets/d/1RlntUnagJdSUA71EbIKC_WZpfQ-3_8ysc5vUsaRH798/edit) couldn’t be validated—in 2024, it was double (relatively speaking), with 48 of 200 websites. I didn’t (and might not have been able to) analyze the nature of the blocking though—that is, it could be intentional (as with geo-blocking), it could be unintentional (perhaps using some overeager edge tooling).

Redirects, interstitials, cookie _pages_ made validation hard as well. In [the legend](https://docs.google.com/spreadsheets/d/1Qw1lUBmuOT1T7ekfTym0zpFpOXkOyd5zCjPUqO4Bk-k/edit?gid=851521783#gid=851521783) I’m emphasizing how I’m not caring about or highlighting these instances anymore—after all, the analysis checks on whether or not the most popular websites use valid HTML, and for that purpose, it’s interesting but not decisive how many issues there are, or if a page to be tested doesn’t happen to be the main page.

There was [one website](https://docs.google.com/spreadsheets/d/1Qw1lUBmuOT1T7ekfTym0zpFpOXkOyd5zCjPUqO4Bk-k/edit?range=201:201) in the sample, Fast.com, that used HTML 4.01 Strict! Unfortunately, the document was written following [XHTML–HTML](/blog/write-html/#toc-the-xhtml-way), which came with many related conformance issues.

There was also one instance that couldn’t be validated at all. I’ve passed on my observations to the W3C team.

### Interpretation {id:#toc-interpretation}

I’m sharing this annual report for _your_ and the community’s interpretation.

Yet here are two cents:

For the new data, there are several improvements (notably a lower average number of HTML errors). That’s better than if we had observed more degradations, but it’s not clear whether we’re dealing with any significant shift. Sustained improvements with more websites using valid HTML would underscore such a shift.

I’m writing [a lot about HTML conformance](https://cse.google.com/cse?cx=007435340685329731950%3Auo6twvdbp_m&q=valid+html), and I am to write more about it. For those of you who don’t know this part of my work, I think we all benefit from ensuring HTML conformance because it’s a foundational quality attribute that hedges against shipping unnecessary and dysfunctional code and payload to our users, and because it’s the easiest-to-implement quality bar we can employ in our profession. **Professional web developers write valid HTML.**

If you’re working on a website covered in the analysis—really, if you’re working on _any_ website—, write HTML, and check (validate) that what you ship is valid HTML.

<p class=note id="note-ahrefs"><sup>*</sup> I do so faithfully, that is, I don’t check and question Ahrefs’ methodology. There had been concerns about some of these top sites in the past—including that a few seemed spammy—, but I’m leaving that issue in Ahrefs’ part of the field. This is not to say that you shouldn’t be critical about any of this.

* * *

<div>
	<form action="https://leanpub.com/rote-learning-html-css"><button>Download now</button></form>
	<p>EPUB and PDF, at Leanpub (<a href="#sellers">other options</a>).
</div>

Here’s the book that allows you to build or confirm your HTML and CSS knowledge in a way no other book or site allows you to: [<cite>Rote Learning HTML &amp; CSS</cite>.](https://leanpub.com/rote-learning-html-css)

What’s great is, the book is free, and [the source](https://github.com/frontenddogma/rote-learning-html-css) is public.

What’s not-so-great is, the book is boring. Super-boring. (Really.)

<table>
	<tr>
		<th scope=row style="width: 33%;">Format
		<td><a href="https://leanpub.com/rote-learning-html-css">Ebook</a> <span>(EPUB and PDF)</span>
	<tr>
		<th scope=row>Price
		<td>Free!
	<tr>
		<th scope=row>Preview
		<td><a href="https://samples.leanpub.com/rote-learning-html-css-sample.pdf">Select chapters</a> <span>(PDF, 151 KB)</span>
	<tr>
		<th scope=row>Extras
		<td><a href="https://github.com/frontenddogma/rote-learning-html-css">Source code</a>
	<tr>
		<th scope=row>Length
		<td>62 pages <span>(PDF)</span>
	<tr id="sellers">
		<th scope=row rowspan="5">Sellers
		<td><a href="https://books.apple.com/us/book/rote-learning-html-css/id6633442792?ls=1">Apple Books</a>
	<tr>
		<td><a href="https://www.kobo.com/us/en/ebook/rote-learning-html-css">Kobo</a>
	<tr>
		<td><a href="https://play.google.com/store/books/details?id=KYAZEQAAQBAJ">Google Play Books</a>
	<tr>
		<td><a href="https://leanpub.com/rote-learning-html-css">Leanpub</a>
	<tr>
		<td><a href="https://j9t.gumroad.com/l/rote-learning-html-and-css">Gumroad</a>
	<tr>
		<th scope=row>Latest version
		<td>1.0.5
</table>

> Endless lists without explanations. Avoid this book at all costs.

…readers say [on Google Play Books](https://play.google.com/store/books/details?id=KYAZEQAAQBAJ).

### Description

<a href="#sellers"><img src="https://d3rdtowr0c5lpf.cloudfront.net/de/publications/books/rote-learning-html-and-css/cover-s.png" alt="The cover of “Rote Learning HTML &amp; CSS.”"></a>

> This is a supplementary—and not beginner-friendly—book about HTML and CSS, and one of the most boring books you’ll ever read.
>
> It contains long lists of HTML elements and attributes and CSS selectors and properties.
>
> Why bother? Why read this book?
>
> Because it provides you with a unique opportunity to learn HTML and CSS, one that isn’t available in this form elsewhere.
>
> Its goal is to show you the rough and raw skeleton of HTML and CSS, so that you can focus on that. Elements, attributes, selectors, properties. No explanations, no examples, no context. The raw material.
>
> The idea is that even when you only review this book once, you will already notice things about HTML and CSS that you weren’t aware of and couldn’t have noticed otherwise.
>
> And still, this is one of the most boring books you’ll ever read. Enjoy.

❧ Many thanks to Martha Martins, who edited this title, as well as to [Bert Bos](https://www.w3.org/People/Bos/), who was so kind to help answer some W3C-related questions. Thank you!

<p class=note>If you like the book and want to learn more about HTML and CSS (or web development), check out some of <a href="https://cse.google.com/cse?cx=007435340685329731950%3Auo6twvdbp_m&q=book+preview+description">my</a> or <a href="https://frontenddogma.com/books/">Frontend Dogma’s books</a>. Or <a href="https://opencollective.com/frontenddogma">become a patron</a> over at Open Collective. That helps to do freestyle projects like this one.