:github_url: hide

.. DO NOT EDIT THIS FILE!!!
.. Generated automatically from Godot engine sources.
.. Generator: https://github.com/godotengine/godot/tree/master/doc/tools/make_rst.py.
.. XML source: https://github.com/godotengine/godot/tree/master/doc/classes/AnimationNodeAnimation.xml.

.. _class_AnimationNodeAnimation:

AnimationNodeAnimation
======================

**Inherits:** :ref:`AnimationRootNode<class_AnimationRootNode>` **<** :ref:`AnimationNode<class_AnimationNode>` **<** :ref:`Resource<class_Resource>` **<** :ref:`RefCounted<class_RefCounted>` **<** :ref:`Object<class_Object>`

An input animation for an :ref:`AnimationNodeBlendTree<class_AnimationNodeBlendTree>`.

.. rst-class:: classref-introduction-group

Description
-----------

A resource to add to an :ref:`AnimationNodeBlendTree<class_AnimationNodeBlendTree>`. Only has one output port using the :ref:`animation<class_AnimationNodeAnimation_property_animation>` property. Used as an input for :ref:`AnimationNode<class_AnimationNode>`\ s that blend animations together.

.. rst-class:: classref-introduction-group

Tutorials
---------

- :doc:`Using AnimationTree <../tutorials/animation/animation_tree>`

- `3D Platformer Demo <https://godotengine.org/asset-library/asset/125>`__

- `Third Person Shooter Demo <https://godotengine.org/asset-library/asset/678>`__

.. rst-class:: classref-reftable-group

Properties
----------

.. table::
   :widths: auto

   +-------------------------------------------------------+-------------------------------------------------------------------+---------+
   | :ref:`StringName<class_StringName>`                   | :ref:`animation<class_AnimationNodeAnimation_property_animation>` | ``&""`` |
   +-------------------------------------------------------+-------------------------------------------------------------------+---------+
   | :ref:`PlayMode<enum_AnimationNodeAnimation_PlayMode>` | :ref:`play_mode<class_AnimationNodeAnimation_property_play_mode>` | ``0``   |
   +-------------------------------------------------------+-------------------------------------------------------------------+---------+

.. rst-class:: classref-section-separator

----

.. rst-class:: classref-descriptions-group

Enumerations
------------

.. _enum_AnimationNodeAnimation_PlayMode:

.. rst-class:: classref-enumeration

enum **PlayMode**:

.. _class_AnimationNodeAnimation_constant_PLAY_MODE_FORWARD:

.. rst-class:: classref-enumeration-constant

:ref:`PlayMode<enum_AnimationNodeAnimation_PlayMode>` **PLAY_MODE_FORWARD** = ``0``

Plays animation in forward direction.

.. _class_AnimationNodeAnimation_constant_PLAY_MODE_BACKWARD:

.. rst-class:: classref-enumeration-constant

:ref:`PlayMode<enum_AnimationNodeAnimation_PlayMode>` **PLAY_MODE_BACKWARD** = ``1``

Plays animation in backward direction.

.. rst-class:: classref-section-separator

----

.. rst-class:: classref-descriptions-group

Property Descriptions
---------------------

.. _class_AnimationNodeAnimation_property_animation:

.. rst-class:: classref-property

:ref:`StringName<class_StringName>` **animation** = ``&""``

.. rst-class:: classref-property-setget

- void **set_animation** **(** :ref:`StringName<class_StringName>` value **)**
- :ref:`StringName<class_StringName>` **get_animation** **(** **)**

Animation to use as an output. It is one of the animations provided by :ref:`AnimationTree.anim_player<class_AnimationTree_property_anim_player>`.

.. rst-class:: classref-item-separator

----

.. _class_AnimationNodeAnimation_property_play_mode:

.. rst-class:: classref-property

:ref:`PlayMode<enum_AnimationNodeAnimation_PlayMode>` **play_mode** = ``0``

.. rst-class:: classref-property-setget

- void **set_play_mode** **(** :ref:`PlayMode<enum_AnimationNodeAnimation_PlayMode>` value **)**
- :ref:`PlayMode<enum_AnimationNodeAnimation_PlayMode>` **get_play_mode** **(** **)**

Determines the playback direction of the animation.

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
