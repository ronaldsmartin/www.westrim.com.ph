# ![WestRim Logo](https://raw.githubusercontent.com/ronaldsmartin/www.westrim.com.ph/master/static/favicon-32x32.png) WestRim Marketing Site

Responsive site redesign for WestRim, Inc., built with [Hugo](https://gohugo.io) and based off digitalcraftsman's [Creative Theme](https://github.com/digitalcraftsman/hugo-creative-theme).

See the finished product here: www.westrim.com.ph

#### From this...

![Old Site Screenshot](https://github.com/ronaldsmartin/www.westrim.com.ph/raw/old-site/screenshots/00-home.png)

#### To this!

![New Site Screenshot](https://github.com/ronaldsmartin/www.westrim.com.ph/raw/old-site/screenshots/v2.0.png)

## Building

### Install Hugo

[Please see the Hugo docs.](https://gohugo.io/overview/installing/)

### Download a copy

  ```
  $ git clone --recursive https://github.com/ronaldsmartin/www.westrim.com.ph.git
  ```

  The `--recursive` flag is used in order to pull down the Creative theme submodule.
  
### Run locally

  ```
  $ cd www.westrim.com.ph/
  $ hugo server
  ```

The site will be available by visiting [`localhost:1313`](http://localhost:1313) in your browser.


## Deploying

Use the `hugo` command in the root directory to generate the new site. Make sure you delete any residue from previous build processes first.

Then, copy the generated files in the `public/` directory to the server.
