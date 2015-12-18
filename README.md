# Radio button and checkbox with style

> Replacement for default radio button and checkbox style

### Install
```sh
$ git clone git@github.com:nkpgardose/radio-check.git
$ cd radio-check
$ open index.html
```

### Usage
```html
<!-- Radio button, use `input-radio` class -->
<fieldset>
  <legend>Radio Sample</legend>
  <input class="input-radio" type="radio" name="pokemon" value="Red" id="pokemonGreen" required>
  <label for="pokemonGreen">Green</label>
  <input class="input-radio" type="radio" name="pokemon" value="Blue" id="pokemonBlack">
  <label for="pokemonBlack">Black</label>
  <input class="input-radio" type="radio" name="pokemon" value="Yellow" id="pokemonGold">
  <label for="pokemonGold">Gold</label>
</fieldset>

<!-- Checkbox, use `input-check` class -->
<fieldset>
  <legend>Check these out</legend>
  <input class="input-check" id="checkbox4" type="checkbox">
  <label for="checkbox4">Checkbox 4</label>
  <input class="input-check" id="checkbox5" type="checkbox">
  <label for="checkbox5">Checkbox 5</label>
  <input class="input-check" id="checkbox6" type="checkbox">
  <label for="checkbox6">Checkbox 6</label>
</fieldset>
```

## License

MIT © [Neil Kim Gardose](https://github.com/nkpgardose)
