# mensa-menus

This script fetches and displays menus for ETH mensas and the Mercato UZH mensa.

## Installation

Simply download the file and drop it in a folder in your `$PATH`

## Usage

Type `menus` to get a list of all default locations.

Type `menus location` (substitute 'location' by a valid location) to get a list of all current menus and their price.

Type `menus location --all` to get all menus, even the blocked ones.

It will show the Dinner Menus after 14:00 (your system time) and next day's lunch after 21:00.

## Customization

Open the file `menus` in your favourite text editor.

Change the value of `prices` to `'student'`, `'staff'` or `'extern'` to get the prices desired. (Line 8)

Add or remove menu names from `blocked_menus` to hide menus you're not interested in. By default, most vegi menus are blocked, because yuck vegies... (Line 12)

Modify the default locations by changing the `locations`. See Line 14 etc. for ids. (Line 33)
