# Harmony

Harmony is a responsive jekyll theme. 

- Built for jekyll 2.x
- Supports Google analytics and RSS feeds
- Sass based styles
- Browser support: IE 8+, Chrome, Safari and Firefox 
- Fluidly responsive 

## Contents

- [Harmony](#harmony)
- [About Jekyll](#about-jekyll)
- [How to install/run](#how-to-installrun)
- [Options/Usage](#optionsusage)
  - [Header navigation links](#header-navigation-links)
  - [Footer links](#footer-links)
  - [Copyrights/Disclaimer statements](#copyrightsdisclaimer-statements)
- [Screenshots](#screenshots)
- [Feedback/Bugs/Suggestions](#feedbackbugssuggestions)
- [Version history](#version-history)
- [License](#license)

## About jekyll 

[Jekyll](http://jekyllrb.com/) is a static site generator, an open-source tool for creating simple yet powerful websites of all shapes and sizes.

## How to install/run

1. [Fork](https://github.com/web-create/harmony/fork) this repository.
2. Clone it: git clone https://github.com/YOUR-USERNAME/harmony.
3. If you're completely new to jekyll, please read more about [Jekyll](http://jekyllrb.com/) and [Github pages](https://help.github.com/articles/using-jekyll-with-pages).
4. Change your directory into cloned repository. 
5. Run `bundle install`
6. Edit the _config.yml on root directory. Change `url` property to to 
`http://127.0.0.1:4000` since you are going to run on localhost.
7. Run the jekyll server by having: `jekyll serve --baseurl ''` or `rake preview`   

Point your browser to [http://localhost:4000](http://localhost:4000).

Note: If you are a windows user please refer to this nice website - http://jekyll-windows.juthilo.com/ by Julian Thilo to configure ruby + jekyll on windows.

## Options/Usage

Harmony has some customizable options. All the configuration details are 
configured in `_config.yml` file under root of the harmony directory. 

Feel free to change your `name`, `descriptionn`, `meta_description`, `author details`,
`social media names` and `Google analytics id` accordingly. 


### Includes 

All the partial includes are under `_includes` directory.

#### Header navigation links

Add/edit links for your header in the file `header-links.html`.

#### Footer links

Customize your footer links by editing `_includes/footer-links.html`

#### Copyrights/Disclaimer statements

All copyright notes are under `_includes/footer.html`. Also note that you 
can toggle on/off copyright notes from the front-end by setting up `show_disclaimer` 
property in `_config.yml`. 

Version history
---------------

| Version no. | Description  | Date |
| --- | --- | --- |
| 1.0 | Initial release | 9th September 2014 |
| 1.0.1 | v1.0.1 with minor bug fix | 9th September 2014 |
| 1.0.2 | v1.0.2 Optimize for Google | 24th October 2014 |


## License

Free / Open sourced under the 
[MIT](https://github.com/web-create/harmony/blob/master/LICENSE.md).
