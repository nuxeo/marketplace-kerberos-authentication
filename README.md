marketplace-kerberos-authentication
===================================

Nuxeo Marketplace packages for the kerberos authentication plugin. Please read the [documentation](http://doc.nuxeo.com/x/QxDF) carefuly.

After installing the package, you need to stop the server. Restart won't cut it as we need to change the JAVA_OPTS.
Don't forget to edit the java.login.config file to set the path to your exported keytab and the principal.

