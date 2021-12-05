# gpsd-gpscap
[PATCH] Add GlobalSat MR-350P-S4 to compatibility list

This is a patch submission for [gpsd/gpsd](https://gitlab.com/gpsd/gpsd).  For small projects not requiring a pull request, or where maintainers prefer e-mail patch submissions, I keep copies here for reference/download.

- File: ./www/gpscap.ini
- Submission Date: 2020-11-28
- Commit Date: 2020-12-05

Summary: Addition to [gpsd Hardware](https://gpsd.gitlab.io/gpsd/hardware.html) documentation page for [GlobalSat MR-350P](https://web.archive.org/web/20211030130843/https://www.globalsat.com.tw/en/product-199953/GPS-Receiver-MR-350S4.html) RS-232 GPS device. Device was tested successfully with [gpsd](https://gpsd.gitlab.io/gpsd/) and [chrony](https://chrony.tuxfamily.org/) using [KPPS](https://www.kernel.org/doc/html/latest/driver-api/pps.html) latching; PPS output was successfully captured using custom-fabricated cable (see patch content for more information). NOTE: Firmware bug discovered that prevents 1PPS output on some units (reference file F-GPS-4R-1402051.pd2 in repo for Timer_Init1PPSOut_Patch. Vendor firmware flashing tool available from the [Internet Archive](https://archive.org/details/f-gps-4-r-1402051).
