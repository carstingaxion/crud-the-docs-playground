# CRUD the `project_urlname` with Playground

## What

- [Create, read update, delete & save][export-to-github] the demo-data using Playground and persist it with prepared settings for GitHub Export.
- or simply browse & view ...
   - [the `docs` with *Twentytwentyfour*](https://playground.wordpress.net/?url=/?p=173&login=yes&import-wxr=https://raw.githubusercontent.com/author_name/project_urlname/main/export.xml).
   - [the `docs` with *Disco*](https://playground.wordpress.net/?url=/?p=173&login=yes&import-wxr=https://raw.githubusercontent.com/author_name/project_urlname/main/export.xml&theme=disco).
   - [the `docs` with *Ollie*](https://playground.wordpress.net/?url=/?p=173&login=yes&import-wxr=https://raw.githubusercontent.com/author_name/project_urlname/main/export.xml&theme=ollie).

## How

- The `blueprint.json` files is made & validated using the playground-based [blueprint builder][builder]
- Images ...
- Export to xml ...

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

# Why

> Idea for the [WCEU Contributor day](https://gatherpress.org/event/hybrid-event-wceu2024-contributor-day/): 
>
> Create a demo of your special use case with GatherPress & Playground!
> And let's grow a collection like the blueprint-galleries.
>
> https://gatherpress.slack.com/archives/CNZS6PPFZ/p1717928500570539

## Based on & wouldn't work without

- the Export to GitHub feature of WordPress Playground
- and a small, custom plugin, that saves a regular export.xml to the file system, instead of downloading it to the user.

## Inspired by

- [adamziel/playground-docs-workflow: Experimenting with maintaining WordPress docs using WordPress Playground](https://github.com/adamziel/playground-docs-workflow)
- and [bgrgicak/playground-blog: A built using WordPress Playground](https://github.com/bgrgicak/playground-blog)

## Ressources

- [How to add demo content in WordPress](https://learn.wordpress.org/lesson-plan/how-to-add-demo-content-in-wordpress/) - Learn WordPress


[builder]: https://playground.wordpress.net/builder/builder.html?blueprint-url=https://raw.githubusercontent.com/author_name/project_urlname/main/blueprints/blueprint.json


[export-to-github]: https://playground.wordpress.net/?blueprint-url=https://raw.githubusercontent.com/author_name/project_urlname/main/blueprints/blueprint.json&gh-ensure-auth=yes&ghexport-repo-url=https://github.com/author_name/project_urlname&ghexport-pr-action=create&ghexport-playground-root=/wordpress/wp-content/project_urlname-main&ghexport-repo-root=/&ghexport-path=.&ghexport-content-type=custom-paths&ghexport-commit-message=Changes%20from%20Playground&ghexport-allow-include-zip=no