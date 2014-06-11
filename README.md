Serial
======

A really simple predictable Serial number generator in PHP 

## Usage

```php

// Generate:
$serial = Serial::Generate();
echo $serial; //4835-4E4F-4E43-B013-796D-CF77

// Validate:
if (Serial::Validate('4835-4E4F-4E43-B013-796D-CF77') == true)
  echo 'Thanks you';
else
  echo 'Error';
  
echo var_dump(Serial::Validate('4835-4E4F-4E43-B013-796D-CF77')); // bool(true)
echo var_dump(Serial::Validate('4835-4E4F-4E43-B013-796D-CF78')); // bool(false)
```

## License
Copyright (c) 2014 Hossam Youssef

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
