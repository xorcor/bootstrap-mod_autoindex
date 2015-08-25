# bootstrap-mod_autoindex
Uses Bootstap CSS with Apache mod_autoindex, for cleaner directory listing

drop this htaccess into folder where the fancy directory listings should occur<br>
HeaderName /path_to/header.html<br>
ReadmeName /path_to/footer.html<br>
IndexOptions +SuppressHTMLPreamble -FancyIndexing<br>
IndexIgnore .htaccess /path_to<br>
that is all<br>
