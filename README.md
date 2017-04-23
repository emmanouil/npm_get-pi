Get Pi
=========
Git repository for get-pi npm module https://www.npmjs.com/package/get-pi
=========
A small library that returns the requested digits of Pi (π). The return pseudo-type is according to the request.
 * _Int_ if only decimals are quested (default) __AND__ number of digits requested is less than 17.
 * _Float_ if only decimals are quested (default) __AND__ number of digits requested is less than 17. 
 * _String_ if explicitly requested __OR__ number of digits requested is less than 17. 


Supported commands:
 - `.getPi(<digits - optional>, <decimalsOnly - optional>)` (returns _digits_ digits of Pi (default = 4), starting counting after the decimal. i.e. for n=1 returns 1)
 - `.getPiString(<digits - optional>, <decimalsOnly - optional>)` (returns a String with _digits_ digits of Pi (default = 4), starting counting after the decimal. i.e. for n=1 returns 1)


## Installation

  `npm install get-pi`

## Usage

    var gip = require('get-pi');

    var numIndex = gip.getPi();
  
  
  Output should be `3.1416`

## NOTES

    Rounding on the last digit occurs ONLY when returning _Float_

## Tests

  TODO

## Contributing

...is welcome :)
