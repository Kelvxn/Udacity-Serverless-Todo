# Getting Started
In this project you will develop and deploy a simple "TODO" application using AWS Lambda and Serverless framework. This application will allow users to create/remove/update/get TODO items. Each TODO item contains the following fields:

todoId (string) - a unique id for an item
createdAt (string) - date and time when an item was created
name (string) - name of a TODO item (e.g. "Change a light bulb")
dueDate (string) - date and time by which an item should be completed
done (boolean) - true if an item was completed, false otherwise
attachmentUrl (string) (optional) - a URL pointing to an image attached to a TODO item
You might also store an id of a user who created a TODO item. Each TODO item can optionally have an attachment image. Each user only has access to TODO items that he/she has created.
