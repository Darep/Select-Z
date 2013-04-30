# Select Z

Select Z is a jQuery plugin for creating styled dropdowns, checkboxes and
radio buttons.

What does Select Z do:

1. Hooks onto the elements you choose
2. Hides the elements
3. Creates a bunch of HTML elements with descriptive CSS classes
4. Hooks the events so everything works
5. ...let's you style the new elements and create any look you want

## Usage

Add the `jquery.selectz.js` and some CSS styles (see `jquery.selectz.css` for examples) to your project.

Then turn a &lt;select> element into a more easily styled one:

	$('.styled-select').selectz();

You can pass the `selectz()` function some options, if you want to:

	$('.styled-select').selectz({
		extraClass: 'secondary-select'
	});

See [examples.html](https://rawgithub.com/Darep/Select-Z/master/examples.html)
for simple examples on how it works.

Supports IE7+ and most (if not all) modern browsers.

## Syncing

Select Z also supports "syncing" of selection elements: if you have multiple
select boxes with a list of same options, changing one selection can also
change the selection on the other select box.

Sync two selections by simple doing this:

	var synced_selects = $('.synced-select');  // there needs to be atleast two
	synced_selects.selectz().syncSelections();

### License

MIT License

Copyright (C) 2012-2013 ajk.fi and Solita Oy

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
