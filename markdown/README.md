Markdown Formatted Licenses
===========================

Formatting rules for converting a license into the markdown format:


General Formatting
------------------

*   Hard wrap all lines at 80 characters. It's a good line length.

*   Files should be named using the license's acronym followed by `-LICENSE.md`.

*   Leave ALL CAPS sections alone (i.e. don't convert to bold), [they need to be
    conspicuous in all formats](http://programmers.stackexchange.com/questions/194142/can-i-convert-all-caps-sections-of-an-osi-license-to-regular-case-and-bold).


Headers
-------

*   Level 1 and level 2 headers should use the two line header style:

        Some Level 1 Header
        ===================

        Some Level 2 Header
        -------------------

*   Headers should always have a blank line following them, and two blank lines
    preceding them (unless it's the document header).

*   There should be only one level 1 header: the document header. It should
    include the name of the license, any versioning information, and the acronym
    of the license. For example:

        The GNU General Public License, Version 2, June 1991 (GPLv2)
        ============================================================


Lists
-----

*   List items should have a blank line between each.

*   List items should be indented 4 spaces each. Ditto nested lists.

        1.  List item.

            a.  Sub item.

        2.  Another thingo.

*   Use `*` to indicate bulleted lists.

*   **Be careful to not relabel ordered lists!** Markdown _always_ starts
    ordered lists at 1. You may want to use sub-headings to preserve ordering.
