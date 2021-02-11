## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/bhaut/hello-repository/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/bhaut/hello-repository/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
*{
  box-sizing: border-box;
}

h1{
  text-align: center;
}

p {
  background-color: #bfbfbf;
  border: 2px solid black;
  height: 150px;
  margin-right: 10px;
  padding: 40px 10px 5px 10px;
  overflow: hidden;
}


#container {
  position: relative;
  
}

#p1 {
  background-color: #D59898;
  position: absolute;
  top: 0;
  right: 0;
  font-weight: bold;
  height: 35px;
  width: 120px;
  padding: 10px;
  text-align: center;
  font-family: Arial, Helvetica, sans-serif;

}
#p2 {
  background-color:#C14543 ;
  color: white;
  position: absolute;
  top: 0;
  right: 0;
  font-weight: bold;
  height: 35px;
  width: 120px;
  padding: 10px;
  text-align: center;
  font-family: Arial, Helvetica, sans-serif;

}
#p3 {
 background-color: #E5D198;
  position: absolute;
  top: 0;
  right: 0;
  font-weight: bold;
  height: 35px;
  width: 120px;
  padding: 10px;
  text-align: center;
  font-family: Arial, Helvetica, sans-serif;

}


.row {
  width: 100%;

}


/********** Large devices only **********/
@media (min-width: 992px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
  }
  .col-lg-1 {
    width: 8.33%;
  }
  .col-lg-2 {
    width: 16.66%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-4 {
    width: 33.33%;
  
  }
  .col-lg-5 {
    width: 41.66%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-7 {
    width: 58.33%;
  }
  .col-lg-8 {
    width: 66.66%;
  }
  .col-lg-9 {
    width: 74.99%;
  }
  .col-lg-10 {
    width: 83.33%;
  }
  .col-lg-11 {
    width: 91.66%;
  }
  .col-lg-12 {
    width: 100%;
  }

  
}

/********** Medium devices only **********/
@media (min-width: 768px) and (max-width: 991px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
   
  }
  .col-md-1 {
    width: 8.33%;
  }
  .col-md-2 {
    width: 16.66%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-4 {
    width: 33.33%;
  }
  .col-md-5 {
    width: 41.66%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-7 {
    width: 58.33%;
  }
  .col-md-8 {
    width: 66.66%;
  }
  .col-md-9 {
    width: 74.99%;
  }
  .col-md-10 {
    width: 83.33%;
  }
  .col-md-11 {
    width: 91.66%;
  }
  .col-md-12 {
    width: 100%;
  }
}

/********** Mobile only **********/
@media (max-width: 767px) {
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
    float: left;
  }
  .col-sm-1 {
    width: 8.33%;
  }
  .col-sm-2 {
    width: 16.66%;
  }
  .col-sm-3 {
    width: 25%;
  }
  .col-sm-4 {
    width: 33.33%;
  
  }
  .col-sm-5 {
    width: 41.66%;
  }
  .col-sm-6 {
    width: 50%;
  }
  .col-sm-7 {
    width: 58.33%;
  }
  .col-sm-8 {
    width: 66.66%;
  }
  .col-sm-9 {
    width: 74.99%;
  }
  .col-sm-10 {
    width: 83.33%;
  }
  .col-sm-11 {
    width: 91.66%;
  }
  .col-sm-12 {
    width: 100%;
  }

  
}
ol-sm-8 {
    width: 66.66%;
  }
  .col-sm-9 {
    width: 74.99%;
  }
  .col-sm-10 {
    width: 83.33%;
  }
  .col-sm-11 {
    width: 91.66%;
  }
  .col-sm-12 {
    width: 100%;
  }

  
}
