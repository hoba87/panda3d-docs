# Panda3D Engine Documentation

This repository contains a work-in-progress conversion from the old Mediawiki format to a new Sphinx-based site. This should make it much easier for people to contribute to the documentation, and will also allow us to have the manual and API reference in one place.

Since this new format is still quite rough around the edges, Panda3D's main website will still be linking to the old manual.

## Todo List
- [x] Base conversion utilizing [the panda-sphinx repository](https://github.com/Moguri/panda-sphinx)
- [ ] Manual fixes for formatting issues
- [ ] Welcome page (index.rst)
- [ ] Move API Reference from Doxygen to Sphinx
- [ ] Spellcheck/proofread

## Building The Documentation
```
pip3 install -r requirements.txt
python3 -m sphinx ./source ./build
```

## Coding Style

When editing the documentation, please try to conform to the following
guidelines:

* Running text should be wrapped to an 80-character ruler. Many editors have
  a feature to do this automatically (eg. Alt+Q in Sublime Text).
* Please configure your editor to strip extra spaces at the end of a line.
* Use a single blank newline at the end of each file.
* Indentation for ReStructuredText should be 3 spaces, except code blocks,
  which need to be indented to 4 spaces for Python code and 2 for C++.
* See the [Python guide](https://devguide.python.org/documenting/#style-guide)
  for more information.