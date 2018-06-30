# Making Contributions

Contributions are absolutely welcome!

So far, I've included most (all?) of the federal holidays in the United States, as well as a few others. There are tests for each holiday, in an attempt to make sure my calculations are correct. This is especially important around complex calculations like the one for Easter.

## Corrections

If you notice anything incorrect, please open a PR if you're able to fix it, or [open a new issue](https://github.com/grantwinney/erl-holidays/issues/new) with as many details as possible, including:

* the function you called,
* the values you passed to it,
* the incorrect result you got,
* the answer you _expected_

## Additions

If you have new holidays to add, you can open a PR (don't forget to add tests for it!), or you can open a [open a new issue](https://github.com/grantwinney/erl-holidays/issues/new) with as many details as possible, and I'll try to add it as time permits:

* the country code for the holiday,
* the calculation to figure out when it falls in a given year (if you know it),
* a few examples of valid dates when the holiday occurs
