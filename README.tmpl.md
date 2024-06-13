# CRUD the `project_urlname` with Playground

## What

- [Create, read update, delete & save][export-to-github] `project_urlname` using Playground and persist it with prepared settings for GitHub Export.
- or simply browse & view ...
   - [`project_urlname` with *Twentytwentyfour*](https://playground.wordpress.net/?url=/?p=173&login=yes&import-wxr=https://raw.githubusercontent.com/author_name/project_urlname/main/export.xml).
   - [`project_urlname` with *Disco*](https://playground.wordpress.net/?url=/?p=173&login=yes&import-wxr=https://raw.githubusercontent.com/author_name/project_urlname/main/export.xml&theme=disco).
   - [`project_urlname` with *Ollie*](https://playground.wordpress.net/?url=/?p=173&login=yes&import-wxr=https://raw.githubusercontent.com/author_name/project_urlname/main/export.xml&theme=ollie).

### You should create a new repository from [this template](https://github.com/new?template_name=crud-the-docs-playground&template_owner=carstingaxion) for yourself, if you'd like to ...

- **collaboratively work** on some demo-data or even real content, used within multiple WordPress Playgrounds.

- let people create website-content for their **scenarios using your plugin or theme**.

- keep a set of demo-data within a clean environment **for screenshots and screencasts**.

- invite people for engagement **during a WordPress contributor day**.

- use **git based version** tracking in favor of WordPress revisions.

- have an instant website with built-in theme switcher & [countless possible designs](https://wordpress.org/themes/tags/full-site-editing/) (*aka block themes*)

- see how it works & test it.

### Ready in 10 seconds

Creating a new repository from [this template](https://github.com/new?template_name=crud-the-docs-playground&template_owner=carstingaxion) lets you start immediately, because all paths, folder names etc. will be replaced to match the URLs of your new created repo. *Enjoy!*

This happens within an automated first commit directly after the repo gets initialised. So, please calm for 10 seconds and finally refresh the page.

## Why

> Idea for the [WCEU Contributor day](https://gatherpress.org/event/hybrid-event-wceu2024-contributor-day/): 
>
> Create a demo of your special use case with GatherPress & Playground!
> And let's grow a collection like the blueprint-galleries.
>
> https://gatherpress.slack.com/archives/CNZS6PPFZ/p1717928500570539

https://github.com/carstingaxion/gatherpress-demo-data

## How

- Setup from template repo to replace paths, etc.
- The `blueprint.json` files is made & validated using the playground-based [blueprint builder][builder]
- Images ...
- Export to xml ...
- Export to GitHub
- ...

### *Settings*

```json
{
    "step": "setSiteOptions",
    "options": {
        "blogname": "Books",
        "blogdescription": "CRUD the Books in Playground.",
        "wordpress_export_to_server__file": "books.xml",
        "wordpress_export_to_server__owner_repo_branch": "author_name/example-books/main",
        "wordpress_export_to_server__export_home": "https://example.test/books"
    }
}
```


### Ressources
- [Query API | WordPress Playground](https://wordpress.github.io/wordpress-playground/query-api/)
- [How to add demo content in WordPress](https://learn.wordpress.org/lesson-plan/how-to-add-demo-content-in-wordpress/) - Learn WordPress


## Based on & wouldn't work without

- the Export to GitHub feature of WordPress Playground
- and a small, custom plugin, that saves a regular export.xml to the file system, instead of downloading it to the user.

### Inspired by

- [adamziel/playground-docs-workflow](https://github.com/adamziel/playground-docs-workflow)
    Experimenting with maintaining WordPress docs using WordPress Playground
- and [bgrgicak/playground-blog](https://github.com/bgrgicak/playground-blog) 
    A built using WordPress Playground

### Acknowledgments

  - [python-project-template](https://github.com/rochacbruno/python-project-template) for their nice template->repo renaming workflow




[builder]: https://playground.wordpress.net/builder/builder.html?blueprint-url=https://raw.githubusercontent.com/author_name/project_urlname/main/blueprints/blueprint.json


[export-to-github]: https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/author_name/project_urlname/main/blueprints/blueprint.json&gh-ensure-auth=yes&ghexport-repo-url=https://github.com/author_name/project_urlname&ghexport-pr-action=create&ghexport-playground-root=/wordpress/wp-content/project_urlname-main&ghexport-repo-root=/&ghexport-path=.&ghexport-content-type=custom-paths&ghexport-commit-message=Changes%20from%20Playground&ghexport-allow-include-zip=no