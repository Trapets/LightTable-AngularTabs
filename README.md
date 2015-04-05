# Angular tabs in LightTable

Custom css-file for the [LightTable](http://www.lighttable.com) to display angular tabs.

## Install
Copy ilus.css to:
* Windows `c:\Users\USERNAME\AppData\Local\LightTable\User\`
* Linux `/home/USERNAME/.config/LightTable/User/`

Add `:lt.objs.plugins/load-css` into your user.behaviors:
`[:app :lt.objs.plugins/load-css "/full/path/to/ilus.css"]`
