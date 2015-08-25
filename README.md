# bootstrap-mod_autoindex
Uses Bootstap CSS with Apache mod_autoindex, for cleaner directory listing

drop this htaccess into folder where the fancy directory listings should occur
HeaderName /path_to/header.html
ReadmeName /path_to/footer.html
IndexOptions +SuppressHTMLPreamble -FancyIndexing
IndexIgnore .htaccess /path_to
that is all
