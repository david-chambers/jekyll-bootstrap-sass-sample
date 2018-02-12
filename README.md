# jekyll-bootstrap-sass-sample
A sample Jekyll site for showing how to combine bootstrap sass and Jekyll to accompany [my blog post](https://davidjchambers.com/2017/12/27/site-setup.html).

# Details
The [`styles/site.scss`](https://github.com/david-chambers/jekyll-bootstrap-sass-sample/blob/master/styles/site.scss) file kicks everything off since it contains a [YAML Front Matter Block](https://jekyllrb.com/docs/frontmatter/)
```sass
--- 
--- 
/*Import the bootstrap framework and builds the output in _site/styles/site.css*/
@import "bootstrap";
```

The "bootstrap" file that it is importing can be found in the sites [Sass Directory](https://github.com/david-chambers/jekyll-bootstrap-sass-sample/blob/master/_sass/_bootstrap.scss).
