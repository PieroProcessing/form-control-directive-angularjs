# form-control-directive-angularjs
angularjs directive to automatize the in-build form control error on each and every input set to validation

Angularjs v.1.x;

this directive automatically traces all input inside the form that need validation and add an error text based of personal implementation you have to write on the directive.
To use correctly the directive the input tag has to be wrap in a parent container tag.
The style applied uses two classe for the input: 'is-valid', 'is-invalid';
and the class 'text-danger' on the small tag that wrap the text message.
You'll find a simple implemenation based on required attribute.
