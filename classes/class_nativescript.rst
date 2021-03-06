.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the NativeScript.xml source instead.
.. The source is found in doc/classes or modules/<name>/doc_classes.

.. _class_NativeScript:

NativeScript
============

**Inherits:** :ref:`Script<class_script>` **<** :ref:`Resource<class_resource>` **<** :ref:`Reference<class_reference>` **<** :ref:`Object<class_object>`

**Category:** Core

Brief Description
-----------------



Member Functions
----------------

+------------------------------+----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_string>`  | :ref:`get_class_documentation<class_NativeScript_get_class_documentation>` **(** **)** const                                           |
+------------------------------+----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_string>`  | :ref:`get_method_documentation<class_NativeScript_get_method_documentation>` **(** :ref:`String<class_string>` method **)** const      |
+------------------------------+----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_string>`  | :ref:`get_property_documentation<class_NativeScript_get_property_documentation>` **(** :ref:`String<class_string>` path **)** const    |
+------------------------------+----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`String<class_string>`  | :ref:`get_signal_documentation<class_NativeScript_get_signal_documentation>` **(** :ref:`String<class_string>` signal_name **)** const |
+------------------------------+----------------------------------------------------------------------------------------------------------------------------------------+
| :ref:`Object<class_object>`  | :ref:`new<class_NativeScript_new>` **(** **)** vararg                                                                                  |
+------------------------------+----------------------------------------------------------------------------------------------------------------------------------------+

Member Variables
----------------

  .. _class_NativeScript_class_name:

- :ref:`String<class_string>` **class_name**

  .. _class_NativeScript_library:

- :ref:`GDNativeLibrary<class_gdnativelibrary>` **library**

  .. _class_NativeScript_script_class_icon_path:

- :ref:`String<class_string>` **script_class_icon_path**

  .. _class_NativeScript_script_class_name:

- :ref:`String<class_string>` **script_class_name**


Member Function Description
---------------------------

.. _class_NativeScript_get_class_documentation:

- :ref:`String<class_string>` **get_class_documentation** **(** **)** const

Returns the documentation string that was previously set with ``godot_nativescript_set_class_documentation``.

.. _class_NativeScript_get_method_documentation:

- :ref:`String<class_string>` **get_method_documentation** **(** :ref:`String<class_string>` method **)** const

Returns the documentation string that was previously set with ``godot_nativescript_set_method_documentation``.

.. _class_NativeScript_get_property_documentation:

- :ref:`String<class_string>` **get_property_documentation** **(** :ref:`String<class_string>` path **)** const

Returns the documentation string that was previously set with ``godot_nativescript_set_property_documentation``.

.. _class_NativeScript_get_signal_documentation:

- :ref:`String<class_string>` **get_signal_documentation** **(** :ref:`String<class_string>` signal_name **)** const

Returns the documentation string that was previously set with ``godot_nativescript_set_signal_documentation``.

.. _class_NativeScript_new:

- :ref:`Object<class_object>` **new** **(** **)** vararg

Constructs a new object of the base type with a script of this type already attached.

*Note*: Any arguments passed to this function will be ignored and not passed to the native constructor function. This will change with in a future API extension.


