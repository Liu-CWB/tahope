Brief introduction of radar data
=================================

During TAHOPE, CWB supply raw radar data (Table 1) and processed radar data (Table 2).

Fig 1. shows the weather radar network in Taiwan.

For more information about the weather radar network in Taiwna, an article `An Operational Multi-Radar Multi-Sensor QPE System in Taiwan <https://journals.ametsoc.org/view/journals/bams/102/3/BAMS-D-20-0043.1.xml>`_ is highly recommanded to read in detail. 


.. figure:: ../image/twradar.jpg
   :width: 400
   :align: center

   Fig 1. The weather radar network in Taiwan (`Reference <https://journals.ametsoc.org/view/journals/bams/102/3/BAMS-D-20-0043.1.xml>`_)



++++++++++++++++++++++++++++++++++++++++++++++++

Table 1. Radara name, variables and data format


.. list-table::
   :widths: auto
   :header-rows: 1

   * - Radar name
     - Wavelength and polarimetry
     - Variables
     - File naming convention
     - Data format
     - Frequecy (Minute)
   * - RCWF
     - S dual
     - -
     - yyyymmdd_HHMM_RCWF_VOL.^\d{3}.gz
     - NEXRED
     - < 10 
   * - RCGI
     - C dual
     - dBuZ, dBZ, KDP, PhiDP, RhoHV, uPhiDP, V, W, ZDR
     - yyyymmddHHMMSS00$Variables.vol
     - Rainbow5
     - < 10
   * - RCLY
     - C dual
     - dBuZ, dBZ, dBZv, KDP, PhiDP, RhoHV, SNR, uPhiDP, V, W, ZDR
     - yyyymmddHHMMSS00$Variables.vol
     - Rainbow5
     - < 10
   * - RCCK, RCMK
     - C dual
     - dBuZ, dBZ, KDP, PhiDP, RhoHV, uKDP, uPhiDP, V, W, ZDR
     - yyyymmddHHMMSS00$Variables.vol
     - Rainbow5
     - < 10
   * - RCMD, RCNT, RCSL
     - C dual
     - dBuZ, dBZ, KDP, PhiDP, RhoHV, SNR, SQI, uPhiDP, V, W, ZDR
     - yyyymmddHHMMSS00$Variables.vol
     - Rainbow5
     - < 10
   * - RCCG, RCHL, RCKT
     - S single
     - dBZ, V, W
     - yyyymmddHHMMSS00$Variables.vol
     - Rainbow5
     - < 10


+++++++++++++++++++++++++

Table 2. Processed data

.. list-table:: 
   :widths: 33 33 33
   :header-rows: 1
   
   * - Categorey
     - File naming convention
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






