# fuzzy-autocomplete

http://jsfiddle.net/wjs4ktqa/

1. Load JQuery and fuzzy-autocomplete.js in header
2. Define your input element: ```<input id='sample-input'>```
3. Call fuzzy-autocomplete library
  4. Load with native array: ```fuzzyAutocomplete($('#sample-input'), ['data1', 'data2', 'data3']);```
  5. Load json array with ajax: ```fuzzyAutocomplete($('#sample-input'), '/path/to/file.json');```
4. See <code>sample.html</code> and aforementioned jsfiddle for working demonstration
