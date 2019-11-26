# Week 13<br>From Notebooks to the Web: Github Pages, Web Servers, and Dash

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MUSA-620-Fall-2019/week-13/master?filepath=lecture-13.ipynb)

## Updating your local environment

There are a few new packages we'll need this week so we'll need
to update your Python environment.

The `environment.yml` in this repository
contains all of the necessary packages. To update your local environment:

**Step 1.** Download the `environment.yml` file in this repository to your computer.

**Important:** Make sure you download the **raw** version of the file from GitHub and that the file extension on your computer is `.yml`.

**Step 2.** From either the Anaconda Prompt (Windows) or Terminal app (MacOS):

```
conda env update --file environment.yml --name musa-620
```

where `musa-620` should be the same name of the environment you have been using.

## Github Pages Template

See the Github Pages Starter template repository at: https://github.com/MUSA-620-Fall-2019/github-pages-starter/

### Steps

- Click on the "Use this template" button to create a new repository.
- Choose a new name for your new repository
- Go to the Settings section of your new repository, scroll down to the "Github Pages" section, and select the "Master" as the branch to be used for GitHub pages. This will automatically build the website.
- Customize your site
  - Enter your site name, description, etc by editing the `_config.yml` file.
  - There are 3 different ways that you can make changes to your blog's files:
    - Edit files within your in the browser at GitHub.com
    - Use a third party GitHub content editor, like [Prose by Development Seed](http://prose.io).
    - Clone down your repository and make updates locally, then push them to your GitHub repository.
- Publish a post
  - Posts are written in Markdown and any files added to the `_posts` directory will be automatically uploaded and published
  - Useful resource: [Markdown Cheatsheet](http://www.jekyllnow.com/Markdown-Style-Guide/)

## Reference

- [Github Pages Markdown Cheatsheet](http://www.jekyllnow.com/Markdown-Style-Guide/)
- [Introduction to Web Servers](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_web_server)
- flask
  - [Documentation](http://flask.pocoo.org/docs/1.0/)
- HTML and CSS
  - [Introduction to HTML and Tutorials](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)
  - [Introduction to CSS and Tutorials](https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS)
- Dash
  - [User Guide](https://dash.plot.ly/)
  - [Dash core components](https://dash.plot.ly/dash-core-components)
  - [Dash HTML components](https://dash.plot.ly/dash-html-components)
  - [App Gallery](https://dash.plot.ly/gallery)
  - [Plotly Documentation](https://plot.ly/python/)
- [Deploying a Dash app](https://dash.plot.ly/deployment)
- [Heroku guide to Python](https://devcenter.heroku.com/articles/getting-started-with-python)
