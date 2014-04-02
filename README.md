PSU-GEOSC-thesis-template
=========================

This is the repository for a TeX template specific to theses out of the Geosciences Department at Penn State. It is based on the work of other grad students in other departments across nearly two decades of academia. I have just polished the hubcaps. 



----------------------



Welcome to the newly-updated TeX template for Geosciences theses. In this folder, you'll find a minimum working example (thesis_template.tex) and its output (thesis_template.pdf). This template is  currently in the two-sided configuration appropriate for books (psuthesis2side). For more general purpose thesis work, you'll need to change the \documentclass[11pt]{psuthesis2side} to \documentclass[11pt]{psuthesis} and recompile. 

The included *.sty files (doublespace, etoolbox) are necessary for formatting (in the first case) and the toggle between Masters and Doctorate degrees (the latter). I have put the Masters thesis template through format review, so it should be good to go. 

To toggle between degrees (not so easy in real life): comment and uncomment the relevant \toggletrue and \togglefalse, just beneath \major and \dept declarations. It will handle the relevant wording (on two pages) and whether to display the Vita (optional with the Masters -- you'll have to go in and change it if you want it to show up in a Masters). 

The signature page is omitted, but is up on the Dept. of Graduate Studies web page. 
