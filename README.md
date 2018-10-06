#ESQuery-jsx
ESQuery-jsx is a library for querying the AST output by Esprima for patterns of syntax using a CSS style selector system. With [JSX support](https://github.com/RReverser/estraverse-fb#).

[Full Documentation](https://github.com/estools/esquery)

## Thanks 

Thanks to [allesklarbeidir](https://github.com/allesklarbeidir) for raising the following [PR](https://github.com/estools/esquery/pull/57). 


## Plan Going forward
Once the JSX PR lands in [esquery](https://github.com/estools/esquery/pull/57), I will depdeprecate `esquery-jsx`;

For JSX-Support use:

`var esquery = require("esquery/jsx");`

instead of:

`var esquery = require("esquery");`

(Note the '/jsx' part)

[![Build Status](https://travis-ci.org/estools/esquery.png?branch=master)](https://travis-ci.org/estools/esquery)
