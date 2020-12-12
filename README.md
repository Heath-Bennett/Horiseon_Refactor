# Horiseon_Refactor

Per customers request I refactored Horiseon's website adding accessibility.

This was achieved by changing \<div> elements to their respective semantic element.  Symantic Elements that were included are:

* \<body>
* \<header>
* \<nav>
* \<figure>
* \<main>
* \<aside>
* \<section>
* \<footer>

Each block of code in the HTML document has been commented to document changes. 

CSS rules that corresponded to the altered div elements have been changed from class selectors to element selectors. 

I have also spaced out the code to aid in the readability factor of the HTML document.

The classes **benefit-lead**, **benefit-brand**, and **benefit-cost** were changed to **benefit**. The corresponidng CSS selectors were changed to **benefit** and combined into one rule.

The classes **search-engine-optimization**, **online-reputation-management**, and **social-media-marketing** have been change to **search-online-social**.  The corresponding CSS selectors were changed to **search-online-social** and combined into one rule. 

The id **search-engine-optimization** was added to thie first section in main.  This repaired the broken link in navigation. 