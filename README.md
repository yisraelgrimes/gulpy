Gulpy v0.0.2


Need to add documentation.


To use this on it's own and not as a dependency of Fresh, make sure to update paths in `./gulpfile.js` and options in `./gulp.options.js` to fit your needs.

Also, make sure to change the variable `gulpOptions` from `../../../gulp.options` to `../gulp.options` before running any gulp commands. By default, Gulpy is set up to be used as a dependency from `node_modules`.

To see all available gulp tasks, run `gulp help` or `gulp info`.


---

## Changelog
- v0.0.2
	- Added tunnel options for BrowserSync Config.
- v0.0.1
	- Added initial task files