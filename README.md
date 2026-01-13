# apa7.bst
I usually use Overleaf to write my papers in LaTex with pdfLaTex as compiler. 
Most conferences and departments I have to work with require the bibliography to follow APA7 rules. 
This was frustrating, as base Overleaf does not offer APA7 style, even with `natbib`, 
and the closest I could get was using `apalike` with an author-year citation scheme. 
So of course I downloaded `apalike.bst` and edited it to follow current APA style rules.

Changes include
- DOIs are included in the bibliography as an URL starting with "https://doi.org/". The `hyperref` package can be used to make them clickable. 
- Lists of authors use '&' instead of 'and'.
- Volume and pages are separated with ','  instead of ':'.


Please let me know if you find any issues or things I missed. 
