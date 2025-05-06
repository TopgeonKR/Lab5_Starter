# Lab 5 - Starter
Make sure you make a PR to your own repo's main and not the class' repo!! Otherwise you will lose points!!

**Name:** Sanggeon Jung
**Partner:** None(solo)


 1) Would you use a unit test to test the “message” feature of a messaging application? Why or why not? For this question, assume the “message” feature allows a user to write and send a message to another user.

- No, I wouldn't use a unit test for the message feature. Sending a message includes many things like typing, clicking a send button, and the message going to another user. It’s not just one small function, so it’s better to test with something bigger like an integration test.


1) Would you use a unit test to test the “max message length” feature of a messaging application? Why or why not? For this question, assume the “max message length” feature prevents the user from typing more than 80 characters.

- Yes I would use a unit test for max message length feature. I believe this is a simple rule. It just checks if the message is shorter than 80 characters. That is perfect for a unit test because it's small and easy to test by itself.