Use the Form Validator component to validate forms without a server-side round-trip while also conforming to the established standards set out in the [GOV.UK Design System](https://design-system.service.gov.uk/).

{{dsExample({
  name: 'form-validator',
  example: 'default',
  height: 1000
})}}

## When to use this component

Use this when sorting is needed to help find data within a large table of data. This might be useful in combination with the [filter](/patterns/filter-a-list) pattern.

## How it works

In alignment with established GOV.UK Design System standards:

* validation is performed on submit. Forms should never be validated as the user types or blurs the field.
* when the form is submitted with errors, focus moves to the error summary; errors are shown above the field and the `<title>` is prefixed with the error count.
* submit buttons are never disabled.

## Research on this component

To be added.