# Nested
Forked from [Jonas Blomdin](http://github.com/jonasblomdin/)

## How to implement filtering
Turns out this is easy, just add a .active class to your options.selector, then hide all :not(.active) before rerunning  $el.nested(options)

## Notes
- Removed demo files
- example.css only contains transition
- Added overlapping box fix (so 6 wide & greater than 6 high works)
- New attribute for eg data-size="12x12" because the ".size12" regex was limited
- Attempting to implement filtering
