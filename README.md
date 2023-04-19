# Proyecto-ATUX-Srl.

<VirtualHost *:80>
    ServerAdmin choque.franky@gmail.com
    DocumentRoot "F:/Atux Srl/atux-pf/public/"
    ServerName	dev.atux.com.bo
	<Directory "F:/Atux Srl/atux-pf/public/">
		Options Indexes FollowSymLinks MultiViews
        AllowOverride all
        Order Deny,Allow
        Allow from all
        Require all granted
	</Directory>
</VirtualHost>
