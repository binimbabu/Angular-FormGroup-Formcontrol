# Formgroup

FormGroup is part of Angular's reactive forms module.
It tracks the value and validity state of a group of FormControl instances (i.e., input fields). It allows you to manage related form fields together.


FormControl is a class provided by Angular's Reactive Forms module that represents a single form input field. It tracks:

The field’s value

Validation status

Touched/untouched and dirty/pristine states

It is the basic building block used in FormGroup and FormArray.

Syntax

new FormControl(initialValue, validators?)


initialValue: The default value for the control.

validators: (Optional) An array of synchronous validators like Validators.required, Validators.minLength, etc.
