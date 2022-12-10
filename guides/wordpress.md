# WordPress SPLOT Guide

Alan Levine https://cog.dog • SPLOT https://splot.ca

This documentation provides general information for installing, updating, and tending to the [WordPress-based SPLOTs](https://splot.ca/category/splots/wordpress/). While each one includes its own set of specific documentation this is aimed as a general reference and also some key information for the versions previously set up via the Reclaim Hosting application installers.

## Meet The SPLOTs

Each WordPress SPLOT is found on Github where you will find general information, a set of examples of other sites using that SPLOT, installation instructions, and detailed documentation on settings, customizations, and update instructions. A github account is not required to download a SPLOT theme (but is handy to have for asking question in the discussion forums posting issues)

Learn more via the links to Github or view a more friendly formatted version for each SPLOT via Docsify This.

* TRU Writer [Github](https://github.com/cogdog/truwriter) | [Docsify This](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/cogdog/truwriter/master&sidebar=true#/?id=tru-writer-wordpress-theme)
* TRU Collector [Github](https://github.com/cogdog/tru-collector) | [Docsify This](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/cogdog/tru-collector/master&sidebar=true#/)
* SPLOTbox [Github](https://github.com/cogdog/splotbox)| [Docsify This](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/cogdog/splotbox/master&sidebar=true#/)
* SPLOTpoint [Githubt](https://github.com/cogdog/splotpoint)| [Docsify This](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/cogdog/splotpoint/master&sidebar=true#/)
* Daily Blank [Github](https://github.com/cogdog/dailyblank)| [Docsify This](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/cogdog/dailyblank/master&sidebar=true#/)
* DS106 Assignment Bank [Github](https://github.com/cogdog/ds106bank)| [Docsify This](https://docsify-this.net/?basePath=https://raw.githubusercontent.com/cogdog/ds106bank/master&sidebar=true#/)


##  Requirements

Creating a WordPress SPLOT requires a self-hosted Wordpress site (the kind that you download or install from [wordpress.org](http://www.wordpress.org). Knowledge of WordPress concepts of pages vs posts, menus, categories, tags, the Customizer will go a long way but is not critical-- but find a friend or colleague to help.

You cannot use a SPLOT theme on a free "wordpress.com" site-- it is possible there with a paid business plan. One example I know of is the [Glendale Community College Center for Teaching, Learning, & Engagement](https://gccazctle.com/) running the SPLOTbox theme. 

Any web host will do, but I most highly recommend [Reclaim Hosting](https://reclaimhosting.com/) if you need to set up your own hosting space. They are awesome.

You will first need to create a new empty Hello World WordPress site.

## Install the Parent theme
Each WordPress SPLOT requires a different "parent" theme that provides the basic structure and presentation for your SPLOT. For example,  TRU Collector requires the Fukasawa theme and SPLOTbox requires one called Garfunkel (full detail are provided in each SPLOT's installation instructions).

Install the specified parent theme within the Wordpress Dashboard under **Appearance** -- **Themes** searching on the theme name. You do not need to activate it, the parent theme merely needs to be present.

Each SPLOT theme is a "child" that adds extra functionality and formatting to provide the SPLOT capability. Next are  two ways to install a SPLOT theme.

## Manual Installation

Don't be daunted by the word "manual" (think of it like driving a car with a stick shift, once you have mastered the clutch, it becomes second nature)!

Each SPLOT site offers a link to download the entire theme in `.zip` file format to a computer. You do not need to open or expand it, just have it handy.

The zip can be uploaded directly to your site via **Themes** (under **Appearence**) in the Wordpress dashboard, then click **Add Theme** and finally **Upload Theme**. Once uploaded, you can activate the theme and your SPLOT is ready for you to start making your own.

There will be more things to set up via the SPLOT's theme options and/or the WordPress Customizer. Refer to each theme's documentation for full details (the latest documentation is always available in the SPLOT theme's options).

You are all done!


### Updating a Manually Installed SPLOT

I am regularly updating SPLOTs to address bugs, issues, but more often to add features. I pledge to never add something that will break a previously set up site, but also keep in mind that I am not a professional programmer!

Note that WordPress's reporting of themes being up to date does **not** reflect custom themes such as SPLOTs. The way you can check is to first note the version of the theme you currently have in use. Find the active SPLOT theme in your Dashboard via  **Appearance** then  **Themes**. Hover over that theme and click the  **Theme Details** button. Note the version number of the SPLOT theme on your site.

Then visit the Github home for your SPLOT and look for what it lists as the current version. If the version on GitHub is a higher number, you may choose to update your SPLOT. It is not urgent to frequently update, but is worth checking, maybe every year.

How complex is it to manually update? Not complex at all! You update a SPLOT theme the exact way you originally installed it. Just download the `.zip` file for new version, and then in your dashboard, go to **Themes** (under **Appearence**). then click **Add Theme** and finally **Upload Theme**. Select the new `.zip` version of your SPLOT theme. Once uploaded you will be asked to confirm updating the theme with the newer version.  

When done, your site should report this new version on your own SPLOT site.


## WP-Pusher Installation

### WP-Pusher Updates

## Updating Reclaim Hosting SPLOT

## PHP 8 Notes





