# Paragraphs in Lists

There should be new lines between the paragraphs of lists:

~~[…]~~ think about _dependency direction._

There are two ways you can write HTML and CSS:

1. ~~“Separation of Concerns.”~~ _CSS that depends on HTML._

   Naming your classes based on your content (like `.author-bio`) treats your HTML as a dependency of your CSS.

   The HTML is independent; it doesn’t care how you make it look, it just exposes hooks like `.author-bio` that the HTML controls.

   Your CSS on the other hand is not independent; it needs to know what classes your HTML has decided to expose, and it needs to target those classes to style the HTML.

   In this model, your HTML is restyleable, but your CSS is not reusable.

2. ~~“Mixing Concerns.”~~ _HTML that depends on CSS._

   Naming your classes in a content-agnostic way after the repeating patterns in your UI (like `.media-card`) treats your CSS as a dependency of your HTML.

   The CSS is independent; it doesn’t care what content it’s being applied to, it just exposes a set of building blocks that you can apply to your markup.

   Your HTML is not independent; it’s making use of classes that have been provided by the CSS, and it needs to know what classes exist so that it [combines] them however it needs to to [sic] achieve the desired design.

   In this model, your CSS is reusable, but your HTML is not restyleable.

The same should be the case here:

> ~~[…]~~ think about _dependency direction._
>
> There are two ways you can write HTML and CSS:
>
> 1. ~~“Separation of Concerns.”~~ _CSS that depends on HTML._
>
>    Naming your classes based on your content (like `.author-bio`) treats your HTML as a dependency of your CSS.
>
>    The HTML is independent; it doesn’t care how you make it look, it just exposes hooks like `.author-bio` that the HTML controls.
>
>    Your CSS on the other hand is not independent; it needs to know what classes your HTML has decided to expose, and it needs to target those classes to style the HTML.
>
>    In this model, your HTML is restyleable, but your CSS is not reusable.
>
> 2. ~~“Mixing Concerns.”~~ _HTML that depends on CSS._
>
>    Naming your classes in a content-agnostic way after the repeating patterns in your UI (like `.media-card`) treats your CSS as a dependency of your HTML.
>
>    The CSS is independent; it doesn’t care what content it’s being applied to, it just exposes a set of building blocks that you can apply to your markup.
>
>    Your HTML is not independent; it’s making use of classes that have been provided by the CSS, and it needs to know what classes exist so that it [combines] them however it needs to to [sic] achieve the desired design.
>
>    In this model, your CSS is reusable, but your HTML is not restyleable.

Also:


1. > [`XMP`, `LISTING`, and `PLAINTEXT`] are obsolete tags for preformatted text that predate the introduction of `PRE`.

   Remember: The spec was largely written in 1996.

2. > `CENTER` was introduced by Netscape before they added support for the HTML 3.0 `DIV` element. It is retained in HTML 3.2 on account of its widespread deployment.

   As we noted [in the HTTP Archive’s Web Almanac](https://almanac.httparchive.org/en/2020/markup), Google is still using `center`, and has been for 22 years (!).

3. > [`action` on `form`] specifies a URL which is either used to post forms via email, e.g. `action="mailto:foo­@bar.com"`, or used to invoke a server-side forms handler via HTTP ~~[…]~~.

   I didn’t know about the `mailto:` option—yet [it doesn’t seem to work (anymore)](https://hell.meiert.org/core/html/form-mailto.html).

4. The HTML 3.2 spec _did_ bring up the option to use tables for layout:

   > [Tables] can be used to markup tabular material or for layout purposes.

   It cautions about problems “when rending [sic] to speech or to text only user agents”—but “can be used for layout purposes” is still there.

5. Finally, when you think of `font` elements, you may remember the `face` attribute. Now, that, too, is an old attribute; but:

   > `FACE` is not part of HTML 3.2.

   Yet to find out about the history of `face`, we would need to see Sauron 🤷‍♂️