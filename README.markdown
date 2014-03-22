# Pinboard tag plugin for Jekyll

Generates a list of links from a user's public [pinboard](http://pinboard.in/) bookmarks.

## Usage:

    {% pinboard user:username limit:# tags:tag,tag %}

## Example:

    {% pinboard user:ericdfields limit:15 tags:ruby,rails %}

## All paramaters are optional, e.g.:

    {% pinboard user:ericdfields %}

The only parameters you can pass with the tag are: `user`, `limit`, and `tags`.

## Configuration options available for use in `_config.yml`:

    pinboard_tag:
      user:       "ericdfields"
      limit:      15               # default
      list_tag:   "ol"             # default
      list_class: "pinboard_list"  # default
      a_target:   "_blank"         # default is ""
      tags:       "ruby,jekyll"

**Original plugin author:**

* Eric D. Fields
* http://github.com/ericdfields/Jekyll-Pinboard-Tag

**Updates by:**

* Bill Turner
* http://github.com/billturner/jekyll-pinboard-tag
