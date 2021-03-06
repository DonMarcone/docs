---
title: Tessellate: Recreating the Demo - RocketLauncher Packages
description: Your Guide to Recreating Elements of the Tessellate Demo for Joomla
breadcrumb: /joomla:Joomla/!templates:Templates/tessellate:Tessellate

---

RocketLauncher Packages
-----

![][demo]

This area of the front page is a **Custom HTML** module. You will find the settings used in our demo below.

>> Any **mod_custom** (Custom HTML) modules are best handled using either RokPad or no editor as a WYSIWYG editor can cause issues with any code that exists in the **Custom Output** field.

### Details

![][demo2]

| Option      | Setting                   |
| :---------- | :----------               |
| Title       | `RocketLauncher Packages` |
| Show Title  | Hide                      |
| Position    | expandedtop-a             |
| Status      | Published                 |
| Access      | Public                    |

### Custom Output

Enter the following in the **Custom Output** text editor.

~~~ .html
<p><strong>RocketLauncher Packages</strong></p>

<p>The RocketLauncher is a custom Joomla install, that installs the demo content and data onto your server, allowing for easy replica of the demo. It is easier to edit than to start afresh.</p>

<a href="http://www.rockettheme.com/docs/joomla/templates/tessellate" class="readon4">Read More</a>
~~~

### Basic

![][demo3]

| Option                    | Setting     |
| :----------               | :---------- |
| Prepare Content           | No          |
| Select a Background Image | Blank       |

### Advanced

![][demo4]

| Option              | Setting                                       |
| :----------         | :----------                                   |
| Module Class Suffix | `fp-expandedtop-a box3 rt-center nomarginall` |

[demo]: assets/demo_22.jpeg
[demo2]: assets/demo_22a.jpeg
[demo3]: assets/demo_22b.jpeg
[demo4]: assets/demo_22c.jpeg
