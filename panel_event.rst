.. _Scroll Animator : #id1
.. _Variable : #id2





Event Panel
====================

When you run **View > Event (⇧⌘E)** menu, Event Panel will be shown. You can add events like `Scroll Animator`_ or `Variable`_ .



----------

.. image:: resource/iu_manual_panel_event_01scr.png

Scroll Animator
---------------

Adds Scroll Animator to animate widget by scrolling. When target widget closing to middle of browser, selected value will transform from before to after.


* ``X-Position`` : Adds Scroll Animator to X-Position.
* ``Y-Position`` : Adds Scroll Animator to Y-Position.
* ``Opacity`` : Adds Scroll Animator to Opacity,



----------

.. image:: resource/iu_manual_panel_event_02var.png

Variable
----------------

Adds Variable to selected widget.


* ``Variable Name`` : Shows Variable list in your project.

* ``Triggered Widget`` : Shows Triggered widget list according to selected Variable.

* ``New Variable Name`` : Adds new Variable name.

* ``Value Count`` : Set Default & Maximum value to variable.

* ``Trigger Action`` : Set Trigger Action to selected widget.


----------

.. image:: resource/iu_manual_panel_event_03receiver.png

Receiver
-------------

Adds Receiver Event to selected widget. When **Equation** returns True, Receiver Event will be shown.


* ``Variable Name`` : Shows Variable list that have Receiver Event.

* ``Receiver Widget`` : Shows Receiver Widget list according to selected Variable.

* ``Equation`` : Set Equation case. (e.g. SampleVariable==1)

* ``Scroll Location`` : Set Equation range about scroll position.

* ``Animation Effect`` : Set Animation Effect when Receiver Event be run.

* ``Duration`` : Set Duration for Receiver Event.




----------

.. image:: resource/iu_manual_panel_event_04link.png

Link
-------------

Adds Link Event to selected widget. Widget can have only One Link.


* ``None`` : No link. (Default value)

* ``Page`` : Adds page or div link.

* ``URL`` : Adds URL link.

* ``Panel`` : Adds link event that calls Panel.

* ``Popup`` : Adds link event that calls Popup.


