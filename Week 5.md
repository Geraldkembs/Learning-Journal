
Week 5

Learning Activities & Resources

This week, I dedicated some time to learning about child themes in WordPress. This is a critical topic for anyone looking to customize WordPress sites while keeping them functional and maintainable. I discovered how child themes work, their benefits, and the practical steps to create one

Estimated Hours

I spent about 6hrs of my time this week understanding the overview and what is expected of me during this course.

Content Insights

Definition and Purpose of Child Themes:

A child theme is a sub-theme that inherits the look and functionality of a parent theme. It allows users to make customizations without risking the integrity of the parent theme when updates are made.
This is particularly important as themes are often updated for security and improved features. Without child themes, any custom work done directly in the parent theme would be lost after an update.
Benefits of Using Child Themes:

Safe Updates: 
Customizations remain intact even after updating the parent theme.
Flexibility:
Allows tweaking of styles and functions without extensive coding.
Learning Opportunity:
Provides hands-on experience with WordPress theme development.
How to Create a Child Theme:

I learned that setting up a child theme involves a few simple steps:
Create a New Folder:
In the /wp-content/themes/ directory, create a new folder for the child theme.
Add style.css: 
This file must include a comment at the top specifying the name, the template (parent theme), and other details.
Add functions.php:
This file is used to enqueue the parent theme’s stylesheet and any additional scripts or styles I might want to add later.

Challenges Encountered
Debugging some CSS conflicts that arose when the child theme was activated took up additional time, but it was a valuable learning experience.

