# CFS Advanced Text Field

This plugin adds a new field type to Matt Gibbs' [Custom Field Suite](https://github.com/mgibbs189/custom-field-suite) that enables support for additional text input options and attributes, many of which were introduced with HTML5.

## Options

The following options are supported:

| Option             | HTML Attribute | Description                                                                  |
|--------------------|----------------|------------------------------------------------------------------------------|
| Type               | type           | HTML5 field type: text, email, number, tel, or url                           |
| Default Value      | value          | Value for the field upon creation                                            |
| Placeholder        | placeholder    | Text to display as the input placeholder                                     |
| Required           | required       | Mark the field as required (also adds "required" attribute, unlike CFS core) |
| Validation Pattern | pattern        | HTML5 validation pattern regexp, for client-side validation                  |
| Max Length         | maxlength      | Maximum number of characters                                                 |

Support for `min`, `max`, and `step` is coming soon.

Note that these options (with the exception of "required") are client-side validators.

## License

**Copyright (c) 2016 [Van Patten Media Inc.](https://www.vanpattenmedia.com/) All rights reserved.**

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

*   Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
*   Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
*   Neither the name of the organization nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.