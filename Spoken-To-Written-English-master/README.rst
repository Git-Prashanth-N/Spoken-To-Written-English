
=================
Spoken To Written
=================
This is a Python module which can that can convert a paragraph of spoken english to written english.

 For example, "two dollars" should be converted to $2. Abbreviations spoken as "C M" or "Triple A" should be written as "CM" and "AAA" respectively.

+++++++++++++
Installation:
+++++++++++++

  Please ensure that you have **updated pip3** to the latest version before installing spoken2written

  You can install the module using Python Package Index using the below command.

.. code-block:: python

   >>python3 setup.py install  



+++++
Usage:
+++++

**Correct one:**

.. code-block:: python
    
    	>>python3
	>>> from spoken2written import sp2wr
	>>> sp2wr.convert_sp_to_wr()

	[IN]:Enter Your paragraph of spoken english:
		C M

	[OUT]:The input Spoken English Paragraph: 

	 " C M"

	Converted Written English Paragraph: 

	 " CM"
	>>> 



