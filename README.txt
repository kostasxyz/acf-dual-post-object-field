ACF Dual Post Object Field
==================================================
Saves the post ID of the post that has the post object field 

Description
-----------

This ACF (Advanced Custom Fields) field is an extension of the post object field.
The post object field saves a post object in a custom field of a post.
The Dual post object field saves the the id of the post with the post object field in a custom field ('reverse_obj') of the post object.

Example:
Let's say we have 2 custom post types. Projects and Tasks.
So a project has many tasks.
Create a custom field for tasks in the ACF with field type of Dual post object.
Now when you select the project object that the task belongs to, the dual post objects also saves in the custom field 'reverse_obj' in the project of the id of the task.
Everything is stored in serialized data.

This is an atempt for reverse relationship.
There is a discussion here about reverse in the ACF forum http://support.advancedcustomfields.com/discussion/1979/how-to-getting-the-reverse-relationship-from-a-relationship-field

Hope that this is something helpfull.