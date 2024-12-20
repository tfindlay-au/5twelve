# 5 Twelve

This project is a simple power adaptor - it draws 5v from the USB micro B port and provides 12v via the 10-pin header.

### Design

This board uses the minimum components and tried to standardise on 0603 packages

|Part number        |Description        |
|-------------------|-------------------|
|PAM2423            |DC-DC Converter    |
|SDFL1608S6R8MTF    |Sunlord Inductor   |
|TSW-105-23-F-D-010 |2x5 pin header     |
|USB3140-30-0230-1-C|USB Micro B port   |
|SS34-E3/9AT        |Circuit protection |
|VLMW1300-GS08      |LED indicator      |

### Safety
The design uses a simple Shottky diode to protect the DC-DC converter

The Feedback loop (U1, pin2) may not need to be connected as this is a fixed voltage output.
