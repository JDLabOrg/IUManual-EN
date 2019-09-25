Complex Widget
============

Transition
----------

.. image:: resource/widget/IUTransition.png

.. thumbnail:: resource/capture_window/transition.png

Transition widget has two transition items. When mouse action triggered,
transition item will change from item 1 to item 2.
You can set **Mouse Action (Mouse Over or Click)** , Transition Effect,
and Duration in property panel.

**Property**

* Child : Invalid
* Link  : Valid
* Scroll Animator : Valid
* Background Image : Invalid
* Backend Ellipsis : Invalid



Carousel
----------

.. image:: resource/widget/IUCarousel.png

.. thumbnail:: resource/capture_window/carousel.png

Carousel widget has multiple carousel items.
You can simply make carousel interface with carousel widget.
Carousel item is the same as Box widget, so you can add or remove child elements to Carousel item.

**Property**

* Child : Invalid
* Link  : Valid(Only for child widget)
* Scroll Animator : Invalid
* Background Image : Invalid
* Backend Ellipsis : Invalid



Google Map
----------

.. image:: resource/widget/IUGoogleMap.png

.. thumbnail:: resource/capture_window/google_map.png

Google Map widget represents google map element. You can input **Map location** wherever you want.

.. note::
  1) In Editor Mode, Google Map widget offers maximum preview 600 px x 600 px size.
  2) South Korea's map is not available Color Theme feature.

**Property**

* Child : Invalid
* Link  : Invalid
* Scroll Animator : Valid
* Background Image : Invalid
* Backend Ellipsis : Invalid



Web Movie
-----------------

.. image:: resource/widget/IUWebMovie.png

.. thumbnail:: resource/capture_window/vimeo_youtube.png

Web Movie widget supports Youtube or Vimeo. You can use Web Movie widget with **Short-Links** :

* ``Vimeo`` : http://vimeo.com/ **videoURL**
* ``Youtube`` : http://youtu.be/ **videoURL**

**Property**

* Child : Invalid
* Link  : Invalid
* Scroll Animator : Valid
* Background Image : Valid
* Backend Ellipsis : Invalid



Video Clip
----------

.. image:: resource/widget/IUMovie.png

.. thumbnail:: resource/capture_window/video_clip.png

Video Clip widget supports MP4. You can input videos from Resource panel.

**Property**

* Child : Invalid
* Link  : Valid
* Scroll Animator : Valid
* Background Image : Valid
* Backend Ellipsis : Invalid



Table
----------

.. image:: resource/widget/IUTable.png

.. thumbnail:: resource/capture_window/table.png

Table widget can add simple table on canvas.

**Property**

* Child : -
* Link  : -
* Scroll Animator : -
* Background Image : -
* Backend Ellipsis : -

----------



.. image:: resource/widget/IUSimpleTabView.png

Simple Tab View
-----------------------------------

.. thumbnail:: resource/capture_window/simple_tab_view.png

Simple Tab View widget has more simple structure than Tab View widget .

**Property**

* Child : -
* Link  : -
* Scroll Animator : -
* Background Image : -
* Backend Ellipsis : -



Tab View
----------

.. image:: resource/widget/IUTabView.png

.. thumbnail:: resource/capture_window/tab_view.png

Tab View widget has multiple **Tabs** .

**Property**

* Child : -
* Link  : -
* Scroll Animator : -
* Background Image : -
* Backend Ellipsis : -


Collapsible
-------------

.. image:: resource/widget/IUCollapsible.png

.. thumbnail:: resource/capture_window/collapsible.png

Collapsible widget has two item (Header and Content).
When you triggered mouse action on Collapsible widget, Content item will be appeared.
You can set **Mouse Action (Mouse Over or Click)** , Transition Effect, and Duration in property panel.

**Property**

* Child : -
* Link  : -
* Scroll Animator : -
* Background Image : -
* Backend Ellipsis : -



Import
----------

.. image:: resource/widget/IUImport.png

.. thumbnail:: resource/capture_window/import.png


Import widget can import **Composition** .
If you want to use Composition, connect target Composition into Import widget.

**Property**

* Child : Invalid
* Link  : Valid
* Scroll Animator : Valid
* Background Image : Valid
* Backend Ellipsis : Invalid



Tweet Share Button
---------------------------------

.. image:: resource/widget/IUTweetButton.png

.. thumbnail:: resource/capture_window/twt_share.png

With Tweet Share Button widget, you can add **Share to Tweeter Button** in your project. (No Resize)

**Property**

* Child : Invalid
* Link  : Valid
* Scroll Animator : Valid
* Background Image : Valid
* Backend Ellipsis : Invalid



Facebook Like Button
-----------------------

.. image:: resource/widget/IUFBLike.png

.. thumbnail:: resource/capture_window/fb_like.png

With Facebook Like Button widget,
you can add **Share to Facebook Button** in your project. (No Resize)

**Property**

* Child : Invalid
* Link  : Valid
* Scroll Animator : Valid
* Background Image : Valid
* Backend Ellipsis : Invalid



Centered Box
--------------

.. image:: resource/widget/IUCenterBox.png

.. thumbnail:: resource/capture_window/center_box.png

Centered Box widget makes horizontal centered layout to Section.
Centered Box widget is added into section automatically,
but you can remove this widget. (No resize)

**Property**

* Child : Invalid
* Link  : Valid
* Scroll Animator : Valid
* Background Image : Valid
* Backend Ellipsis : Invalid



Progress Bar
-------------

.. image:: resource/widget/IUProgressBar.png

.. thumbnail:: resource/capture_window/progress_bar.png


Progress Bar widget displays a progress bar.
If you want draw certain status with bar elements, add this widget in your project.

**Property**

* Child : Invalid
* Link  : Valid
* Scroll Animator : Valid
* Background Image : Invalid
* Backend Ellipsis : Invalid



SVG (Scalable Vector Graphics)
----------------------------------

.. image:: resource/widget/IUSVG.png

.. thumbnail:: resource/capture_window/svg.png

SVG widget displays Scalable Vector Graphics.
You can select simple SVG form, or input custom :code:`<svg>` code whatever you want.

**Property**

* Child : Invalid
* Link  : Valid
* Scroll Animator : Valid
* Background Image : Invalid
* Backend Ellipsis : Invalid
