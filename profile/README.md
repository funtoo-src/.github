# .github
```
~ # echo 'sync_base_url=https://github.com/funtoo-repo/{repo}' >> /etc/ego.conf
~ # echo 'GENTOO_MIRRORS=https://direct-github.funmore.org' >> /etc/portage/make.conf
~ # rm -rf /var/git/meta-repo
~ # ego sync && emerge -DuavNA --keep-going @world && emerge --depclean
``` 
