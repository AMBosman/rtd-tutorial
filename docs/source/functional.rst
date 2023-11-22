Functional description of ITS-FMS Interface
=====

Introduction
------------
Within the ITS-FMS interface various use cases are supported. 
To clearly define what data fields need to be filled for specific use cases, each use case was assigned a, so called, ITSEventCode, see Table 1. 
These ITSEventCodes are also used in the Protobuf definition to identify what fields need to be filled for a specific use case, see also 3.3.2.

.. csv-table:: Table 1. Overvieew of supported use cases by ITSEventCode
   :header: "Number", "ITS Event Code", "Description Event"
   :widths: 15, 30, 30

   "Category 0", "Special messages", ""
   "000", "UNKNOWN_ITS_EVENT_CODE", "Unknown ITS event code"
   "001", "CHANGED_FREQUENCY_REQUEST", "Frequency requested to change to x Hz"
