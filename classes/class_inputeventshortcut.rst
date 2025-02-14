:github_url: hide

.. DO NOT EDIT THIS FILE!!!
.. Generated automatically from Godot engine sources.
.. Generator: https://github.com/godotengine/godot/tree/master/doc/tools/make_rst.py.
.. XML source: https://github.com/godotengine/godot/tree/master/doc/classes/InputEventShortcut.xml.

.. _class_InputEventShortcut:

InputEventShortcut
==================

**Inherits:** :ref:`InputEvent<class_InputEvent>` **<** :ref:`Resource<class_Resource>` **<** :ref:`RefCounted<class_RefCounted>` **<** :ref:`Object<class_Object>`

Represents a triggered keyboard :ref:`Shortcut<class_Shortcut>`.

.. rst-class:: classref-introduction-group

Description
-----------

InputEventShortcut is a special event that can be received in :ref:`Node._unhandled_key_input<class_Node_method__unhandled_key_input>`. It is typically sent by the editor's Command Palette to trigger actions, but can also be sent manually using :ref:`Viewport.push_input<class_Viewport_method_push_input>`.

.. rst-class:: classref-reftable-group

Properties
----------

.. table::
   :widths: auto

   +---------------------------------+-------------------------------------------------------------+
   | :ref:`Shortcut<class_Shortcut>` | :ref:`shortcut<class_InputEventShortcut_property_shortcut>` |
   +---------------------------------+-------------------------------------------------------------+

.. rst-class:: classref-section-separator

----

.. rst-class:: classref-descriptions-group

Property Descriptions
---------------------

.. _class_InputEventShortcut_property_shortcut:

.. rst-class:: classref-property

:ref:`Shortcut<class_Shortcut>` **shortcut**

.. rst-class:: classref-property-setget

- void **set_shortcut** **(** :ref:`Shortcut<class_Shortcut>` value **)**
- :ref:`Shortcut<class_Shortcut>` **get_shortcut** **(** **)**

The :ref:`Shortcut<class_Shortcut>` represented by this event. Its :ref:`Shortcut.matches_event<class_Shortcut_method_matches_event>` method will always return ``true`` for this event.

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
