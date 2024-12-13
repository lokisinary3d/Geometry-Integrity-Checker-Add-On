# Geometry Integrity Checker Add-On

Table of Contents
- [Installation](#installation)
- [Features](#features)
  - [Duplicate Detection](#duplicate-detection)
  - [Automated Scanning](#automated-scanning)
  - [Detailed Scan Results](#detailed-scan-results)
  - [Reset to Defaults](#reset-to-defaults)
- [Usage](#usage)
  - [Scanning for Duplicates](#scanning-for-duplicates)
  - [Automating Scans](#automating-scans)
  - [Viewing and Managing Results](#viewing-and-managing-results)
- [Version History](#version-history)
- [Frequently Asked Questions (FAQ)](#frequently-asked-questions-faq)
- [Troubleshooting](#troubleshooting)
- [Contribute](#contribute)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Support](#support)

---

## Installation

Follow these steps to install the Geometry Integrity Checker Add-On:

1. Download the ZIP file containing the add-on.
2. Open Blender and go to **Edit > Preferences**.
3. In the Preferences window, go to the **Add-ons** tab and click **Install...**.
4. Select the downloaded ZIP file and click **Install Add-on**.
5. Search for "Geometry Integrity Checker" in the Add-ons tab and enable it by checking the box next to its name.
6. The add-on will appear in the **N-Panel** under the "Geometry Integrity" tab. Press `N` to toggle the N-Panel if it isn't visible.
7. If it is showing an error then go to this location C:\Users\ your use name\AppData\Roaming\Blender Foundation\Blender\3.6(or other version)\scripts\addons\ GeometryIntegrityChecker-v1.1(or other version)
8. Remane the GeometryIntegrityChecker-v1.1(or other version) as GeometryIntegrityChecker
---

## Features

### Duplicate Detection

- Detect duplicate or near-duplicate vertices, edges, and faces across multiple mesh objects.
- Includes customizable thresholds for near-duplicate detection.
- Supports both exact and approximate detection for robust results.

### Automated Scanning

- Automate scans at user-defined intervals.
- Enable or disable automated scans with a simple toggle.
- Adjust the scan interval (in seconds) for precise control.

### Detailed Scan Results

- Displays results for each scanned object, including:
  - Number of duplicate vertices, edges, and faces.
- Expand and collapse individual results for easy navigation.

### Reset to Defaults

- Reset all settings and results to their default state.
- Clear scan history and restore original preferences with a single click.

---

## Usage

### Scanning for Duplicates

1. Open Blender and load your scene.
2. Select the objects you want to scan in the 3D Viewport.
3. Open the **Geometry Integrity Checker** panel from the N-Panel.
4. Adjust the scan threshold or enable/disable specific detection types (e.g., duplicates or near-duplicates).
5. Click the **Scan Mesh** button to start scanning.
6. Review the results in the panel, with expandable/collapsible entries for each object.

### Automating Scans

1. Open the **Geometry Integrity Checker** panel.
2. Enable the **Automate Scans** toggle to start automated scanning.
3. Adjust the **Interval (Seconds)** property to set the time between scans.
4. The add-on will continuously scan selected objects at the defined interval.

### Viewing and Managing Results

- Expand or collapse results for each object to view detailed information.
- Use the **Select Duplicates** button to highlight duplicates in the 3D Viewport.
- Remove duplicates automatically with the **Remove Duplicates** button.

---

## Version History

### Version 1.0
- Added expandable and collapsible scan results.
- Improved automated scanning with persistent timer support.
- Enhanced UI for better clarity and usability.
- Introduced automated scanning with user-defined intervals.
- Added reset functionality to restore default settings.
- Initial release with duplicate and near-duplicate detection for vertices, edges, and faces.

---

## Frequently Asked Questions (FAQ)

1. **Can I use this add-on with older versions of Blender?**
   - The add-on is compatible with Blender 4.3.0 and newer versions.

2. **What happens if I stop an automated scan?**
   - Automated scans will cease immediately, but any existing results will remain visible.

3. **Does the add-on support custom thresholds for near-duplicates?**
   - Yes, you can adjust the threshold for near-duplicate detection in the panel.

4. **How do I reset all settings and results?**
   - Use the **Reset** button at the top of the panel to restore default settings.

5. **Are there plans for more features?**
   - Yes! We welcome feedback and feature requests via our [GitHub repository](https://github.com/lokisinary3d/Geometry-Integrity-Checker-Add-On).

---

## Troubleshooting

1. **The add-on is not visible in the N-Panel.**
   - Press `N` to toggle the N-Panel visibility.
   - Ensure the add-on is enabled in **Preferences > Add-ons**.

2. **Automated scans aren't working.**
   - Ensure the **Automate Scans** toggle is enabled.
   - Check that the scan interval is set to a reasonable value.

3. **Scan results are incomplete or incorrect.**
   - Verify that the objects you want to scan are selected in the 3D Viewport.
   - Adjust the threshold for near-duplicates if needed.

---

## Contribute

We welcome contributions! If you’d like to improve the add-on or report issues:

- Visit our [GitHub repository](https://github.com/lokisinary3d/Geometry-Integrity-Checker-Add-On).
- Submit bug reports or feature requests.
- Contribute code via pull requests.

---

## License

The Geometry Integrity Checker Add-On is open-source software licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

This add-on was made possible thanks to the support and feedback from the Blender community.

---

## Support

For technical support or inquiries, contact us at [lokisinary3d@gmail.com](mailto:lokisinary3d@gmail.com).

---

Happy Blending! 🎨

--- 
