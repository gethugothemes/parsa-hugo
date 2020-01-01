# Easy Setup (Hugo + Netlify + Forestry)
Build your website with kross hugo theme by following this easy steps (No Coding Required)

<a href="http://bit.ly/meghna-hugo-installation" target="_blank" title="meghna hugo installation" rel="nofollow"><img width="100%" src="https://user-images.githubusercontent.com/37659754/70844354-4028be00-1e6a-11ea-8d84-02e9a25e7db8.png"></a>

In this tutorial we will show you to make your website live without buying any hosting and touching a single line of code. We made this tutorial based on [meghna hugo](https://github.com/themefisher/meghna-hugo) but you can setup everithing like this.

### What you need !!

1. Git acccount (Ex: Github, Gitlab etc ) . In our case we use github.
2. [Netlify](https://bit.ly/netlify-account) account to host files and add custom domain .
3. [Forestry](https://bit.ly/forestry-account) account to maintain whole project without code.


### Step 1 : Fork or Clone repository

First we will fork this [parsa hugo](https://github.com/themefisher/parsa-hugo) template.

### Step 2 : Add your repository in Forestry

Go to your [forestry](https://bit.ly/forestry-account)  account and click on `import your site now`. declare your config.toml file [`exampleSite`] and fill up basic settings . Mark everything is done then go to configuration to change the base url . You can put any url but this have to similar as netlify . So for now put a name which you are going to put in netlify as netlify subdomain.

### Step 3 : Setup and host website with Netlify

Here comes the last step . Go to your [netlify](https://bit.ly/netlify-account) account and click add new site . Choose your git repository to import your website in netlify .  And now you can see the forked `parsa hugo` theme. select it and follow the steps. Then go to `site settings` for change the site name and put your subdoamin name here what you puted on forestry as base url. save it and go to `deploy` from top menu, Wait a while and click on `site preview` or just simply go to the subdomain you puted as base url. **BOOM! Your site is live.** Now you can go to forestry and add, remove or customize every setting and content.

> If you face any issue regarding the installation feel free to onen [open a new issue](https://github.com/themefisher/parsa-hugo/issues)


## Table of Contents

- [Demo](#demo)
- [Installation](#installation)
- [Reporting Issues](#reporting-issues)
- [Technical Support or Questions](#technical-support-or-questions)
- [Licensing](#licensing)
- [More Hugo Themes](https://themefisher.com/hugo-themes/)


## Demo

| ![](https://user-images.githubusercontent.com/37659754/58609653-2c50ac80-82ca-11e9-9f42-887141a0f6dd.png) | ![](https://user-images.githubusercontent.com/37659754/58609715-7043b180-82ca-11e9-9225-dfc9d255f516.png) | ![](https://user-images.githubusercontent.com/37659754/58609747-894c6280-82ca-11e9-9253-d1256af4aad9.png) | ![](https://user-images.githubusercontent.com/37659754/58609762-9cf7c900-82ca-11e9-9956-53e6a3b65636.png) | ![](https://user-images.githubusercontent.com/37659754/58609777-ac771200-82ca-11e9-9814-9e1fc7404b91.png) |
|---|---|---|---|---|
| Homepage  | Homepage 2  | Single  | About  | Contact  |


**The images are only for demonstration purpose, Please don't use those images.**

[Live Preview](http://demo.themefisher.com/parsa-hugo/).


## Installation
At the top we have shown an easy hugo installation. but still if you think you want to go with the traditional way then use the following commands:

```
$ git clone git@github.com:themefisher/parsa-hugo.git
$ cd parsa-hugo/exampleSite/
$ hugo server --themesDir ../..
```

## Reporting Issues

We use GitHub Issues as the official bug tracker for the **Parsa Theme**. Please Search [existing issues](https://github.com/themefisher/parsa-hugo/issues). It’s possible someone has already reported the same problem.
If your problem or idea is not addressed yet, [open a new issue](https://github.com/themefisher/parsa-hugo/issues/new)

## Technical Support or Questions

If you have questions or need help integrating the product please [contact us](mailto:themefisher@gmail.com) instead of opening an issue.

## Licensing

- Copyright 2019 Themefisher (https://themefisher.com/)
- Licensed under MIT (https://github.com/themefisher/parsa-hugo/blob/master/LICENSE)

## Premium Themes

| [![Mega-Bundle-HUGO](https://gethugothemes.com/wp-content/uploads/edd/2019/09/Mega-Bundle-HUGO.png)](https://themefisher.com/products/hugo-mega-bundle/) | [![revolve](https://gethugothemes.com/wp-content/uploads/edd/2019/11/revolve.jpg)](https://gethugothemes.com/products/revolve-hugo/) | [![Liva](https://gethugothemes.com/wp-content/uploads/edd/2019/11/liva.png)](https://gethugothemes.com/products/liva-hugo/) |
|:---:|:---:|:---:|
| **Hugo Mega Bundle**  | **Revolve**  | **Liva**  |
| [![northendlab](https://gethugothemes.com/wp-content/uploads/2019/11/Blogplate-Blog-Template.png)](https://gethugothemes.com/products/northendlab/) | [![Influencer](https://gethugothemes.com/wp-content/uploads/2019/11/Influencer.png)](https://gethugothemes.com/products/influencer-hugo/) | [![Kross](https://gethugothemes.com/wp-content/uploads/edd/2019/07/kross-portfolio-template.jpg)](https://gethugothemes.com/products/kross-hugo-theme/) |
| **Northendlab** | **Influencer** | **Kross** |
| [![Biztrox](https://gethugothemes.com/wp-content/uploads/2019/12/Biztrox.png)](https://gethugothemes.com/products/hugo-business-theme/) | [![Phantom](https://gethugothemes.com/wp-content/uploads/edd/2019/06/Phantom.jpg)](https://gethugothemes.com/products/phantom-hugo-theme/) | [![all](https://gethugothemes.com/wp-content/uploads/2019/12/get-more-hugo-themes.png)](https://gethugothemes.com/shop/) |
| **Biztrox** | **Phantom** | **More Hugo Themes** |