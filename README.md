# Relation English Formatter

Provides a proof of concept field formatter for Relation fields.

**Daniel Phin** ([dpi][dpi]) ([web][web])

Turns related entities from unordered lists to English style lists.

For example: EntityLink, EntityLink, and EntityLink.

Installation.

* You must ensure the patch on http://drupal.org/node/1015732 comment #2 is applied. Unless it has been committed.
* Enable `Relation English Formatter` module.
* Go to the Display tab of the Node Type the relation field is on.
  http://localhost/drupal/admin/structure/types/manage/{nodetype}/display
* Find the instance of a Relation field in the list.
* In the `Format` column, change formatter from `Default` to `Relation English Natural`.

[dpi]: http://drupal.org/user/81431 "Drupal.org profile of `dpi`"
[web]: http://danielph.in/ "Daniel Phin"