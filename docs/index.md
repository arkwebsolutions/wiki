
# Home

For full documentation visit [mkdocs.org](https://mkdocs.org).


## Heroku Cheat Sheet

Enter console: `heroku run console -a app-name` 

Enter logs: `heroku logs -tail -a app-name`

Check DB Status: `heroku run rake db:migrate:status -a app-name`

Run DB Migrate: `heroku run rake db:migrate -a app-name`
## Rails
## Ruby

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs help` - Print this help message.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
