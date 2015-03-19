# Page Path History Manager Module for Processwire

This modules allows you to easily manage past page URLs tracked with the  [PagePathHistory] module.

It extends the settings tab on the page edit form in the backend and allows you to:

* view past URLs of the current page and parent pages,
* delete past URLs, and
* create new fallback URLs.

## Installation

1. Install the module [PagePathHistory] from within the Processwire admin. [PagePathHistory] is included in core but not installed by default.
2. Install this module from within the Processwire admin or copy the file content to `/site/modules/PagePathHistoryManager`.
3. In Admin, click Modules → Check for new modules to refresh module directory. Afterwards install the newly registered module PagePathHistoryManager.
4. You can now manage past URLs from within the settings tab when editing any page.

## License

The MIT License (MIT)

Copyright (c) 2015 Marc Löhe

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

[PagePathHistory]: https://github.com/ryancramerdesign/ProcessWire/blob/ccb1a190e7bb86e5/wire/modules/PagePathHistory.module