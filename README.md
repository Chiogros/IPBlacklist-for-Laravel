# Laravel - IPBlacklist Middleware

A very simple IP blacklist middleware for Laravel.

- Put it in app/Http/Middleware
- Enable middleware by adding it in app/Http/Kernel.php
- Add IPs to block in the private array $blockedIPs
```
private $blockedIPs = ["XXX.YYY.ZZZ.WWW", "..."];
```
