Fire & Ice Glass 2019
=====================

## Get started with Bundler

```bash
$ bundle install
```

## Serve the site locally

Includes a site HTML compile and SASS compile. Use the `incremental` flag to build 
only the assets that have changed. The `JEKYLL_ENV` variable is assumed to be 
"development" when omitted. 

```bash
$ jekyll serve --I
```

In a browser, open [http://127.0.0.1:4050/](http://127.0.0.1:4050/)

### Additional Flags

+ `--drafts` to publish/preview drafts
+ `--future` to publish/preview posts with a future date
+ `--unpublished` to publish/preview posts marked with unpublished


## Build the Site for Production

Specify the production environment to omit content intended for development only. 
Optionally, add the future flag to publish posts that have a future timestamp. 

```bash
$ JEKYLL_ENV=production jekyll build --future
```


## Categories

Categories are created by adding a file to the /category/ folder with Front Matter content. 
It is important that the Front Matter “category:” name matches the way posts use that Category. 
Capitalization is important! 


## Resources

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of 
Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you 
have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/