
# VestaCP Nginx Force SSL
This is a couple of template files for VestaCP Nginx Only installs that allows you to force SSL by default. Simply download and extract the 4 files, then place them into `/usr/local/vesta/data/templates/web/nginx`.

If you are adding this to an existing domain you'll need to select the template and then run Rebuild Web for the user via the GUI or run `v-rebuild-web-domains` for each user, there is also a little bash script available [here](https://forum.vestacp.com/viewtopic.php?f=10&t=16188#p67137) credit to plutocrat. Otherwise just apply the correct template when adding the domain.

![enter image description here](https://i.imgur.com/kZpkVOk.png)

I've included 2 versions to force ssl, the force-ssl-www enforces the www where the ssl-no-www omits it completely.

- [x] Tested on CentOS 7 VestaCP 0.9.8
