---
title: The Vestibule
layout: about
permalink: /vestibule.html
# include CollectionBuilder info at bottom
credits: false
# featured-image value can be one objectid for a photo object in this collection, a relative path to an image in this project, or a full url to any image. If left blank, no featured image will appear at top of About page.
about-featured-image: rfalib_mom_at_14
# set background-position for featured image, "center", "top", "bottom"
position: center
# major heading to display over featured image
heading: The Vestibule
# paragraph text below heading in featured image
sub-heading: 
# additional padding added to the feature to increase size. Give value in em or px, e.g. "5em".
padding: 35em
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% capture 1773map %}

{% include feature/pdf.html objectid="rfalib_1773surveymap" %}

{% endcapture %}


{% capture momthoughts %}
the insularity of my mother’s people, i think, is grounded in the fact that it’s a blended family that descends from generations of untreated trauma. were the circumstances of mama’s conception consensual? i don’t know. i just know that the asymmetrical power dynamics between a female descendant of formerly enslaved people and a scotsman, according to familial oral history, make it such that it was as likely as not that mama — my great-grandmother, who co-parented me, whom i chose to sleep next to for the comfort and her tv — might be the child of rape.

i also know that my great-grandmother was an unwed, teenage mother whose first child was my grandmother. mama, who was the oldest of two, had nine children. my grandmother had seven. i have none. and i fear it will not work out for me.

the only people as insular as my mother’s island people are my father’s, igbo intelligentsia with ties to the ministry of education. mama taught piano, always kept a piano in her house, but i don’t think my parents’ families ever even talked about such things.

{% endcapture %}

{% include feature/accordion.html title1="My Mother in Context" text1=1773map title2="Mom Thoughts" text2=momthoughts %}