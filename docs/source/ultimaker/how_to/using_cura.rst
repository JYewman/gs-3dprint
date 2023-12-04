================================
💻 Using Ultimaker Cura
================================

This comprehensive guide covers the use of Ultimaker Cura software with the Ultimaker 3 Extended.

.. note::

   Ultimaker Cura is an advanced 3D printing software interface, offering extensive control over printer settings and print previews.

Introduction
------------

Ultimaker Cura is a state-of-the-art 3D printing software that transforms your 3D models into print-ready G-code. It provides an array of settings for material, quality, and custom print preferences, suitable for Ultimaker 3 Extended printers.

Installation and Setup
----------------------

1. **Download and Install Ultimaker Cura**:
   - Download the latest version of Cura from the `Ultimaker website <https://ultimaker.com/software/ultimaker-cura>`_.
   - Follow the provided instructions to install it on your computer.

2. **Adding Your Printer**:
   - Open Ultimaker Cura.
   - Navigate to 'Settings' > 'Printer' > 'Add Printer'.
   - Choose 'Ultimaker 3 Extended' from the list of printers.

3. **Setting Up a Network Printer**:
   - Ensure your Ultimaker 3 Extended is connected to the same network as your computer.
   - In Cura, go to 'Settings' > 'Printer' > 'Manage Printers'.
   - Click 'Add' and select the networked printer from the discovered printers list.

Preparing Your Model for Printing
---------------------------------

1. **Importing an STL File**:
   - Click 'File' > 'Open File(s)' or use the 'Open File' icon to import your STL file.
   - Your model will appear on the virtual print bed.

2. **Adjusting the Model**:
   - Use the tools on the left to move, scale, or rotate your model.

3. **Choosing Material and Print Settings**:
   - Select the material type from the material dropdown. Ultimaker Cura supports various materials like PLA, ABS, PETG, Nylon, and more.
   - Each material has specific properties and requires different printing temperatures and speeds.
   - For beginners, it's recommended to start with PLA due to its ease of use.
   - Choose a pre-configured profile for print quality. For instance, 'High' for detailed prints, 'Normal' for standard prints, and 'Low' for draft prints.
   - Each quality setting adjusts layer height, print speed, and infill density to balance between print speed and quality.

4. **Adjusting Advanced Settings**:
   - In 'Custom' mode, you can fine-tune settings like:
     - **Print Temperature**: Adjust based on material. PLA generally prints at around 190-220°C, while ABS requires higher temperatures.
     - **Bed Temperature**: Critical for print adhesion. PLA works well at around 50-60°C, whereas ABS might need 80-110°C.
     - **Layer Height**: Smaller heights for high-quality prints, larger for faster prints. Common settings range from 0.1mm (high quality) to 0.3mm (low quality).
     - **Print Speed**: Faster speeds can reduce print time but might reduce quality. Adjust based on printer's capability and the complexity of the print.
     - **Infill**: Determines the density of the inner part of the print. Higher infill percentage for stronger prints, lower for faster and less material usage.
   - Experiment with these settings for specific needs, balancing between print quality, strength, and printing time.

Slicing and Printing
--------------------

1. **Slicing Your Model**:
   - Click 'Slice' to convert your model into G-code.

2. **Saving or Sending the File**:
   - Save the G-code to a USB drive or send it directly to your printer via network.

3. **Starting the Print**:
   - Use the printer's interface to initiate the printing process.

Post-Processing and Maintenance
-------------------------------

1. **Post-Printing Steps**:
   - Let the print bed cool down before removing the print.
   - Remove any supports or brims used during printing.

2. **Printer Maintenance**:
   - Regularly clean the print bed and nozzle.
   - Check for firmware updates through Cura.

Troubleshooting and Support
---------------------------

- **Print Quality Issues**: Consult the `Ultimaker Cura user guide <https://ultimaker.com/learn/ultimaker-cura-user-manual>`_ and the Ultimaker community forums for troubleshooting.
- **Software Issues**: Make sure you are using the most recent version of Ultimaker Cura.

Conclusion
----------

Mastering Ultimaker Cura unlocks the full potential of your Ultimaker 3 Extended, allowing for highly customized and quality prints.

Additional Resources
--------------------

- `Ultimaker Cura User Manual <https://ultimaker.com/learn/ultimaker-cura-user-manual>`_
- `Ultimaker Community Forums <https://community.ultimaker.com/>`_
- `Ultimaker Material Profiles <https://ultimaker.com/materials>`_
