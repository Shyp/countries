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
- `dialCode`: The calling dial code of the country, including the '+' prefix.

## Known differences from ISO-3166-1

https://gist.github.com/dylanpyle/5472b81ec907d629e44b

Several countries or country codes are different from the ISO list - these are either fairly recent political developments, or countries that our carrier partners do not offer shipping to. We'll update this list as the carrier themselves update their own.
