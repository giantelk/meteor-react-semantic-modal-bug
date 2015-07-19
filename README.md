#Bug with Meteor, React and Semantic-UI.

I can't get 2 Modal windows to show, only the 1st one shows. I CAN get this working without react, i.e. with only Meteor & Semantic-UI.

Using Mac OS, and Chrome browser.

##Update
Here's the fix, silly typo:
https://github.com/giantelk/meteor-react-semantic-modal-bug/issues?q=is%3Aissue+is%3Aclosed

`$('.ui.modal.my-dialog-two')` was missing the `.` before `ui.modal.my-dialog-two`.

- end
