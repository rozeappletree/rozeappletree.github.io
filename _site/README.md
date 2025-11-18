dongyado's blog
=====

visit with : http://dongyadoit.com

### 
- notes of development
- some thoughts.

### 
- Based on jekyll and github pages.

If you like the theme of this blog, just use it.

### Running locally

This blog is built with Jekyll. To run it locally:

1.  Install [Ruby](https://www.ruby-lang.org/en/documentation/installation/)  `sudo apt-get install ruby-full ` and then [Bundler](https://bundler.io/) `gem install bundler`.
2.  Clone the repository.
3.  Navigate to the project directory and install the dependencies:
    ```bash
    bundle install
    ```
4.  Serve the website locally:
    ```bash
    bundle exec jekyll serve
    ```
5.  Open your browser and go to `http://127.0.0.1:4000`.


---

credits: https://github.com/dongyado/dongyado.github.io

## Setup Disqus

- Goto disqus.com and "Install on site", redirects to https://disqus.com/admin/create/

- "Website name" will be your `site.disqus` config value. 

    > Note that if name is already taken, some suffix will be added. Eg. `blog-template` became `blog-template-3` in our case. The entire link is https://blog-template-3.disqus.com/admin/ which is used in [disqus.html](_includes/disqus.html)