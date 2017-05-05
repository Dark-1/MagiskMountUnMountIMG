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
  
  
GitHub Pages Site : [**Magisk Mount & UnMount IMG**](https://dark-1.github.io/MagiskMountUnMountIMG "GitHub Pages") .  
GitHub Repository : [**MagiskMountUnMountIMG**](https://github.com/dark-1/MagiskMountUnMountIMG "GitHub") .  
XDA Developers Thread : [**[Magisk] Magisk Mount & UnMount IMG**](https://forum.xda-developers.com/apps/magisk/magisk-mount-unmount-img-t3597614 "XDA Developers") .  
  

----------

----------

## Notes ##  
  
Usefull for Users/Developers who wants to Edit Magisk IMG.  
  
Module folder can be [Deleted/Added] to [Remove/Add] a Module.  
File can be [Edited/Modified/Deleted/Added] as per Users/Developers wish.  
  
This *ZIP* Mount's OR UnMount's on Different Condition's :  
1. If `magisk.img` is NOT Mount'ed , Then Mount `magisk.img` To `/Magisk` .  
2. If `magisk.img` is Mount'ed , Then UnMount `/Magisk` From `magisk.img` & Shrink `magisk.img` .  
   
   
Following is the **Pseudo** Code :  
  
- IF [ `magisk.img` is NOT Mount'ed ] , Then :  
  - This *ZIP* will Mount Magisk IMG.  
  - Mount `magisk.img` -> `/Magisk` .  
- ELSE , Then :  
  - This *ZIP* will UnMount & Shrink Magisk IMG.  
  - UnMount `/Magisk` -> `magisk.img` & Shrink `magisk.img` .  
   
   
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
#### Template v3 ! ####  
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
  
.
