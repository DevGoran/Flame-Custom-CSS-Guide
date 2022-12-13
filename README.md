Dashboard repository: https://github.com/fdarveau/flame

About Flame: Flame is self-hosted startpage for your server. Easily manage your apps and bookmarks with built-in editors. 



This is a guide on how to create your own custom CSS for Flame. 
Although there is a guide from the creator (https://github.com/pawelmalak/flame/wiki/Custom-CSS), it does not go into depth very much.


**********Insert Dashboard pic example**********


I suggest opening three tabs or windows for this:
- First of all, open the dashboard 3 times (IP:PORT or FQDN); then on one go to Settings/ CSS. Here we will make the style adjustments.
- Second, open developer tools by pressing F12. With this we will find out how the elemnts are called, whcih we'd like to change.
- Third, this will be your review page, where you will review the changes.

With this in mind, let's start!

Open the page with the developer tools and go to the "Inspector" tab. Here you see all the classes you will be able to edit, however, you will first have to find them, which is not too hard.

**********Insert Inspector pic example**********

You can expand and collaps the classes with the arrows. By hovering over them, you will see a "live selection" on the website in form of a highlited color:

**********Insert Arrow pic example**********

With this in mind, let's find out on how to manually edit the Application headline. So, let's first expand all classes in order to find the application headline class.

**********Insert classes expanded pic example**********

Now, that we found the correct class, we can edit many things. For this, you will find the actual styling just right of the HTML section:

**********Insert Styles window pic example**********

The easiest way to actually see your changes is to edit the values right in this window and see the changes immeditaly. Let's say we are not happy with the text color and size. We can easily adjust this by changing the following values:

**********Insert values pic example**********

**********Insert preview pic example**********

In case you like the changes, copy the class name with its values into the Settings/ CSS of Flame:

**********Insert CSS setting pic example**********

Important: add !important to each line you adjusted in order to override the design with your changes:

**********Insert CSS pic example**********

Now click on save and check your dashboard!

**********Insert dashboard changes pic example**********

And there you go, you mind your first change to your dashboard!
