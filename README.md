Dashboard repository: https://github.com/fdarveau/flame

About Flame: Flame is self-hosted startpage for your server. Easily manage your apps and bookmarks with built-in editors. 

This is a guide on how to create your own custom CSS for Flame. 
Although there is a guide from the creator (https://github.com/pawelmalak/flame/wiki/Custom-CSS), it does not go into depth very much.

![image](https://user-images.githubusercontent.com/82758334/207410982-edc641d5-bb83-47dd-aa05-611c1d96c69c.png)
<p>&nbsp;</p>

I suggest opening three tabs or windows for this:
- First tab: open the dashboard 3 times (IP:PORT or FQDN); then on one go to Settings/ CSS. Here we will save the style adjustments.
- Second tab: open developer tools by pressing F12. With this we will find out how the elemnts are called, whcih we'd like to change.
- Third tab: this will be your review page, where you will review the changes.

With this in mind, let's start!

Open the page with the developer tools and go to the "Inspector" tab. Here you see all the classes you will be able to edit, however, you will first have to find them, which is not too hard.

![image](https://user-images.githubusercontent.com/82758334/207411420-56a28a9e-aa35-4360-89c1-069eae6cd1c6.png)
 
<p>&nbsp;</p>
You can expand and collaps the classes with the arrows. 
By hovering over them, you will see a "live selection" on the website in form of a highlited color:

![image](https://user-images.githubusercontent.com/82758334/207411840-23ec63ab-67c2-4100-b914-5ad10c2abe23.png)
 
 <p>&nbsp;</p>
With this in mind, let's find out on how to manually edit the Application headline. So, let's first expand all classes until we get to the application headline class. As we can see, the class is called ".SectionHeadline_SectionHeadline__2gmr_".

![image](https://user-images.githubusercontent.com/82758334/207412462-e103e90d-a0a3-4d16-8b61-2edb2c6592f4.png)
 
<p>&nbsp;</p>
Now, that we found the correct class, we can edit many things. For this, you will find the actual styling just right of the HTML section:

![Screenshot 2022-12-13 191551](https://user-images.githubusercontent.com/82758334/207413220-b1de074c-2cc4-4df0-bc51-a60aa5bb01ef.png)
 
<p>&nbsp;</p>
The easiest way to actually see your changes is to edit the values right in this window. Let's say we are not happy with the text color and size. We can easily adjust this by changing the following values:

![Screenshot 2022-12-13 191818](https://user-images.githubusercontent.com/82758334/207414105-aabf7be9-7b82-4fa3-bd00-6af1f3656471.png)
 
<p>&nbsp;</p>
In case you like the changes, copy the class name with its values into the Settings/ CSS of Flame and remove the values you didn't adjust (in this case text-transformation, font-weight and margin-bottom). 
 
![image](https://user-images.githubusercontent.com/82758334/207414236-82b0324e-132d-428d-b59c-d48032bb3fe4.png)

<p>&nbsp;</p>

Also add !important next to each value in order to override the standard style:

![image](https://user-images.githubusercontent.com/82758334/207417488-a5cddc49-ce40-43a7-9f4e-f64a31048da0.png)

Now click on save and refresh your dashboard!

And there you go, you made your first change to your own personal dashboard!

PS: If you changes don't appear, make sure to empty your cache: https://github.com/pawelmalak/flame/wiki/Custom-CSS
