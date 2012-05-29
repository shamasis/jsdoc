OVERVIEW
========

JSDoc 3 Haruki is an experimental template optimised for use with publishing processes that consume either JSON or XML. Whereas the default JSDoc template outputs an HTML representation of your docs, Haruki will output a JSON, or optionally an XML, representation.

Currently Haruki only supports a subset of the tags supported by the default template. Those are:

  * @name
  * @desc
  * @type
  * @namespace
  * @function (or @method)
  * @var (or @member)
  * @class
  * @event
  * @param
  * @returns
  * @throws
  * @example
  * @access (like @private or @public)
  

USAGE
=====

    ./jsdoc myscript.js -t templates/haruki -d console -q format=xml