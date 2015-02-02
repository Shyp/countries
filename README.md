# Countries

A list of countries in the world, and some data about them.

This is **not** identical to the ISO 3166 list - this is a combination of supported countries from our carrier partners.

We can ship to all of these places, so you can safely use this list in a dropdown picker.

## Attributes

- `name`: The name of the country
- `alpha-2`: The ISO 3166 alpha-2 country code for the country
- `alpha-3`: The ISO 3166 alpha-3 country code for the country
- `aliases`: Some other names for the country (e.g. to match against if you're parsing user input)
- `primary`: In the case of multiple countries that share the same country code, this identifies the name that the country codes should map to.

## Known differences from ISO-3166

- This list uses country names and codes from the Netherlands Antilles (rather than the Caribbean Netherlands).
- This list contains Zaire.
- This list does not contain around 30 countries that our partner carriers do not offer shipping to.

These differences are present in the lists that we've received from the carriers.
