# Magisk Mount & UnMount IMG #  

----------

### Magisk ###  
by **topjohnwu**  

----------

This is **Magisk Mount & UnMount IMG** *ZIP* for Users/Developers.  
A.K.A. "**M2UI**" in Short.  
  
By **Dark**❶  
Profile @ XDA-Developers : [**Dark**❶](http://forum.xda-developers.com/member.php?u=7292542 "XDA Profile") .  
Profile @ GitHub : [**Dark**❶](https://github.com/dark-1 "GitHub Profile") .   
WebSite @ GitHub Pages : [**Dark**❶ WebSite](https://dark-1.github.io "GitHub WebSite") .   
  
**Magisk Mount & UnMount IMG** :-  
GitHub Pages Site : [**Magisk Mount & UnMount IMG**](https://dark-1.github.io/MagiskMountUnMountIMG "GitHub Pages") .  
GitHub Repository : [**MagiskMountUnMountIMG**](https://github.com/dark-1/MagiskMountUnMountIMG "GitHub") .  
XDA Developers Thread : [**[Magisk] Magisk Mount & UnMount IMG**](https://forum.xda-developers.com/apps/magisk/magisk-mount-unmount-img-t3597614 "XDA Developers") .  
  

----------

----------

## Notes ##  
  
Useful for Users/Developers who wants to Edit Magisk IMG.  
Works WithOut Magisk Binary.  
  
Module folder can be [Deleted/Added] to [Remove/Add] a Module.  
File can be [Edited/Modified/Deleted/Added] as per Users/Developers wish.  
  
This *ZIP* Mount's OR UnMount's on Different Condition's :  
1. If `magisk.img` is NOT Mount'ed , Then Mount `magisk.img` To `/Magisk` .  
2. If `magisk.img` is Mount'ed , Then UnMount `/Magisk` From `magisk.img` .  
   
   
Following is the **Pseudo** Code :  
  
- IF [ `magisk.img` is NOT Mount'ed ] , Then :  
    - This *ZIP* will Mount Magisk IMG.  
    - Mount `magisk.img` -> `/Magisk` .  
- ELSE , Then :  
    - This *ZIP* will UnMount & Shrink Magisk IMG.  
    - UnMount `/Magisk` -> `magisk.img` .  
   
   
I have **Copied** the Code from "magisk-module-template" ZIP by **topjohnwu**.  
I have **Edited** some part of the Code to make it work.  
I have **Added** some part of the Code to make it work.  
I have **Removed** Un-Necessary part of Code Because It is *Either* Not Used *OR* Not Needed.  
I have **Removed** Un-Necessary Directory(s) & File(s) Because It is *Either* Not Used *OR* Not Needed.  
  
###### EnJoY ...  :smiley: ######  
  
#### Credit's ####
  
Thanks **topjohnwu** for Magisk & for the code in "magisk-module-template" , could not have done without it.  

----------

## Changelog ##  
  
#### v0.0 ####  
- Initialized.  
  
#### v1.0 ####  
- Initial Release.  
- Copied the Code.  
- Edited some part of the Code.  
- Added some part of the Code.  
- Removed Un-Necessary part of Code.  
- Removed Un-Necessary Directory(s) & File(s).  
   
#### v1.1 ####  
- Updated `README` .  
- Updated `update-binary` .  
- Added `.gitattributes` .  
- Fixed `curSizeM` & `curFreeM` .  
   
#### v1.2 ####  
- Updated `README` .  
- Updated `update-binary` .  
- Added Function `image_resize_shrink()` & `image_check()` .  
- Changed Most Function Variable's to Local Variable's .  
- Modified Check for `IMG` in `/data` OR `/cache` .  
- And Then , Called `image_check()` to Verify .  
   
#### v1.3 ####  
- Updated `README` .  
- Updated `update-binary` .  
- Removed Function `image_resize_shrink()` .  
- Did Some Optimization of Code .  
- This Does Not Require Magisk Binary .  
- This is the Last Release ,  
- As I am Dis-Continuing this Project ,  
- Due to Creation of Advance Version of Same .  
- Thank You .  
  
.
