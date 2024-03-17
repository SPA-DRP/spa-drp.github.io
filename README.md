# spa-drp.github.io
Webpage of the SPA Directed Reading Program and the University of Washington.

For questions about the DRP, please see the [contact page](https://spa-drp.github.io/contact.html) on the [DRP website](https://spa-drp.github.io/).

For questions about this respository and the codebase, please open a new [issue](../../issues/new).


## Building locally

### Setting up your local environment
The website is built using [Jekyll](https://jekyllrb.com/). Setup instructions for your OS can be found [here](https://jekyllrb.com/docs/installation/#requirements). Here are [some useful words](https://jekyllrb.com/docs/ruby-101/) to know.

### Build instructions

To build the website locally, run the following command and visit [localhost:4000](http://localhost:4000/) on your browser
```{shell}
$ bundle exec jekyll serve
```

If you get errors about missing/out-of-date gems, run the following command first
```{shell}
$ bundle install
```

### Why Jekyll and not HTML?

Simply put, it is easier to maintain and update in the long run. It allows you to re-use "code" and "data" easily, and automatically generates HTML pages for you with minimal effort. As you can see in the instructions below, one would only rarely edit HTML files directly.

It does take a little effort to set up Jekyll but the effort is worth it for long-term maintenance.

## Updating the website

#### Adding new projects for the next quarter

1. Create a new folder under `_projects` under the appropriate year and quarter.
2. For each project, create a new file. See below for the format of the file. (**APARA TODO: Write a script to automatically generate these files!**)
3. Go to `_archive` and create a new file with the appropriate name `yyyy_quarter.md`. Copy the contents from a previous quarter and just update the `year` and `quarter` variables. (**APARA TODO: Figure out if there is a way to programatically generate these files!**)
4. Go to `currentmentors.md`. Edit the `year` and `quarter` variables. Update the existing links and message to reflect applications being open/closed.
5. Test locally. If all looks good, commit and push.

#### Adding writeups for previous quarter

1. Add the writeups and slides to `writeups` folder. Sort them in an appropriate folder.
2. Go to the corresponding project files and update the `mentees` variable with the mentee name and links to the files. See below for the format and also take a look at existing files.
3. Test locally. If all looks good, commit and push.

#### Adding a news item

1. Go to `_data/news.yml`
2. Add a new news time in the same format as other items. The date should be in `YYYY-MM-DD` format.

### Format for each project

Each project gets its own file. This can be found in `_projects` (the nested folder structure is not necessary but helps with organization). Create a new file for each project that follows this template:

```{markdown}
---
mentor: Mentor Name
title: Project name
mentees:
  - name: Student 1
    slides: Relative path to the slides file. See existing files for example
    writeup: Relative path to the writeup file 
  - name: You can add more students here
    external: Maybe a link to a Shiny app?
prereq: "Prerequisites: Put in double quotes if there are colons in the description. Same for all other variables above"
year: 2025
quarter: autumn
---
Enter the description of the project here
```

Some important things to note:
* The block inside the `---` lines is called "front matter" and the variable names (like `mentor` or `title`) are case-sensitive.
* If a variable value in the front matter has a colon `:` (for example URLs or titles) put the variable in quotes.
* The variables, `mentor`, `title`, `prereq`, `year`, and `quarter` are necessary.
* `quarter` should be one of `autumn`, `winter`, or `spring`.
* The `mentees` variable is optional. For each mentee you add, the `name` variable is necessary. The other variables for each mentee is `slides`, `writeup`, and `external`. These variables are optional.
* See existing projects for examples.

