# remove-Lee-paywall-overlay
Browser bookmarklet to remove the Lee Services "subscription wall" overlay

Single line is here: https://github.com/jasonbuechler/remove-Lee-paywall-overlay/blob/master/remove-lee-bookmarklet.js

```
# protocol head for the URI
# note this cannot be pasted into Chrome's uri box...
# ...but can be added to a saved bookmark ("bookmarklet")

javascript:

# target rootmost element, disable its display

document.querySelector('.fc-ab-root').style.display='none';

# clear the 'overflow' style to re-enabled scrolling

document.body.style.overflow='';

# return something or else Chrome will deliver a blank page

void(0);
```
