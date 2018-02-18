# jekyll-bootstrap-sass-sample
A sample Jekyll site for showing how to combine bootstrap sass and Jekyll to accompany [my blog post]().

# Details
The [`styles/site.scss`](https://github.com/david-chambers/jekyll-bootstrap-sass-sample/blob/master/styles/site.scss) file kicks everything off since it contains a [YAML Front Matter Block](https://jekyllrb.com/docs/frontmatter/)
```sass
--- 
---  
/*Imports base variables, the bootstrap framework, and custom css
  and builds the output in _site/styles/site.css*/
@import "base";
@import "bootstrap";
@import "layout";
```

The imported files above can be found in the sites [Sass Directory](https://github.com/david-chambers/jekyll-bootstrap-sass-sample/tree/post2-overridingBootstrapSass/_sass).