Para instalar el sistema (más o menos)
======================================
<blockquote>
$ curl -O https://raw.githubusercontent.com/wp-cli/builds/gh-pages/phar/wp-cli.phar
$ mv wp-cli.phar wp
$ chmod 755 wp
$ ./wp core download
$ ./wp core config --dbname=ahoramadrid  --dbpass=lalala --dbuser=root
$ ./wp core install --url=http://localhost/dev/ahoramadrid-wp --title=AhoraMadrid --admin_user=admin --admin_password=foo --admin_email=foo@bar.com
$ ./wp core language install es_ES
$ ./wp core language activate es_ES
$ ./wp plugin install jetpack html-editor-syntax-highlighter mass-pagesposts-creator user-control --activate
$ ./wp plugin install ~/Downloads/ahora_madrid/bloom.zip ~/Downloads/ahora_madrid/divi-builder.zip ~/Downloads/ahora_madrid/et-shortcodes.zip ~/Downloads/ahora_madrid/elegantbuilder.zip ~/Downloads/ahora_madrid/handheld.zip ~/Downloads/ahora_madrid/monarch.zip --activate
$ ./wp theme install ~/Downloads/ahora_madrid/Divi.zip
$ ./wp theme activate AM_theme
<blockquote>
