# go2json

parse .go files, output JSON

This code is fairly hacky. **Not** the result of indepth study and
consideration. It's more a glob of code that sort of seems to work for the cases
that I'm dealing with.

The idea is to make something a little easier to deal with to write generators
based on existing code. Mostly to be able to get info about defined structs to
use a template to generate database CRUD code.

The go2json.json file found here is the result of running this program on
itself.
