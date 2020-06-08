## Well Hello there! :wave: This repository is not only meant to showcase my Fully Fuctional Form but to also show that how to create a repository on GitHub with some Proffesional touch to begin with.

# :ledger: Fully Functional Form for login and Sign Up.

Below you can see an animation that what i have created:-

![App Ideas Image](./giphy.gif)

# :books: The Project Description

Before we actually get into the code, I'd like to break down the code in sections. This will hep us to write the code in more organized way.


We have 4 smaller **boxes** inside the main component (  the ```.container```  ):

1. The Sign In form
2. The Sign Up form
3. The Sign In overlay
4. The Sign Up overlay

Also, at one moment in time you can see either:

   - The Sign In form alongside the Sign Up overlay
   - The Sign Up form alongside the Sign In overlay
   
In the overlay panels we have some text and a ````button```` - by clicking it you will bring up the other combination of screens and vice-versa. Check the GIF above one more time to see what I mean.

# :label: The forms animation-explained

These aren't difficult to understand at all. Basically we have again two containers - the ``.form-container``s - each having a ``width`` of ``50%`` and a ``position`` - ``absolute``. We move both of them at the same time from the left to the right, and when they get behind the ``.overlay-container`` from above (while these are moving) we quickly change the ``z-index`` value so the **Sign Up** form (for example) will move on top of the **Sign In** form, and vice-versa. Magic to the eyes, but just some code logic behind!:laughing:
