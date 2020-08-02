#Refactor for Horiseon landing page, 07-2020
[]()

##Table of Contents:
1. HTML
2. CSS 

##HTML
*added various internal notation for clarity and ease of review, matching CSS notations when appropriate
*added missing selector ID "search-engine-optimization" to appropriate <div> so that header navigation links correctly
*changed body>div>h1>div to body>header>h1>nav
*eliminated class=header as this was no longer necessary for functionality
*changed primary <div>s for Stacked Content and Benefits Column to <section> tags
*


##CSS
*added various internal notation for clarity and ease of review, matching HTML notations when appropriate
*re-ordered styles to group related elements without impacting funtionality of CSS. Maintained separation for Content divs so future edits won't require extra work.
*adjusted paths for selector in accordance with HTML change(body>div>h1>div to body>header>h1>nav)Reference:[changed body>div>h1>div to body>header>h1>nav]
*
