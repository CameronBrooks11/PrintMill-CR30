# PrintMill-CR30

My personal notes and docs on the Creality CR-30 PrintMill 45 degree, infinite Z-axis printer.

Look at these:

- https://docs.sainsmart.com/article/krirs6bq2o-creality-cr-30-3-dprint-mill-resources

## Setup

- First you have to assemble using [CR-30 PrintMill User Guide - PDF](https://img.staticdj.com/543cc0fea15932a8fb9414a116c87ec1.pdf?spm=..page_1996207.download_support_1.1)

- Then I used this video as reference for the bed levelling: [3DPrintMill aligning Y-axis stop switch , bed leveling and setting Y-offset. - YouTube](https://www.youtube.com/watch?v=3c2PW5GNZrE)

  - Note that in the video, the bed is leveled by fully lowering it using the thumbscrews for Z-level and skew adjustments, and then the Y stepping is used—with a shim—to fine-tune the level. This approach seems counterintuitive to me because the primary purpose of the adjustment screws is to offer two degrees of freedom: one to set the initial offset and another for later fine-tuning. By bottoming out the screws to drop the bed completely, any subsequent skew—say, if one corner sits higher—cannot be corrected using the screws. Instead, you’d have to raise them (a mechanical adjustment) and then reconfigure the software offset. It appears the method might be aimed at ensuring the nozzle never crashes into the belt or bed, but it sacrifices the entire purpose of having adjustable screws.

- Firmware is really easy, just download the zip, extract it, and copy the .bin file over to the SD card of the printer and then insert the SD while off then power on to update.

  - Download it here: [Downloads for CR-30 3D Printer - Creality](https://www.creality.com/pages/download-cr-30-3d-printer)
  - You dont need a video but I watched this: [CR-30 3DPrintMill Firmware Flash & Update CR-30 Creality 3D Printer - YouTube](https://www.youtube.com/watch?v=CpIbMpt8sbA)
  - I suggest doing this regardless since some older firmware versions will not allow you to set a negative offset which is required for the offset calibration with the shim

- CALIBRATION AND LEVELLING

- Now you need the slicer: [Software Downloads - Creality](https://www.creality.com/pages/download-software)

- For an example print object to test you can use [RepRap's Infinite-Z-Beam - GitHub](https://github.com/RepRapLtd/Infinite-Z-Beam/blob/main/Mechanics/STLs/beam.stl)
