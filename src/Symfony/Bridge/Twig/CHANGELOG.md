CHANGELOG
=========

2.2.0
-----

 * [BC BREAK] restricted the `render` tag to only accept URIs as reference (the signature changed)
 * added a render function to render a request
 * The `app` global variable is now injected even when using the twig service directly.
 * Added an optional parameter to the `path` and `url` function which allows to generate
   relative paths (e.g. "../parent-file") and scheme-relative URLs (e.g. "//example.com/dir/file").

2.1.0
-----

 * added global variables access in a form theme
 * added TwigEngine
 * added TwigExtractor
 * added a csrf_token function
 * added a way to specify a default domain for a Twig template (via the
   'trans_default_domain' tag)
