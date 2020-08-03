#Refactor for Horiseon landing page, 07-2020

[Deployed URL][https://ospreyvelt.github.io/Horiseon/]

##Table of Contents:

HTML
CSS
##HTML

*added various internal notation for clarity and ease of review, matching CSS notations when appropriate *added missing selector ID "search-engine-optimization" to appropriate

so that header navigation links correctly *changed body>div>h1>div to body>header>h1>nav *eliminated class=header as this was no longer necessary for functionality *
##CSS

*added various internal notation for clarity and ease of review, matching HTML notations when appropriate *re-ordered styles to group related elements without impacting funtionality of CSS. Maintained separation for Content divs so future edits won't require extra work. *adjusted paths for selector in accordance with HTML change(body>div>h1>div to body>header>h1>nav)Reference:[changed body>div>h1>div to body>header>h1>nav] *