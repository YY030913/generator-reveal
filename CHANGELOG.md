# Changelog

## v0.3.0
### Changes
- Add `grunt dist` task.
- Add optional `sass` support for custom themes.
- Clean up API: HTML slides behave the same as markdown slides:
    * Both may use the `--attributes` option.
    * HTML slides no longer need to contain their own encapsulating `<section>` element.
    * Support `{}`, `{"attr": "some-attr"}`, `{"filename":"some-filename"}` and `{"attr": "some-attr", "filename":"some-filename"}` as valid slide `Objects` in the `slides/list.json` `Array`.
- Use `.yo-rc.json`, i.e. store user input in config.
- Add Changelog :)
- Remove `coffee-script` as a production dependency.

## v0.2.0
### Changes
- Rewritten in Coffee, but keeping API compatibility.
- Add `--attributes` option.