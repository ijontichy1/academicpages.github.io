---
permalink: /
title: "אוריינות דיגיטלית"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

בדוח שפרסם איגוד הספריות האמריקאי (ALA: **A**merican **L**ibrary **A**ssosication) בשנת 2013 מוגדרת אוריינות דיגיטלית כ"יכולת להשתמש בטכנולוגיות מידע ותקשורת על מנת לאתר, להבין, להעריך, ליצור ולהעביר מידע דיגיטלי, יכולת אשר דורשת הן כישורים טכניים והן כישורים קוגניטיביים". מהפכת המידע של העשורים האחרונים הפכה את הסביבה הדיגיטלית לאינהרנטית לעולם, ורבים מהבאים בשערי האוניברסיטה מקבלים אותה כמובנת מאליה. הדבר מוביל לעמעום כישורי החשיבה הביקורתית בכל הנוגע למידע שמקורו בסביבה הדיגיטלית, ופוגם ביכולת האינדיבידואלית לקבל החלטות מושכלות על סמך מידע זה. לדידה של חוקרת התקשורת רנה הובס (Hobbs), כישורי חשיבה ביקורתית בכל הנוגע לתקשורת המונים, תרבות פופולרית או מדיה דיגיטלית אינם מושגים באמצעות שימוש בטכנולוגיה עצמה; במקום לראות את הסביבה הדיגיטלית כמקור מידע ניטרלי, על התלמידים לתהות על אודות המקורות לאותו מידע, האינטרסים של מחבריו ומפיציו ובאיזה אופן הוא מייצג את המציאות. 

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables 
