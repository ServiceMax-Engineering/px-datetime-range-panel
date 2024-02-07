v2.3.2
==================
* Set both From and To to this date, when time is not enabled and only one date is selected on the Calendar Panel.
* Set the left calendar as the month selected from From

v2.3.1
==================
* Fixed vertical paddind and display issue

v2.3.0
==================
* Update z-index

v2.2.3
==================
* Added notify on timeIsValid

v2.2.2
==================
* added test for the reference bug between baseDate and the moment objs

v2.2.1
==================
* fixing demo pages for IE11

v2.2.0
==================
* added `allowApply` property to allow outside input into `_canApply`

v2.1.3
==================
* cleaned up api

v2.1.2
==================
* Updated to newest px-datetime-common behavior versions

v2.1.1
===================
* added `sudo:required` to travis

v2.1.0
===================
* updated `position: absolute` to `position: static` for rangepicker's iron-dropdown

v2.0.2
===================
* fix calendar dependency

v2.0.1
==================
* fix link in docs

v2.0.0
==================
* Polymer 1.X/2.X hybrid support
* range property has been deleted, please use `fromMoment` and `toMoment` for controlling the range. the px-datetime-range-submitted event still exists when a new range is applied.
* `fromMoment` and `toMoment` can be null to have an empty field

v1.0.8
==================
* add device flags

v1.0.7
==================
* Updated presets documentation

v1.0.6
==================
* Allow presets to be functions

v1.0.5
==================
* add min and max date support

v1.0.4
==================
* Fix comment for analyzer

v1.0.3
==================
* presets now deselect when cancel is clicked

v1.0.2
==================
* runtime theming for demo

v1.0.1
==================
* shows selected months on load

v1.0.0
==================
* update dependencies for design refresh
* component redesign
* Allow presets for time not just date

v0.5.0
==================
* added localization through resources, language, formats and Px.moment.changeLocale()

v0.4.14
==================
* added css var for dash between time fields

v0.4.13
==================
* converted time zone property to typeahead

v0.4.12
==================
* add Cloud Flare cache reset

v0.4.11
==================
* remove hidden from demo, add issue templates

v0.4.10
==================
* get rid of old code

v0.4.9
==================
* uprev

v0.4.8
==================
* add link to Moment documentation

v0.4.7
==================
* fixed issue with demo page

v0.4.6
==================
* added styling section to API documentation

v0.4.5
==================
* Moving theming style includes and updated ghp.sh
* updated api for new colors

v0.4.4
==================
* Update to px-demo
* removed demosass
* Updated to cool grays

v0.4.3
==================
* Update colors design to pick up new colors

v0.4.2
==================
* changing ghp.sh to account for Alpha releases

v0.4.1
==================
* Fixed event listeners in demo page

v0.4.0
==================
* Updated dependencies

v0.3.11
==================
* changing browser in wct testing from safari 8 to safari 10 on elcapitan

v0.3.10
==================
* changing all devDeps to ^

v0.3.9
==================
* Update px-theme to 2.0.1 and update test fixtures

v0.3.8
==================
* update dependencies for dropdown

v0.3.7
==================
* removing px-theme style call


v0.3.6
==================
* changing Gruntfile.js to gulpfile.js

v0.3.5
==================
* added style variables for theming

v0.3.4
==================
* bower updating px-demo-snippet

v0.3.3
==================
* fixed codepen

v0.3.2
==================
* Updated dependencies

v0.2.8
==================
* added overflow to demoContainer and removed flex__wrap from mega-demo

v0.2.7
==================
* fixed typo in init

v0.2.6
==================
* updated mega demo styles and bower px-demo-snippet to ^

v0.2.5
==================
* added image to readme, removed watch, added view on github

v0.2.4
==================
* Added vulcanize

v0.2.3
==================
* updated gh-pages script to vulcanize demo

v0.2.2
==================
* Fixed blockPastDates and blockFutureDates logic

v0.2.1
==================
* Added new demos

v0.2.0
==================
* Added blockPastDates

v0.1.4
==================
* Use local copy of moment.js

v0.1.3
==================
* fixed broken functionality in demo that didn't show buttons when clicked

v0.1.2
==================
* re-added the @demo tag to element to show demo button, and removed auto_ghp.sh script

v0.1.1
==================
* Auto build of github pages

v0.1.0
==================
* Upgrade to Polymer 1.5.0

v0.0.3
==================
* make sure presets respect blockFutureDates

v0.0.1
==================
* Initial release
