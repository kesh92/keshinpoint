# SmartLoad's Marketing Website

This is the GitHub project that maintains the SmartLoad marketing website. The website is built off of GitHub pages, which uses [Jekyll](https://jekyllrb.com/) to build static content. This website is maintained by [kesh92](https://github.com/kesh92) of [SmartBear Software](https://smartbear.com). The website takes its content from the `gh-pages` branch.

This Jekyll project is simply a directory of files, the source code for building a web site. A few directories have specialized uses for Jekyll and are denoted with an `_` underscore beginning the name.

- `example-site`: The Jekyll project is a Git repository. The top level contains configurations and files that will become root level pages in your site. Edit the overall site settings in `_config.yml`. Changes to `_config.yml` are not automatically refreshed during jekyll serve, you have to stop the server and restart.

- `_layouts`: The basic templates for complete web pages, generally constructed with Liquid includes. They are called by YAML front matter on each page or post.

- `_includes`: Modular chunks of HTML that can be called into a page layout by Liquid. For example {% include head.html %} in a page layout would add the include head.html from the `_includes` directory. This folder also contains this website's top level navigation headers which house the sign in and sign up button, and associated links.

- `_posts`: Files in this directory will become blog post-like objects. They always have a date and title in the file name. If your site isn’t a blog, you don’t have to add a `_posts` directory. Other directories can be designated Collections to create regular groups of pages with properties similar to Posts. An example name of the `md` file for a blog post is `2017-04-18-first-post.md`, with `-` acting as a way to add spaces.

- `_sass`: Contains the modular `.scss` partials that will be pulled into your main CSS for the site.

- `assets`, `css`, `images`: Directories without an underscore are copied to the generated site. One should contain a base SCSS file used to compile the partials into the site’s CSS file. Any file with no YAML front matter will also be simply copied without processing, for example images or java script libraries.

- `_site`: This is the built out version of your new static site. **Never modify files in this directory. It will be completely deleted and rebuilt with each jekyll serve or jekyll build. If you want to deploy your site to a static web host, copy this directory to your server!**

## Running Locally
You can run this website locally. Prerequisites include [Ruby](https://www.ruby-lang.org/en/documentation/installation/) and [Jekyll](https://jekyllrb.com/docs/installation/).

- Clone this repository into tour local machine.
- `cd` into the root of the cloned repo
- run `bundle install`

To run the local build, just enter this command in your terminal
```
bundle exec jekyll serve
```

Preview your local Jekyll site in the localhost, detailed in your terminal after running the above command. See the official [GitHub documentation](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/) for doing this.


## Working with the content
Anyone is welcome to add changes to the content. To make changes, please do the following -

- Clone repository
- Create a new branch, and add your changes to that branch
- Create a PR to the main `gh-pages` branch

Any new commits to the `gh-pages` branch will automatically be picked up by GitHub pages, and new content should be reflected in the main marketing website in under 10 minutes. 
