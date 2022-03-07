---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: page-fullwidth

#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true

memlocklink: https://preview.memlock.io/

---

<h1 style="text-align: center;">Learn smarter</h1>

<div class="row">

</div>
<div class="small-12 large-6 columns" markdown="1">
![a book](/images/unsplash-books-1024x683.jpg)
</div>


<div class="small-12 large-6 columns" markdown="1">

#### Welcome
We're memlock. We're in an exciting invite-only alpha at the moment, but we've got big plans. If your school isn't already involved, get in touch using our [contact form]({% link pages/pages-root-folder/contact.md %}).

If you're a teacher or a student already using memlock, [click here to log in]({{ page.memlocklink }}).

<div class="text-center">
<a class="button large radius alert float-left" href="{{ page.memlocklink }}" target="_blank" style="text-align: center;">Open Memlock</a>
</div>
</div>