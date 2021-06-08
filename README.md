[![Build Status](https://travis-ci.com/jcs-elpa/liquidmetal.svg?branch=master)](https://travis-ci.com/jcs-elpa/liquidmetal)
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

# Liquid Metal
> Quicksilver scoring algorithm, essentially LiquidMetal

Port from https://github.com/rmm5t/liquidmetal.

## Usage

```el
(liquidmetal-score "FooBar" "foo")   ; 0.950
(liquidmetal-score "FooBar" "fb")    ; 0.917
(liquidmetal-score "Foo Bar" "fb")   ; 0.929
(liquidmetal-score "Foo Bar" "baz")  ; 0.0
(liquidmetal-score "Foo Bar" "")     ; 0.8
```

## Contribution

If you would like to contribute to this project, you may either
clone and make pull requests to this repository. Or you can
clone the project and establish your own branch of this tool.
Any methods are welcome!