# Anime Fileshare
## Self hosting this
It's pretty easy! This is a static website with no backend necessary.
Here are steps to self-host this thing:
- Put a test.txt file into the files directory
- Serve the top level directory
- go to {your domain or localhost}/?test.txt

Hopefully you won't see a 404 page. If test.txt is empty, you should see an empty page. Put something inside test.txt and you'll see it on the page!

I use Caddy to serve this site, but you can *probably* use other stuff like Nginx or Apache or Serve.

(Just opening index.html via a browser displays the page, but the file is not there. I guess it's a filesystem thing that I can't be bothered to fix)

## More of my stuff at https://liz.sex