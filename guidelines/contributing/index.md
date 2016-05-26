---
layout: guidelines
---

## Contributing to the draft

We have a few options for making contributions to the draft. 

1. Use Hypothes.is annotations to comment on any part of the text.
2. Add comments or suggestions through the GH issues.
3. Make a pull request to the gh-pages branch.

For text under discussion, options 1 and 2 are preferred for both transparency and consensus-building. PRs will be accepted for revisions based on those discussions but aren't necessary to contribute. 

For PRs related to the guidelines section (all the wonky HTML, apologies), we're providing a basic structure to follow.

Adding a new category/subcategory (and add it to the ToC `UL`)
{% highlight html %}
<h2 id="CATEGORY"></h2>
<h3 id="CATEGORY-SUBCATEGORY"></h3>
<div class="criteria">
    <div class="criterion">
    </div>
    ....
    <div class="criterion">
    </div>
</div>
{% endhighlight %}

{% highlight html %}
<!-- add a new criterion -->
<div class="criterion">
    <div class="revisions">
        <p class="">See class options</p>
    </div>
    <div class="metadata">
        <!-- see below for the "metadata" structure -->
    </div>
</div>
{% endhighlight %}

The options for a criterion (original, revised, added, deprecate, flag) as a `p` child under `div.revisions`.

{% highlight html %}
<!-- original statement -->
<p class="original"></p>

<!-- flag original statement for review -->
<p class="original questioned"><i class="fa fa-warning fa-fw"></i></p>

<!-- revise statement -->
<p class="revision"><i class="fa fa-pencil fa-fw"></i></p>

<!-- add a statement -->
<p class="revision added"><i class="fa fa-plus-circle fa-fw"></i></p>

<!-- deprecate statement -->
<p class="original deprecated"><i class="fa fa-trash fa-fw"></i></p>
{% endhighlight %}

"Metadata" elements as a sibling to `div.revisions`.

{% highlight html %}
<div class="metadata">
    <h4>Application</h4>
    <p></p>
    <h4>Grouping</h4>
    <p></p>
    <h4>Notes</h4>
    <p></p>
    <h4>References</h4>
    <p><a href="#"></a></p>
    <h4>Similar Criteria</h4>
    <p><a href="#"></a></p>
</div>
{% endhighlight %}



