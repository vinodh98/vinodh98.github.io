## Notes
 - Use the jekyll/jekyll container image to build our webpages
 ```bash
 docker pull jekyll/jekyll
 ```
 - Example build command
 ```bash
docker run --rm --label=jekyll --volume=<HOME>/Dropbox/Development/GitHub/vinodh98.github.io/src/myblog:/srv/jekyll --volume=<HOME>/Dropbox/Development/GitHub/vinodh98.github.io:/srv/jekyll/_site -it -p 4000:4000 jekyll/jekyll jekyll build
 ```
