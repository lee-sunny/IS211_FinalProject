# IS211_FinalProject

Project Option 2: Blog Application

python app.py


Example logins

Email: lee@demo.com   PW: testing
  
Email: testuser@demo.com    PW:testing


User workflow

My Blog/Home - provides a list of all blog posts in reverse chronological order. Users can read them without logging in.

Register - Requires unique username(between 2-20 characters) and email. Validation is in place so an error is thrown if username or email is already in the system. Password is hashed for security. A profile pic can be updated. A default pic is provided in static folder. For existing users, a link at the bottom to signin page is provided. Once all requirements are fulfilled and user clicks the sign up bottom, a success message is given and user is redirected to login page.

Login - User email and password is validated and user is redirected to their own Dashboard page. Once validated and logged in, the navigation bar on the right side is changed and user has access to "My Dashboard", "New Post", "Account", and "Logout".


My Dashboard - In the dashboard, user can click on existing post titles which are linked so that they can update or delete the post.
All posts are displayed in reverse chronological order (whether in Home or Dashboard view). The update page is permalink/update for each blog post. The existing blog post tile and content is pre-populated to ease of editing. The delete button throws a modal to prevent accidental deletions.

New post - Each post is required to have a title and content. The time is stamped authomatically.

Account - Allows user to update their username or email as well as profile picture. If username or email is updated, previous info is deleted in the database.


EXTRA CREDIT:

The application supports multiple users. As long as the username and email is unique. The user, once logged in, can also update their information in "Account" link in top right. This updated information replaces their previous credentials. Login required is used for updating and deleting existing posts and also only author of each post has access to the update and delete features.

EXTRA CREDIT:

Perma-links: A unique URL is created for each blog post. Whether on the Home page or the Dashboard page, each blog post title is linked to its own perma-link. Also each username is linked to the user's own dashboard which also uses permalinks with username.


