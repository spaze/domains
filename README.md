# Domains
Unofficial and incomplete lists of various domain names, for research purposes only.

## Sources
- [Initial set](https://blog.root.cz/oskar/jak-vylistovat-domenu-cz/866150/) by Ondřej Caletka
- Few updates by [Patrik Votoček](https://github.com/Vrtak-CZ)
- [Majestic Million](https://blog.majestic.com/development/majestic-million-csv-daily/)
- [Alexa Top 1M](http://s3.amazonaws.com/alexa-static/top-1m.csv.zip)
- [regZone.cz](https://www.regzone.cz/uvolnovane-domeny/)
- [HSTS preloaded list](https://cs.chromium.org/chromium/src/net/http/transport_security_state_static.json)
- [scans.io dataset](https://gist.github.com/roycewilliams/b87a140a4869baf4d2c907c6e352b970) by [@roycewilliams](https://github.com/roycewilliams)
- [Expired domains archive](http://wladass.cz/archiv-expirovanych-domen/) from [Monitoruju.net](https://www.monitoruju.net/expirovane-domeny-archiv/)
- [Nette Framework-powered](https://gist.github.com/Myiyk/7589213) list by [@Myiyk](https://github.com/Myiyk)
- [Certificate Transparency](https://www.certificate-transparency.org/) logs
- [A list](http://www.vitezslav-lindovsky.cz/czech_domains.txt) by [Vítězslav Lindovský](https://github.com/vitezslav-lindovsky), and another one of [domains with pages that contain a substring, "drupal"](http://www.vitezslav-lindovsky.cz/czech_domains_on_drupal.txt)

Thanks!

## Want to contribute?
Have a list of domains you'd like to add? Feel free to create a pull request!

Here's a short how-to:
1. Only 2nd-level domains *foo.tld*, no *bar.foo.tld* (lines should match `^[a-z0-9-]+\.tld$`)
2. Use LF newlines, not CRLF
3. Generate a new list, for example with `cat tld-cz.txt yourlist.txt | sort | uniq > tld-cz-new.txt`
4. Review `tld-cz-new.txt`, rename to `tld-cz.txt`, pull request it

Thank you!
