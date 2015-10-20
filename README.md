# optgroup_max_options plugin for selectize.js

See the [Selectize Plugin Docs](https://github.com/brianreavis/selectize.js/blob/master/docs/plugins.md) for general use instructions.

This plugin allows to set the max number of items for optgroups that user can select.

```
  $('select').selectize({
    plugins: {
      'optgroup_max_options': {
        maxOptions: number
      },
    }
  });
```

```
<select id="select-repeated-options" class="demo-default" multiple>
	<option value="">Select...</option>
	<optgroup label="Group 1" data-data='{"maxOptions: 1"}'>
		<option value="1" selected="selected">Item A</option>
		<option value="2">Item B</option>
		<option value="3">Item C</option>
	</optgroup>
	<optgroup label="Group 2" data-data='{"maxOptions: 2"}'>
		<option value="4">Item A</option>
		<option value="5">Item B</option>
		<option value="6">Item C</option>
	</optgroup>
</select>
```

# selectize.js

Selectize is an extensible jQuery-based custom &lt;select&gt; UI control. It's useful for tagging, contact lists, country selectors, and so on. It clocks in at around ~7kb (gzipped). The goal is to provide a solid & usable experience with a clean and powerful API.

- [Demos](http://brianreavis.github.io/selectize.js/)
- [Changelog](https://github.com/brianreavis/selectize.js/releases)
- [Examples](examples/)
- [Usage Documentation](docs/usage.md)
- [API Documentation](docs/api.md)
- [Plugin Documentation](docs/plugins.md)
