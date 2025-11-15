# BaseKit Recipes

Composer package of Drupal Recipes for BaseKit:
- `recipes/basekit` — base modules + shared config
- `recipes/article` — Article content model (type, fields, displays, roles, views)
- `recipes/blocks/...` — per custom block bundle
- `recipes/site` — aggregator composing the above

Apply:

```
php core/scripts/drupal recipe gravellian/basekit-recipe:recipes/site
# Or individually
php core/scripts/drupal recipe gravellian/basekit-recipe:recipes/basekit
php core/scripts/drupal recipe gravellian/basekit-recipe:recipes/article
php core/scripts/drupal recipe gravellian/basekit-recipe:recipes/blocks/hero_headline
```

