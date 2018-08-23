# A Responsive Fluid/Hybrid HTML Email Boilerplate

First of all I would like to thank and give full credit to [Nicole Merline for this excellent tutorial](https://webdesign.tutsplus.com/tutorials/creating-a-future-proof-responsive-email-without-media-queries--cms-23919) which I based this code upon.

I have changed the images to include image sizes as that makes life easier when trying to remember how large the image should be.  I have added a few more layouts and decided on the practice I personally would like to use for picking colours throughout the template.

I changed some naming conventions too.

This is a work in progress, it can be improved quote a lot consider this my first draft (in reality about 101st).
Once we fully test we'll supply screenshots.  

## Main Features
1. Responsive using fluid hybrid
2. Left text with right media acts responsively with the image above the text
3. Background images are created using the [camapign monitor](https://backgrounds.cm/) way of doing things
4. Custom fonts are implemented in a way that doesn't break in MS Outlook.  Custom fonts will not show in Outlook and some other email clients so you should be aware of that.  They will fall back to the font within the template.
5. A button that expands to any width depending on the text inside it.
6. Easy to adjust padding settings
7. Easy to implement colours and background colours
8. A 3 column grid
9. Some fixes to stop the 3 column grid from breaking in the MailChimp editor
10. Full MailChimp editing support.  Including repeatable blocks that you can add, remove or move as you wish.  There are some problems with the MailChimp editor which are beyond our control.  We recommend not trying to move the bottom module but dragging the second bottom below it.

## How to use it

Just look in the code it's all commented.  There are also MailChimp tags so it will work immediately in MailChimp.

**Please resize images before you upload!  Do not expect the template to constrain the images.  Outlook will use the original size so resize them before you use**.

 

## Where to get support

If you find an issue with the code, please raise an issue or submit a pull request.  

I'm not going to troubleshoot email issues that are not created by the template as is.  You can use [Stack Overflow](https://stackoverflow.com) for that.

If you want commercial (paid) support, designs, codes etc please contact me via my website [Square Balloon](https://www.squareballoon.co.uk)

### How to remove MailChimp.

For now it's there, but I'll make a separate version at some point without the codes.

TO remove it remove all references to:

mc:repeatable="options" 
mc:variant="  XXXX   " where x is the text
mc:edit

\*|UNSUB|* - MailChimps unsubscribe link
\*|UPDATE_PROFILE|* - MailChimps update profile link

 ## Can I use this commercially
 
 Go ahead
 
 ## The future
 
 I intend to make MailChimp and Non MailChimp versions.
 I intent to include a few more modules and styles, although I will leave the basic template as is
 I intend to give more people credit where I have used their teachings