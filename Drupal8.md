Image URL
`{{ file_url(node.field_image.entity.fileuri) }}`

Concat String with Variable
`'some string' ~ some.Var ~ 'more string'`

Path to current theme
`{{ directory }}`

Using Attributes in Twig Templates
https://www.drupal.org/docs/8/theming-drupal-8/using-attributes-in-templates

See array details

```
<ol>
  {% for key, value in _context  %}
    <li>{{ key }}</li>
  {% endfor %}
</ol>
```

`composer require drupal/your_module_name`
`/usr/local/bin/composer.phar require drupal/your_module_name`

## Setting Up

`drush vset theme_debug 1`

## Going Live

`drush vset theme_debug 0`