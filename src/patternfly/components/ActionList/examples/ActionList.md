---
id: 'Action list'
beta: true
section: components
cssPrefix: pf-c-action-list
---

## Examples
### Basic
```hbs
{{#> action-list}}
  {{#> action-list-item}}
    {{#> button button--modifier="pf-m-primary"}}Action{{/button}}
  {{/action-list-item}}
  {{#> action-list-item}}
    {{#> button button--modifier="pf-m-primary"}}Action{{/button}}
  {{/action-list-item}}
  {{#> action-list-group}}
    {{#> action-list-item}}
      {{#> button button--modifier="pf-m-primary"}}Action{{/button}}
    {{/action-list-item}}
    {{#> action-list-item}}
      {{#> button button--modifier="pf-m-primary"}}Action{{/button}}
    {{/action-list-item}}
  {{/action-list-group}}
  {{#> action-list-group}}
    {{#> action-list-item}}
      {{#> button button--modifier="pf-m-primary"}}Action{{/button}}
    {{/action-list-item}}
    {{#> action-list-item}}
      {{#> button button--modifier="pf-m-primary"}}Action{{/button}}
    {{/action-list-item}}
  {{/action-list-group}}
  {{#> action-list-item}}
    {{#> button button--modifier="pf-m-primary"}}Action{{/button}}
  {{/action-list-item}}
  {{#> action-list-item}}
    {{#> button button--modifier="pf-m-primary"}}Action{{/button}}
  {{/action-list-item}}
  {{#> action-list-item action-list-item--modifier="pf-m-icon"}}
    {{#> button button--modifier="pf-m-primary"}}Icon{{/button}}
  {{/action-list-item}}
  {{#> action-list-item action-list-item--modifier="pf-m-icon"}}
    {{#> button button--modifier="pf-m-primary"}}Icon{{/button}}
  {{/action-list-item}}
  {{#> action-list-item action-list-item--modifier="pf-m-icon"}}
    {{#> button button--modifier="pf-m-primary"}}Icon{{/button}}
  {{/action-list-item}}
{{/action-list}}
```

## Documentation
