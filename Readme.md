# DOM Js
Collection of small frequently used Js functions for DOM elements manipulation across projects. Nothing fancy, just simple stuff. Simply for writing less code.

## Issues
Please use [Github issues](https://github.com/code-soup/dom-js/issues) to submit any bugs you may find.


## Documentation

    @import dom from 'dom-js';
   
Wrapper of document.querySelector();

    dom.get('.selector'); 
    dom.getAll('.selector'); // instead of document.querySelectorAll();
    
Un/Set class on node

    dom.addClass(node, className); 
    dom.removeClass(node, className);
    
Un/Set class on node via selector

    dom.setClass(selector, className);
    dom.unsetClass(selector, className);
 
Get Bounding rect

    dom.getRect(selector)
    
Get dataset attribute

    dom.getData(node, attr);


#### License
This project is licensed under the [GPL license](http://www.gnu.org/licenses/gpl-3.0.txt).