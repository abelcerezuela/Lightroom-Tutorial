===============================================================================
Adobe Photoshop Lightroom: how to make a basic photo editing, by Abel Cerezuela
===============================================================================

.. sectnum::

.. contents:: **Table of contents**

What is Adobe Photoshop Lightroom?
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Adobe Lightroom (officially **Adobe Photoshop Lightroom**) is a family of **image organization and image manipulation software** developed by *Adobe Systems* for Windows and macOS.

It allows viewing, organizing and editing large numbers of digital images, and the most important, Lightroom's edits are non-destructive.

Despite sharing its name with *Adobe Photoshop*, it cannot perform many *Photoshop* functions such as photo manipulation (adding, removing or altering the appearance of individual image items), rendering text or 3D objects on images, or modifying individual video frames. That's because **it's focused exclusively for a complete, clear and fast photographic and video edition** [#]_.

.. [#] en.wikipedia.org

Knowing its interface
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Lightroom is structured in **seven modules**: *Library, Develop, Map, Book, Slideshow, Print* and *Web*.

 .. image:: imgs/1-modules.png

Each Module is an independent section that contains a set of tools relevant only to that particular module. In other words, it is a way to group and organize different tools together. [#]_
The two core Modules are the *Library* and the *Deveolp*.

**Library Module**

Here is where you can **organize and manage your photographs**. Everything you need to help you find, import, sort and organize photographs is here. Navigation options are located on the left-side panel. This panel grants access to all images within the current Catalog. You can also choose to browse them by source Folder or Collection. To manage folders and physically move or copy image files, use the Folder tab. In addition to all of that, you can publish your images to online services with the help of “Publish Services” tab at the bottom of the left-side panel.

 .. image:: imgs/1.png

You can choose to view images in a resizable grid or one photograph at a time. A few filter options can be found on the **Filmstrip**, such as Flags and Color Labels. For more filters, hit the  ``\`` button to toggle the filter bar.
The filter bar allows you to **search images** by specifying lenses, focal lengths, aperture, camera, keywords or other criteria.

The right-side panel is your **metadata tool**. Here, you can add keywords and copyright information, as well as specify which metadata details to keep. Since you will most likely use the Library Module to sort through photographs and separate the good ones from the bad, the right-side panel also includes a small number of basic image adjustments.


.. [#] photographylife.com/lightroom-modules-explained

**Develop Module**

Without a doubt, this is the Module where you will be spending the majority of your time. It has a set of very useful and powerful tools that are specifically designed for editing images.

 .. image:: imgs/2.png

In the left-side panel, we have the **Presets** tab. Presets are extremely useful in speeding up your workflow. In this tab, you can create, organize and import/export Presets.
The left-side panel also includes some basic Library Module functionality – you can switch between different **Collections**.

**Filmstrip** at the bottom of the screen includes the usual navigation. As in the Library Module, some filtering options are also available – you can view images by rating, flags or color labels.

**The largest number of tools is found on the right-side panel**. In fact, nowhere else in Lightroom will you find such a huge amount of sliders and numbers to enter. This is where all the post-processing magic happens, from exposure tweaks to sharpening, noise reduction, tone curve, lens corrections... At the top of the panel you will find the ever-useful histogram and right under it, a list of area-specific tools for local adjustments and cropping.

The rest of modules are used less often, but they are equally powerful. For example, the **Web** module helps you to organize and publish an online photo gallery.
It creates the css and js necessary files and leaves them organized and stored in folders, ready to be published.

 .. image:: imgs/3.png

Let's start with a basic photo edition
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
We are going to transform the following image:

 .. image:: imgs/4.png

into this one:

 .. image:: imgs/5.jpg
    :width: 1000px

****

Import the image
--------------------
Click the option *Import...* located in the right-bottom corner of the *Library* module and select the photography that you want to edit.

 .. image:: imgs/4-import.png

****

Basic Panel
--------------------
Let's go to the *Develop* module. First of all, we want to improve the basic parameters such as White Balance, Exposure, Shadows and Saturation.
All of these basic controls can be found at the *Basic* panel.

Since our image it's really dark and it lacks color, we're going to move the *Shadows* slider to the right to make the shadows lighter (even make them disappear if you want!)
and also the *Vibrance* and the *Saturation* sliders to recover the colors of the real landscape (remember, the light, colors and all the other image data is stored
and preserved thanks to the raw image format. You just have to make this information appear or disappear moving the sliders controls!).

Moreover, we're going to lower the *Highlights* to recover some details in the sky.

This is our image now:

 .. image:: imgs/7-basics.png

You can already notice a huge change and this only is only the beginning!

****

Detail
--------------------

In order to obtain a sharper image we're going to increase the amount of sharpening at the *Detail* panel:

 .. image:: imgs/7-detail.png

Now, even the distant elements are clearly visible.

****

Crop Tool
-------------
We're going to swift crop our photo with the *Crop Tool* which is located under the *Histogram* and looks like a rectangle.

 .. image:: imgs/8-cutOut.png

****

Brush Tool
--------------
We want to edit separately the rocks, plants and water of this landscape. To achieve this, we're going to use the *Brush Tool* and select each one of these elements.

**Rocks**

We're going to select the rocks by painting them and enhance the *Clarity* control:

 .. image:: imgs/9-brushRocks1.png

Now, the micro-contrast, shapes and forms of the rocks are more defined:

 .. image:: imgs/10-brushRocks2.png

**Plants**

Let's make the plants luminous:

 .. image:: imgs/12-brushPlants2.png

**Water**

And increase the water highlights:

 .. image:: imgs/14-brushWater2.png

****

Last touches: Tone Curve and Color Selection
------------------------------------------------
We're going to boost the brightness of the whole photograph using the *Tone Curve*.

The *Tone Curve* represents all the tones of your image. The bottom axis of the Tone Curve
is the Tone axis: the line starts with Shadows at the left-most end and ends with Highlights
in the right-most end. In the middle you have Midtones, which are then further split into
darker Midtones, called Darks in Lightroom, and brighter Midtones, called Lights. In other
words, going left to right, the curve starts with Shadows, Darks, Lights and ends with Highlights [#]_.

 .. [#] photographylife.com/mastering-lightroom-how-to-use-the-tone-curve-panel

More Lights and less Darks and Shadows:

 .. image:: imgs/15-lightTones.png

Finally, we want to increase the saturation of the yellow color exclusively.

We can do that with the color selection:

 .. image:: imgs/16-yellows.png

****

Export the final result
----------------------------
Return to the *Library* module and click the option *Export...* :

 .. image:: imgs/17-export.png

Here you can set many options, like the *export location*, the *file name* or the *image size* :

 .. image:: imgs/18-exportOptions.png

Before export the photo, we're going to add a watermark to protect the copyright of our creation:

 .. image:: imgs/19-watermark.png

****

**Now we can admire our masterpiece**

 .. image:: imgs/5.jpg
    :width: 1000px
