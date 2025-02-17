# Changelog

## v0.3.0

**Release date: 11/14/2021**

 - Begin a `team` module that allow for schedule scraping for each team (thanks to [@andrewsseamanco](https://github.com/andrewseamanco))
 - Fix a few bugs in `summary` and `misc` scraping modules, see [#9](https://github.com/j-andrews7/kenpompy/issues/9) & see [#7](https://github.com/j-andrews7/kenpompy/issues/7).
 - Fix issue with `get_program_ratings` due to additional column being added.

## v0.2.0

**Release date: 02/16/2020**

 - Added the `FanMatch` class for scraping the FanMatch page.
   - Also calculate predicted Margin of Victory and slightly alters format of output table for more convenient use.
 - Fix several edge-case bugs in `summary` and `misc` scraping modules, mostly having to do with teams with no rank.


## v0.1.0 - Initial Release

**Release date: 12/26/2019**

 - Provide functions for scraping nearly all `Summary` and `Miscellaneous` pages.