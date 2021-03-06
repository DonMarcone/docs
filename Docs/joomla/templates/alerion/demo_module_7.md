---
title: Alerion: Recreating the Demo - Location Detail
description: Your Guide to Recreating Elements of the Alerion Template for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/alerion:Alerion

---

Location Detail
-----
![][demo]
This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details
![][demo2]

| Option     | Setting                                            |  
| :--------- | :------------------------------------------------- |  
| Title      | Location[span class="hidden-tablet"] Detail[/span] |  
| Show Title | Show                                               |  
| Position   | utility-b                                          |  
| Status     | Published                                          |  
| Access     | Public                                             |  
| Language   | All                                                |  
| Note       | Blank                                              |  

>> The title of this module requires RokCandy in order to appear properly on the screen due to the `[span]` tags present. See the main [RokCandy](../../extensions/rokcandy/rokcandy_use.md#rokcandy-use-in-rockettheme-template-demos) guide for additional instructions.

### Custom Output
Enter the following in the **Custom Output** text editor.

~~~
[eventlocation no="2" name="/<span class="hidden-tablet">TECHNO</span>EVENT" place1="East 27 Street and Campus Road," place2="Brooklyn, NY 11210" date1="Mon<span class="hidden-tablet">day</span>, April 1, 2013 at 1:00 PM" date2="Tue<span class="hidden-tablet">sday</span>, April 30, 2013 at 4:00 PM"][/eventlocation]
~~~

### Basic
![][demo3]

| Option                    | Setting |  
| :------------------------ | :------ |  
| Prepare Content           | Yes     |  
| Select a Background Image | Blank   |

### Advanced
![][demo4]

| Option              | Setting                           |  
| :------------------ | :-------------------------------- |  
| Module Class Suffix | `box4 title4 jagged fp-utility-b` |  

[demo]: assets/demo_5.jpeg
[demo2]: assets/location_1.jpeg
[demo3]: assets/location_2.jpeg
[demo4]: assets/location_3.jpeg