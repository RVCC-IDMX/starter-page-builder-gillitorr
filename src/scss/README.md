# File Organization

## scss folder
The scss folder holds all of the other folders and files for specific element styling. 

### _main.scss
The _main.scss file includes the general styles for the whole web page (more general than specific)


### utilities folder
This folder includes stylesheets that may be applied to specific elements.


#### _functions.scss
The functions.scss file can only contain universal statements.

#### _variables.scss
The variables.scss file assigns values to a name that can be used in main.scss
#### _mixins.scss
The mixins.scss file also allows you to define styles that can be re-used throughout main.scss

### base folder
This folder contains all the resets and typography. In general, this folder contains all the CSS that handle the layout.

#### _typography.scss
This file includes font styling such as font faces, weights, line heights, and size. These may be applied to headings, body text, or any other text.

#### _reset.scss
This file contains short set of CSS rules that resets the styling of all HTML elements to a consistent baseline.

### components folder
The components folder is used to target specific parts of the HTML such as the header.

#### _header.scss
This file includes styling specific for the header.

### pages folder
This folder is used to have separate styles for sepeate pages.

#### _home.scss
This file contains styling specific to the home page.