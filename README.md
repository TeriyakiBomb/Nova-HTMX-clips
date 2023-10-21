A selection of basic clips for **HTMX** 🌍

## Details


Clips follow standard attribute name format for clarity and triggers are named to correspond with the attributes minus hyphens, for example:

| Title         | Description                           | Trigger    |
| ---           | ---                                   | :-:        |
| **hx-boost**  | Inserts hx-boost="true"               | `hxboost`  |
| **hx-get**    | Inserts hx-get=""                     | `hxget`    |
| **hx-vals**   | Inserts hx-vals=""                    | `hxvals`   |

This extension also provides alternates and shorthand for common attributes, for example:

| Title                     | Description                                       | Trigger       |
| ---                       | ---                                               | :-:           |
| **hx-swap delete**        | Inserts hx-swap="delete"                          | `hxswapdel`   |
| **hx-swap none**          | Inserts hx-boost="none"                           | `hxswapnone`  |
| **hx-trigger click**      | Inserts hx-trigger="click"                        | `hxclick`     |
| **hx-trigger alt**        | Inserts hx-trigger="keydown[key=='altKey']"       | `hxalt`       |


HTMX clips offers clips in the following categories:

- Core attributes
- Triggers
- Additional attributes

## Updates

There's quite a few, but I don't think there's 100% coverage of all attributes, just the ones I've used + a quick look through the HTMX docs to bulk it out to make it more useful for other people. If there's anything you'd like to see added, feel free to create an issue on the repo