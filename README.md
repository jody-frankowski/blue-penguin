![screenshot](https://tyler-carr.com/images/ftp/out.png)

# Blue Penguin Dark for pelican
A simple dark theme for pelican, with light/dark mode support using media queries available. Solarized pygments. Feeds support.

This theme has been adapted from the original [Blue Penguin Theme](https://github.com/jody-frankowski/blue-penguin) for use on [my website](https://tyler-carr.com), all changes are generic and this theme can be used interchangeably with the original. 

## Settings
```python
# all the following settings are *optional*

# HTML metadata
SITEDESCRIPTION = ''

# all defaults to True.
DISPLAY_HEADER = True
DISPLAY_FOOTER = True
DISPLAY_HOME   = True
DISPLAY_MENU   = True
DARK_LIGHT_SWITCHING_OFF = True

# provided as examples, they make ‘clean’ urls. used by MENU_INTERNAL_PAGES.
TAGS_URL           = 'tags'
TAGS_SAVE_AS       = 'tags/index.html'
AUTHORS_URL        = 'authors'
AUTHORS_SAVE_AS    = 'authors/index.html'
CATEGORIES_URL     = 'categories'
CATEGORIES_SAVE_AS = 'categories/index.html'
ARCHIVES_URL       = 'archives'
ARCHIVES_SAVE_AS   = 'archives/index.html'

# use those if you want pelican standard pages to appear in your menu
MENU_INTERNAL_PAGES = (
    ('Tags', TAGS_URL, TAGS_SAVE_AS),
    ('Authors', AUTHORS_URL, AUTHORS_SAVE_AS),
    ('Categories', CATEGORIES_URL, CATEGORIES_SAVE_AS),
    ('Archives', ARCHIVES_URL, ARCHIVES_SAVE_AS),
)
# additional menu items
MENUITEMS = (
    ('GitHub', 'https://github.com/'),
    ('Linux Kernel', 'https://www.kernel.org/'),
)

# example pagination pattern
PAGINATION_PATTERNS = (
    (1, '{url}', '{save_as}'),
    (2, '{base_name}/page/{number}/', '{base_name}/page/{number}/index.html'),
)

```

Dark/Light switching is disabled by default, but can be enabled in the config file by adding:

```
DARK_LIGHT_SWITCHING_OFF = FALSE
```


## How to contribute
Contributions are very welcome. Keep in mind that this theme goal is to be
minimalistic/simple. Contributions will be accepted through Github Pull
Requests. If you don’t have a Github account you can suggest me your
changes by email.

## Contributors
See [CONTRIBUTORS.md](CONTRIBUTORS.md).

## License
Public domain.
