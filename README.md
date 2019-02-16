## Caddy Webserver Custom Source Built Binaries

Source compile built Caddy 64bit binaries on CentOS 7.4 64bit system for [Centmin Mod LEMP stack](https://centminmod.com/) integration.

* source/bin/0.10.9/gcc4.8.5/caddy.zip - Caddy binary built using system GCC 4.8.5 compiler
* source/bin/0.10.9/gcc7.1.1/caddy.zip - Caddy binary built using GCC 7.1.1 compiler
* source/bin/0.10.9/clang4.0.1/caddy.zip - Caddy binary built using Clang 4.0.1 compiler
* source/bin/0.10.10/gcc4.8.5/caddy.zip - Caddy binary built using system GCC 4.8.5 compiler
* source/bin/0.10.10/gcc7.2.1/caddy-gcc7.zip - Caddy binary built using GCC 7.2.1 compiler
* source/bin/0.10.10/clang4.0.1/caddy-clang4.zip - Caddy binary built using Clang 4.0.1 compiler
* source/bin/0.10.11/gcc4.8.5/caddy.zip - Caddy binary built using system GCC 4.8.5 compiler
* source/bin/0.10.11/gcc7.2.1/caddy-gcc7.zip - Caddy binary built using GCC 7.2.1 compiler
* source/bin/0.10.11/gcc8.0.1/caddy-gcc8.zip - Caddy binary built using GCC 8.0.1 Feb 18th, 2018 built compiler
* source/bin/0.10.11/clang4.0.1/caddy-clang4.zip - Caddy binary built using Clang 4.0.1 compiler
* source/bin/0.10.11/gcc4.8.5-nofilebrowser/caddy.zip - Caddy binary built using system GCC 4.8.5 compiler. Without filemanager, hugo, jekyll plugins.
* source/bin/0.10.11/gcc7.2.1-nofilebrowser/caddy-gcc7.zip - Caddy binary built using GCC 7.2.1 compiler. Without filemanager, hugo, jekyll plugins.
* source/bin/0.10.11/gcc8.0.1-nofilebrowser/caddy-gcc8.zip - Caddy binary built using GCC 8.0.1 Feb 18th, 2018 built compiler. Without filemanager, hugo, jekyll plugins.
* source/bin/0.10.11/clang4.0.1-nofilebrowser/caddy-clang4.zip - Caddy binary built using Clang 4.0.1 compiler. Without filemanager, hugo, jekyll plugins.
* source/bin/0.11.3/clang5.0.1/caddy-clang5.zip - Caddy binary built using Clang 5.0.1 compiler. Without deprecated hugo, jekyll plugins and filemanager
* source/bin/0.11.3/gcc4.8.5/caddy.zip - Caddy binary built using system GCC 4.8.5 compiler. Without deprecated hugo, jekyll plugins and filemanager
* source/bin/0.11.3/gcc7.3.1/caddy-gcc7.zip - Caddy binary built using GCC 7.3.1 compiler. Without deprecated hugo, jekyll plugins and filemanager
* source/bin/0.11.4/clang5.0.1/caddy-clang5.zip - Caddy binary built using Clang 5.0.1 compiler. Without deprecated hugo, jekyll plugins and filemanager. Add geoip & s3browser plugins.
* source/bin/0.11.4/gcc4.8.5/caddy.zip - Caddy binary built using system GCC 4.8.5 compiler. Without deprecated hugo, jekyll plugins and filemanager. Add geoip & s3browser plugins.
* source/bin/0.11.4/gcc7.3.1/caddy-gcc7.zip - Caddy binary built using GCC 7.3.1 compiler. Without deprecated hugo, jekyll plugins and filemanager. Add geoip & s3browser plugins.

## Benchmarks

* [Caddy HTTP/2 server & benchmarks - Part 2](https://community.centminmod.com/threads/caddy-http-2-server-benchmarks-part-2.12873/)

## Caddy Plugins

```
/usr/local/bin/caddy -version
Caddy 0.11.4 (+33b00dc Sat Feb 16 15:44:48 UTC 2019) (unofficial)
1 file changed, 46 insertions(+), 1 deletion(-)
caddy/caddymain/run.go
```

```
/usr/local/bin/caddy -plugins/usr/local/bin/caddy -plugins
Server types:
  http

Caddyfile loaders:
  short
  flag
  default

Other plugins:
  http.authz
  http.awses
  http.awslambda
  http.basicauth
  http.bind
  http.browse
  http.cache
  http.cgi
  http.cors
  http.datadog
  http.errors
  http.expires
  http.expvar
  http.ext
  http.fastcgi
  http.filter
  http.forwardproxy
  http.geoip
  http.git
  http.gopkg
  http.grpc
  http.gzip
  http.header
  http.index
  http.internal
  http.ipfilter
  http.jwt
  http.limits
  http.locale
  http.log
  http.login
  http.mailout
  http.markdown
  http.mime
  http.minify
  http.nobots
  http.pprof
  http.prometheus
  http.proxy
  http.proxyprotocol
  http.push
  http.ratelimit
  http.realip
  http.reauth
  http.redir
  http.request_id
  http.restic
  http.rewrite
  http.root
  http.s3browser
  http.secrets
  http.status
  http.templates
  http.timeouts
  http.upload
  http.webdav
  http.websocket
  on
  tls
  tls.cluster.file
  tls.dns.azure
  tls.dns.cloudflare
  tls.dns.digitalocean
  tls.dns.dnsmadeeasy
  tls.dns.dyn
  tls.dns.godaddy
  tls.dns.googlecloud
  tls.dns.linode
  tls.dns.namecheap
  tls.dns.ns1
  tls.dns.ovh
  tls.dns.powerdns
  tls.dns.rackspace
  tls.dns.route53
  tls.dns.vultr
```