# Deploy updated site on github

    git push

# Deploy updated site (on kth):

  /home/g/o/gocht/.gem/ruby/2.3.0/gems/jekyll-3.5.2/exe/jekyll b -d ~/public_html/

# Update References:

JabRef
 * sort by year
 * export html (list)

Remove html, head, body tags, make sure abstract does not contain empty line (jabref will
create <p> without closing tag, which jekyll doesn't like.
replace html file (_includes/publications.html) and update site
