# Security Expectations: Form Assertions

This package contains some patterns and functions which are helpful for testing common security problems facing forms.

## Use Cases

Common use cases supported by this package are:

- Static HTML forms
- Client-side generated forms
- ReactJS forms

The controls covered here are:

- Text input
- File input
- Password input
- Textarea input

## Issues tested

### TODO:General best practices

- There's some limitation on the field

### TODO: Cross-site scripting

Testing for this vulnerability includes checking for:

- Scripts input by users
- Attempts to break commonly used, but insecure, validation and sanitization methods

This field checks all three of text, password, and textarea inputs.

### TODO: File type uploads

For this, we check to make sure that there is _some_ limitation on file types accepted

### TODO: Bad password rules

Here we'll check for:

- Minimum password rules
- Passwords which are too short, or which restrict the use of longer passwords
- Allowing common passwords
