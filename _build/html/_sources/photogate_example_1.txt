.. _lab1_label:



Freefall - calculating *g*
===================================


Equation for calculating acceleration due to gravity is:


.. math:: 

   g = \frac{v \mathrm{2} - v \mathrm{1}}{\mathrm{\Delta t}} 


where :math:`g` is the acceleration due to gravity, :math:`v1` is the velocity in gate 1, :math:`v2` is the velocity in gate 2 and 
:math:`\Delta t` is the time between gates.

    



1) Setting up the photogates
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
On a single support stand [#f1]_, place the two photogates a distance apart. Make sure that the top (first) photogate is connected to the Photogate 1 position on the Arduino Shield. 


.. figure:: _static/photogates_3.png
   :align:  center

   
2) Software
^^^^^^^^^^^^^^^^^^^^^
Set-up the software as described in the previous section :ref:`software_label`.

   
   
   
3) Sample data
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
In the example shown below, we used a 0.5" wide metal block (12.7mm). Hold the object slightly above the first photogate and release to drop it between the two gates. Save data for analysis. 

.. figure:: _static/wbd_drop.png
   :align:  center

4) Data analysis
^^^^^^^^^^^^^^^^^^^^^^^^^^^

* From time in gates, calculate velocity, :math:`v`, of falling object: 

     * :math:`v` = object length (m) / time in gate (s)
     
     * :math:`v1`  = 0.0127/0.00940 = 1.351 :math:`\mathrm{m}/\mathrm{s}`
     * :math:`v2`  = 0.0127/0.00406 = 3.128 :math:`\mathrm{m}/\mathrm{s}`

* From equation, *g* is given by:
  
.. math::

   g  \approx  \frac{3.128-1.351}{0.17982} \approx 9.88 \mathrm{m}/\mathrm{s}



     
     
.. rubric:: Footnotes

.. [#f1] Additional equipment from Carolina Biologicals. Support Stand $15.50, Part # 707146 and Clamp Holder, $9.90, Part # 707310
