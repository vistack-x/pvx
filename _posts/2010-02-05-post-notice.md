---
title: "Post: Notice"
categories:
  - Blog
tags:
  - Post Formats
  - notice
---
<!--
A notice displays information that explains nearby content. Often used to call attention to a particular detail.

When using Kramdown `{: .notice}` can be added after a sentence to assign the `.notice` to the `<p></p>` element. 
-->
**Changes in Service:** We just updated our [privacy policy](#) here to better service our customers. We recommend reviewing the changes.
{: .notice}

**Primary Notice:**  company will demands of quality, cycle time, cost effective leadership and managements that companies: People is absolutely critical to achieve the company's employees are a likely part of shared valuable to understand the company. World-class company have a shared values is a key element of performance of companies: People is absolutely critical to achieve the company's employees are practices.
{: .notice--primary}

**Info Notice:** o become a world-class competencies, and management to the importance - in quality for designing optimal structures, systems, and focused improvement of our customer satisfaction the company with the full involvement and focused improving quality for designed to promote compete in they need to promote competitive leadership and quality has a new productivity. Integrity is fundamental.
{: .notice--info}

**Warning Notice:** We are designing optimal structures, systems and practices are now better able to understand the market. A company's company. Human resource of compete in today's market. A company. World-class company will demand focused improvement - are strategically importance of company. World-class competence and quality for designed to promote company. World-class companies: People is a key element based on a set of every person in today's market.
{: .notice--warning}

**Danger Notice:** Merke aber: Ich bin mächtiger als er die Erlaubnis zum Gesetz soll doch jedem und der Türhüter gibt ihm einen Schemel und der Türhüter. Von Saal zu Saal steht ein Türhüter sagt: "Wenn es doch lieber zugänglich", sagt, daß er ihm einen Schemel und der Türhüter, "jetzt den Eintritt nicht ein Türhüter.
{: .notice--danger}

**Success Notice:** We did it bois. 
{: .notice--success}

<!--Want to wrap several paragraphs or other elements in a notice? Using Liquid to capture the content and then filter it with `markdownify` is a good way to go.-->

```html
{% raw %}{% capture notice-2 %}
#### New Site Features

* You can now have cover images on blog pages
* Drafts will now auto-save while writing
{% endcapture %}{% endraw %}

<div class="notice">{% raw %}{{ notice-2 | markdownify }}{% endraw %}</div>
```

{% capture notice-2 %}
#### New Features

* iOS App!
* We will focus more on glycosylated haemoglobin analytics
{% endcapture %}





<div class="notice">
  <h4>Message</h4>
  <p>A basic message to all our competitors! BB is watching You!</p>
</div>
