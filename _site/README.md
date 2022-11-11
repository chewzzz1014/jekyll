## Overview
- Learning jekyll, a static site generator
- Pre: Install ruby and gem on my device. Then install `jekyll` package using gem (package manager for Ruby)


## Create a new jekyll website

```
jekyll new [blog name]
```

## To serve on local host
- Command for running for the first time.

```
    bundle exec jekyll serve
```

- 2nd time of running and above

```
jekyll serve
```

## To show draft on website too

- Build website for post and website
```
jekyll serve --draft
```


## Use other theme
1. Search for theme
2. Put in Gemfile

    ```
    gem "package-name-here"
    ```
3. Use command 

    ```
    bundle install
    ```
4. Change theme in _config.yml
5. Rerun server using

    ```
    bundle exec jekyll serve
    ```