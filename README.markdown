# MaskValidator

This gem was inspired in the Sobrinho's gems to validate simple things inside of ActiveModel.

Use mask in inputs and validate then in the models.

## Installation

`gem "mask_validator"`

## Usage:

`validates :phone, mask: "(99) 9999-9999"`

`validates :acronym, mask: "***"`

* a - Represents an alpha character (A-Z,a-z)
* 9 - Represents a numeric character (0-9)
* * - Represents an alphanumeric character (A-Z,a-z,0-9)

For more information about masks in the form inputs check the jquery plugin [Masked input](http://digitalbush.com/projects/masked-input-plugin/)

## License

Copyright © 2011 Marcelo Cajueiro, released under the MIT license
