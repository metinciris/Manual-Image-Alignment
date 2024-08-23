# Manual Image Alignment Tool

This tool allows for the manual alignment of two images, specifically designed for pathology slide images. The tool provides fine-tuning capabilities for precise alignment and allows for adjustments such as rotation, transparency, and zoom. Additionally, a feature to set a new rotation center is included.

## Features
- **Manual Alignment:** Adjust the alignment of two images with fine-tuning options.
- **Set Rotation Center:** Easily set a new rotation center for more accurate alignment.
- **Save Settings:** Save the alignment settings to a file for future use.
- **Zoom and Transparency:** Control the zoom level and transparency of the images for better visualization.

## How to Use
1. **Load Images:** Load the two images you want to align.
2. **Manual Alignment:** Use the sliders and buttons to adjust the alignment. Fine-tune the alignment using the fine-tune mode.
3. **Set Rotation Center:** Click on the "Set Rotation Center" button to set a new center of rotation.
4. **Save Settings:** Save your alignment settings by clicking on the "Save" button. The settings will be saved in the same directory as `manual_align.txt`.

## Future Enhancements
- **Automatic Fine-Tuning:** Future versions may include an automatic fine-tuning feature to correct minor misalignments and reduce white spaces between images.
- **Shadow-Based Alignment:** Implementing a shadow-based alignment feature to better align image contours.

## Requirements
- **Python 3.x**
- **Pillow**
- **Tkinter**

## Installation
Install the required Python packages using pip:

```bash
pip install pillow
