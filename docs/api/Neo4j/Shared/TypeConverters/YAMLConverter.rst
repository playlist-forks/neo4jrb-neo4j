YAMLConverter
=============



Converts hash to/from YAML


.. toctree::
   :maxdepth: 3
   :titlesonly:


   

   

   

   




Constants
---------





Files
-----



  * `lib/neo4j/shared/type_converters.rb:98 <https://github.com/neo4jrb/neo4j/blob/master/lib/neo4j/shared/type_converters.rb#L98>`_





Methods
-------



.. _`Neo4j/Shared/TypeConverters/YAMLConverter.convert_type`:

**.convert_type**
  

  .. hidden-code-block:: ruby

     def convert_type
       Hash
     end



.. _`Neo4j/Shared/TypeConverters/YAMLConverter.db_type`:

**.db_type**
  

  .. hidden-code-block:: ruby

     def db_type
       String
     end



.. _`Neo4j/Shared/TypeConverters/YAMLConverter.to_db`:

**.to_db**
  

  .. hidden-code-block:: ruby

     def to_db(value)
       Psych.dump(value)
     end



.. _`Neo4j/Shared/TypeConverters/YAMLConverter.to_ruby`:

**.to_ruby**
  

  .. hidden-code-block:: ruby

     def to_ruby(value)
       Psych.load(value)
     end





