# sudweb.fr dotfiles

These files control how the website is configured over the Web.

These are the current Apache *Virtual host directives*:

```
DocumentRoot /home/sudweb/www

Include /home/sudweb/dotfiles/apache.conf
Include /home/sudweb/dotfiles/apache-sudweb.conf
Include /home/sudweb/dotfiles/apache-proxies.conf
```

You can control them by submitting a *pull request*:

1. [apache.conf](apache.conf)
2. [apache-sudweb.conf](apache-sudweb.conf)
3. [apache-proxies.conf](apache-proxies.conf)

# Hosting

Hosting is generously provided by [Alwaysdata](https://alwaysdata.com).
