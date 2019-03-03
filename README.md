# Form Placeholder
Fork of Drupal Form Placeholder Module for Backdrop CMS: (http://drupal.org/project/form_placeholder).

Support for older browsers has been left off this version, as the Placeholder attribute is now widely supported.

## Installation
1. Install Form Placeholder (form_placeholder) module as usual.
2. Go to configuration page at "admin/config/user-interface/form-placeholder".
3. Specify CSS selectors for textfields you want to add a placeholder.


## Example

To add placeholders for the Login, Register, Password & Password reset forms copy and paste this text into the "Visibility" settings box:

#user-login #edit-name
#user-login #edit-pass
#user-register-form #edit-name
#user-register-form #edit-mail
#user-pass #edit-name
#user-pass-reset-form #edit-pass-pass1
#user-pass-reset-form #edit-pass-pass2

