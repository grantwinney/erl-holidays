# erl-holidays

This is a module for testing whether or not a particular date is a holiday. Right now it's pretty much only US holidays, but [contributions are welcome](CONTRIBUTING.md)!

To use it, just pass in the [2-letter country code](https://www.worldatlas.com/aatlas/ctycodes.htm) and a standard `DateTime` in `{{Y,M,D},{H,m,s}` format. The time portion of the date is never used, but I wanted it to be as easy to pass in values obtained from the likes of [`local_time_to_universal_time_dst`](http://erlang.org/doc/man/calendar.html#local_time_to_universal_time_dst-1) and [`universal_time`](http://erlang.org/doc/man/calendar.html#universal_time-0).

## Issues / Suggestions

There's a separate module with dozens of tests to validate each holiday, so hopefully everything is okay.

If you see anything that looks wrong, or have new holidays to add, either [open a new issue](https://github.com/grantwinney/erl-holidays/issues/new) with as many details as possible or [create a new PR](https://github.com/grantwinney/erl-holidays/pulls).
