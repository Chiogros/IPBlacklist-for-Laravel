# Laravel - IPBlacklist Middleware

A very simple IP blacklist middleware for Laravel. It redirects user on 403 page if he's not allowed.

- Put it in app/Http/Middleware
- Enable middleware by adding it in app/Http/Kernel.php
- Add IPs to block in the private array $blockedIPs
```
private $blockedIPs = ["XXX.YYY.ZZZ.WWW", "..."];
```
