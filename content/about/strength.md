+++
title = "About Us"
description = "About Us"
keywords = ["Sri Bharathi Group","About Sri Bharathi Group","SBG","Filter Pads", "Filter Media"]
+++

<!-- A shortcode to render a series list unrelated to the current article -->
{{< sbglist distilling-jruby >}}

* Established by an eminent subject matter expert with more than 40 years of experience in the industry.
* We have tie-up with technical leaders and other organizations in the Filtering Industry.
* Manufacturing of High Quality Filter Pads, Filter Bags and other Industrial Filtering Equipments.
* We have been continuously in the Research & Development of the products tailored to the technological up heaves and in the most updated versions to the requirements of the clients since our inception.
* Its activities are governed by the ethical principles and garnered to the glory for its maintaining the promises and the standards.
* Has state of the art technology for the Filter Pads manufacturing.
* Eminent subject matter experts in the filed of Filter Pads & Filtering Technology.
* Recognized as a reputed & quality supplier by multiple leading companies in India.

Normal quote:
{{< blockquote >}}
  This is a simple quote.
{{< /blockquote >}}

Quote with author
{{< blockquote author="Author2" >}}
  This is a quote with only an Author named Author2.
{{< /blockquote >}}

Quote with author and source
{{< blockquote author="Author3" source="Source" >}}
  This is a quote from Author3 and source "source."
{{< /blockquote >}}

Quote with author and link
{{< blockquote author="Author4" link="https://www.google.com" >}}
  This is a quote from Author4 and links to https://www.google.com.
{{< /blockquote >}}

Quote with author, link and title
{{< blockquote author="Author5" link="https://www.google.com" title="Google" >}}
  This is a quote from Author5 and links to https://www.google.com with title "Google."
{{< /blockquote >}}

Quote with author and a link longer than 32 characters, string is first cut at 32 characters then everything after the last forward slash is removed
{{< blockquote author="Author6" link="https://twitter.com/CryptoGangsta/status/716427930126196737" >}}
  This is a quote from Author5 and links to https://twitter.com/CryptoGangsta/status/716427930126196737 which is longer than 32 characters.
  <br>And this is a new line in the quote with the HTML br tag.
{{< /blockquote >}}

Test from the Octopress blockquote page at: http://octopress.org/docs/plugins/blockquote/
{{< blockquote author="@allanbranch" link="https://twitter.com/allanbranch/status/90766146063712256" >}}
  Over the past 24 hours I've been reflecting on my life & I've realized only one thing. I need a medieval battle axe.
{{< /blockquote >}}


### Named variable test

* {{< wp tag="VIC_cipher" >}}
* {{< wp tag="VIC_cipher" lang="fr" >}}
* {{< wp tag="VIC_cipher" lang="fr" title="" >}}
* {{< wp tag="VIC_cipher" title="VIC Cipher" >}}
* {{< wp tag="VIC_cipher" lang="en" title="VIC Cipher" >}}


### Positional variable test

* {{< wp VIC_cipher >}}
* {{< wp VIC_cipher fr >}}
* {{< wp VIC_cipher "" fr >}}
* {{< wp VIC_cipher "VIC Cipher" >}}
* {{< wp VIC_cipher "VIC Cipher" fr >}}

{{< codecaption lang="html" title="Code caption shortcode" >}}
<figure class="code">
  <figcaption>
    <span>{{ .Get "title" }}</span>
  </figcaption>
  <div class="codewrapper">
    {{ highlight .Inner (.Get "lang") "linenos=true" }}
  </div>
</figure>
{{< /codecaption >}}
