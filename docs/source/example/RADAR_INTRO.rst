
Brief introduction of radar data
-----

.. list-table:: The radar name, variables and data format
   :widths: 25 25 25 25
   :header-rows: 1

   * - Radar name
     - Variables
     - file name
     - data format
   * - RCWF
     - -
     - yyyymmdd_HHMM_RCWF_VOL.^\d{3}.gz
     - NEXRED
   * - RCGI
     - dBuZ, dBZ, KDP, PhiDP, RhoHV, uPhiDP, V, W, ZDR
     - yyyymmddHHMMSS00$Variables.vol
     - Rainbow 5
   * - RCLY
     - dBuZ, dBZ, dBZv, KDP, PhiDP, RhoHV, SNR, uPhiDP, V, W, ZDR
     - yyyymmddHHMMSS00$Variables.vol
     - Rainbow 5
   * - RCCK, RCMK
     - dBuZ, dBZ, KDP, PhiDP, RhoHV, uKDP, uPhiDP, V, W, ZDR
     - yyyymmddHHMMSS00$Variables.vol
     - Rainbow 5
   * - RCMD, RCNT, RCSL
     - dBuZ, dBZ, KDP, PhiDP, RhoHV, SNR, SQI, uPhiDP, V, W, ZDR
     - yyyymmddHHMMSS00$Variables.vol
     - Rainbow 5
   * - RCCG, RCHL, RCKT
     - dBZ, V, W
     - yyyymmddHHMMSS00$Variables.vol
     - Rainbow 5


.. list-table:: Radar Processing data
   :widths: 33 33 33
   :header-rows: 1
   
   * - Categore
     - File name
     - Data format
   * - MOSAIC2D
     - COMPREF.yyyymmdd.HHMM.gz
     - self define
   * - MOSAIC3D
     - MREF3D21L.yyyymmdd.HHMM.gz
     - self define
   * - QPE1HR
     - CB_GC_PCP_1H_RAD.yyyymmdd.HHMM.gz
     - self define



The weather radar network in Taiwan (`Reference <https://journals.ametsoc.org/view/journals/bams/102/3/BAMS-D-20-0043.1.xml>`_)
.. figure:: ../image/twradar.jpg
   :width: 400
   :align: center




