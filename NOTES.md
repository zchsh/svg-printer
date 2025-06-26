# Notes for svg-printer

## Next steps

- [ ] Add on-page docs-ish notes about print quirks
  - This tool is likely easiest to use on a larger screen, such as a tablet or laptop
  - Printing from certain browsers can be annoying.
  - Chrome seems to have the most considered approach.
  - Firefox seems to work pretty well, though I've run into some nitpicky bugs when printing SVGs.
  - Safari can be frustrating. The print preview sometimes doesn't match the printed document.

- [ ] Implement page size adjustment
  - In theory could rely on browser print... in practice, nice to have a preview
  - Number inputs for width and height

- [ ] Implement page size presets
  - Probably more useful than custom units

- [ ] Implement page size units
  - Start with `inches` most likely, cause that's how paper works where I am...
  - Add `mm` probably, that's it really