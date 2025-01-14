# Uncommon HTML Error: Misinterpreting Less-Than and Greater-Than Symbols

This repository demonstrates a subtle HTML error related to the improper use of less-than (&lt;) and greater-than (&gt;) symbols.  These symbols, when used directly in text without proper encoding, can be misinterpreted by the browser as HTML tags, leading to unexpected rendering issues or even errors.

## Bug Description
The bug occurs when these symbols are included within text content without being encoded using HTML entities. The browser incorrectly attempts to parse them as tags, causing errors or misinterpreting the surrounding text.

## Solution
The solution is to always encode these symbols using HTML entities: `&lt;` for less-than and `&gt;` for greater-than.  This prevents the browser from mistaking them for HTML tags.

## How to Reproduce
1. Open `bug.html` in your web browser.
2. Observe the unexpected rendering or errors.
3. Open `bugSolution.html` to see the corrected version.

## Related Resources
* [HTML Entities](https://www.w3schools.com/html/html_entities.asp)