# form-control-directive-angularjs
angularjs directive to automatize the in-build form control error on each and every input set to validation

Angularjs v.1.x;

 - this directive automatically traces all input inside the form that need validation.
 (nd: use the name attribute in form and input you want to trace)
 - add an error text based on personal implementation of the directive.
(nd: to use correctly the directive the input tag has to be wrap in a parent container tag)
- the style applied uses two classe for the input: 'is-valid', 'is-invalid';
- a class 'text-danger' is embedded on the small tag that wrap the text message and that is injected into the dom.
- the directive use a $filter dependency to translate the text.(see: https://angular-gettext.rocketeer.be);
You'll find a simple implemenation based on required attribute.
