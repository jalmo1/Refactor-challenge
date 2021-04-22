# Refactor-challenge

--HTML--

In this refactor challenge, I immediately noticed that almost, if not all the tags were <div> tags.

I changed line 13's <div> to <header>
Also added an <a href="#"> to the <h1>

On line 19 I changed the <div> to <nav> so the website knows it is a navigation element

On line 36 I changed the <div> to <main> so the website knows what the main content is

line 38 I added an ID for "search-engine-optimization" so the <nav> link works

On lines 40, 51, and 62 I added an alt="" to the <img> so the images have a description for screen readers
Also added the alt="" to the <img> on lines 77, 86, 95

On line 73 I changed the <div> to <section> to declare another section in the webpage

On line 103 I changed the <div> to <footer> to declare the footer section 


--CSS--

In the css file I had to change a few of the elements in the .header {} to nav instead of div

I also reorganized the ".search-engine-optimization" so that all of the declarations are together
I did the same thing for ".online-reputation-management" and 
".social-media-marketing" so they are all together

I also moved a {} and p {} to the top of the css file right under the body {} declaration