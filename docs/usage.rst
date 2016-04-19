Usage
=====

To compile and run

.. code-block:: bash

    cd ABAGAIL
    ant
    java -cp ABAGAIL.jar opt.test.XORTest
    java -cp ABAGAIL.jar opt.test.TravelingSalesmanTest
    

To generate javadoc documentation:

.. code-block:: bash

    ant javadoc


Note that for ant versions 1.9.3 or earlier, you need to remove

.. code-block:: bash

    additionalparam="subpackages"
    from the javadoc target tag.

To run the Abalone example

.. code-block:: bash

    java -cp ABAGAIL.jar opt.test.AbaloneTest

For some examples of how to use the library for your own projects look for the test packages, such as opt.test, and shared.test inside of the project source directory.
