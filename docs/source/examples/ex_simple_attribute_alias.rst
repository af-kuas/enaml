..
  NOTE: This RST file was generated by `make examples`.
  Do not edit it directly.
  See docs/source/examples/example_doc_generator.py

Simple Attribute Alias Example
===============================================================================

An example of using an Enaml alias to expose an internal attribute.

This example is similar to 'simple_widget_alias.enaml', but it shows
how the developer can exert more control over a widget by exposing
individual attributes instead of entire widgets.

.. TIP:: To see this example in action, download it from
 :download:`simple_attribute_alias <../../../examples/aliases/simple_attribute_alias.enaml>`
 and run::

   $ enaml-run simple_attribute_alias.enaml


Screenshot
-------------------------------------------------------------------------------

.. image:: images/ex_simple_attribute_alias.png

Example Enaml Code
-------------------------------------------------------------------------------
.. literalinclude:: ../../../examples/aliases/simple_attribute_alias.enaml
    :language: enaml
