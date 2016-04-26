# Blender-2-G'MIC

B2G is a Python script that allows you to access G'MIC's image processing features from within the Blender Video Sequence Editor (VSE). With the script, you can creatively filter single images, image sequences, and movie files.

This is experimental Alpha release software likely to contain bugs that might cause Blender and/or G'MIC to malfunction. It also makes use of Windows/Linux system features that may encounter difficulties. It is provided without a warranty of any kind (see GPL software license included with the script).

While the code should recognize whether it's being used on Linux or Windows, when you start using the blend file on one system, it's best to keep it there rather than trying to treat it as totally portable. File paths, image formats and codec issues all come into play. Issues that can rear their head are pathnames and spaces in file/folder names. Best not to have spaces. Blender can employ an internal "Relative Path" notation that will prevent the B2G from working well. Relative paths can be turned off permanently in the Users Preferences window, or, more simply, you can select "Make All Paths Absolute" from the File Menu/External Data to ensure images are referenced so G'MIC can find them.

**PREREQUISITES**

To use Blender-2-G'MIC you will need:

*  Blender 2.76 or 2.77

      https://www.blender.org/download/
      
*  The G'MIC software installed and added to your System path, or alternatively, the standalone version.       

      http://gmic.eu/download.shtml







Overview of script features at YouTube:

**1. Creative Imagery with Blender-2-G'MIC**

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/4Q78OPmbn3o/0.jpg)](https://www.youtube.com/watch?v=4Q78OPmbn3o)


**2. Blender-2-G'MIC Feature Update**

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/p1twxAsLb6o/0.jpg)](https://www.youtube.com/watch?v=p1twxAsLb6o)



Details on how to enable the link between Blender and G'MIC and general usage info are given in the following video.

**3. Initial Settings & Use**

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/TSzoEXAV1zs/0.jpg)](https://www.youtube.com/watch?v=TSzoEXAV1zs)
