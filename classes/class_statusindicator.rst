:github_url: hide

.. DO NOT EDIT THIS FILE!!!
.. Generated automatically from Godot engine sources.
.. Generator: https://github.com/godotengine/godot/tree/master/doc/tools/make_rst.py.
.. XML source: https://github.com/godotengine/godot/tree/master/doc/classes/StatusIndicator.xml.

.. _class_StatusIndicator:

StatusIndicator
===============

**Inherits:** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

Application status indicator (aka notification area icon).

\ **Note:** Status indicator is implemented on macOS and Windows.

.. rst-class:: classref-reftable-group

Properties
----------

.. table::
   :widths: auto

   +-----------------------------+--------------------------------------------------------+----------+
   | :ref:`Image<class_Image>`   | :ref:`icon<class_StatusIndicator_property_icon>`       |          |
   +-----------------------------+--------------------------------------------------------+----------+
   | :ref:`String<class_String>` | :ref:`tooltip<class_StatusIndicator_property_tooltip>` | ``""``   |
   +-----------------------------+--------------------------------------------------------+----------+
   | :ref:`bool<class_bool>`     | :ref:`visible<class_StatusIndicator_property_visible>` | ``true`` |
   +-----------------------------+--------------------------------------------------------+----------+

.. rst-class:: classref-section-separator

----

.. rst-class:: classref-descriptions-group

Signals
-------

.. _class_StatusIndicator_signal_pressed:

.. rst-class:: classref-signal

**pressed** **(** :ref:`int<class_int>` mouse_button, :ref:`Vector2i<class_Vector2i>` position **)**

Emitted when the status indicator is pressed.

.. rst-class:: classref-section-separator

----

.. rst-class:: classref-descriptions-group

Property Descriptions
---------------------

.. _class_StatusIndicator_property_icon:

.. rst-class:: classref-property

:ref:`Image<class_Image>` **icon**

.. rst-class:: classref-property-setget

- void **set_icon** **(** :ref:`Image<class_Image>` value **)**
- :ref:`Image<class_Image>` **get_icon** **(** **)**

Status indicator icon.

.. rst-class:: classref-item-separator

----

.. _class_StatusIndicator_property_tooltip:

.. rst-class:: classref-property

:ref:`String<class_String>` **tooltip** = ``""``

.. rst-class:: classref-property-setget

- void **set_tooltip** **(** :ref:`String<class_String>` value **)**
- :ref:`String<class_String>` **get_tooltip** **(** **)**

Status indicator tooltip.

.. rst-class:: classref-item-separator

----

.. _class_StatusIndicator_property_visible:

.. rst-class:: classref-property

:ref:`bool<class_bool>` **visible** = ``true``

.. rst-class:: classref-property-setget

- void **set_visible** **(** :ref:`bool<class_bool>` value **)**
- :ref:`bool<class_bool>` **is_visible** **(** **)**

If ``true``, the status indicator is visible.

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
.. |bitfield| replace:: :abbr:`BitField (This value is an integer composed as a bitmask of the following flags.)`
