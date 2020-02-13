# generamba-templates
[Generamba](https://github.com/rambler-digital-solutions/Generamba) - code generator for Xcode. Repository contains templates.

## List of templates

* [MVP screen](https://github.com/HandsAppTeam/generamba-templates/tree/master/handsapp_mvp_screen) - generates a new screen of HandsAppMVP architecture.
* [MVP table screen](https://github.com/HandsAppTeam/generamba-templates/tree/master/handsapp_mvp_table_screen) - generates a new screen of HandsAppMVP architecture contains UITableView.

## Installation

To install a template just put these strings in your `Rambafile` and run `generamba template install` in Terminal

```
### Catalogs
catalogs:
- 'https://github.com/HandsAppTeam/generamba-templates'

### Templates
templates:
- {name: template_name}
```
