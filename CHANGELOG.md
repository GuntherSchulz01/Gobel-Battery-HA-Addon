# Changelog


---------------

## 1.9.28

-  Roll back generate_bms_request and associated Date Time and Capacity Parsing.


------------------------------

## 1.9.27

-   Fixed Date Time and Capacity Parsing to accomodate generate_bms_request.


---------------

## 1.9.26

-   Fixed generate_bms_request.


---------------

## 1.9.25

-   Fixed Date Time Parsing.


------------------------------

## 1.9.24

-   Fixed Date Time and Capacity Parsing.


---------------

## 1.9.23

-   Fixed Capacity Parsing.


---------------

## 1.9.22

-   Fixed Date Time and Capacity Parsing.


---------------

## 1.9.21

-   GS made many fixes.


---------------

## 1.9.20

-   Add JK BMS RS485 support.
-   Fix Energy Discharged/Charged bug.


---------------

## 1.9.0

-   Auto reconnection after connection lost.
-   Add index of max/min cell voltage.
-   Modify Protoss PW10 / Waveshare manual, change 'Flow Control Settings' to 'Flow Control', 'Software Flow Control' to 'OFF'.


---------------

## 1.8.2

-   Fix temperature unit error.
-   Fix max/min voltage unit error.
-   Add voltage difference value.
-   Change data reading timeout to 3 seconds.

---------------


## 1.8.0

-   Value precision of energy charged/discharged is changed to 5.

---------------


## 1.7.8

-   TDT BMS bug fix.

---------------


## 1.7

-   fix RS232 multiple packs bug.
    for Pace BMS, use PACE_LV (latest version protocol) by default, if it does not work, try PACE_LV_V1.
-   add max/min cell voltage for whole system and each pack.
-   add TDT BMS support.

---------------

