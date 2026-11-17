# Third-party notices

Handball Highlights Maker is built with the following open-source components. Each is
the property of its authors and is used under its own license. Thank you to all of them.

| Component | Used for | License |
|---|---|---|
| [Python](https://www.python.org/) | Runtime | PSF License |
| [PySide6 / Qt for Python](https://www.qt.io/qt-for-python) | User interface, video playback | LGPL-3.0 |
| [OpenCV (opencv-python-headless)](https://opencv.org/) | Reading video frames | Apache-2.0 |
| [RapidOCR (rapidocr-onnxruntime)](https://github.com/RapidAI/RapidOCR) | Reading the scoreboard | Apache-2.0 |
| [ONNX Runtime](https://onnxruntime.ai/) | Running the OCR model | MIT |
| [NumPy](https://numpy.org/) | Numeric processing | BSD-3-Clause |
| [imageio-ffmpeg](https://github.com/imageio/imageio-ffmpeg) | Provides the FFmpeg program | BSD-2-Clause |
| [FFmpeg](https://ffmpeg.org/) | Cutting, joining and encoding video | LGPL-2.1+ / GPL-2+ (depends on the build) |
| [PyInstaller](https://pyinstaller.org/) | Packaging the app | GPL-2.0 with a bootloader exception |
| [Inter font](https://rsms.me/inter/) | Used in the manual animations | SIL Open Font License 1.1 |

## Your rights for LGPL / GPL components

- **PySide6 / Qt (LGPL-3.0):** the Qt libraries ship as separate, replaceable files in the
  application folder. You may replace them with a modified version as the LGPL allows.
  Source code: <https://code.qt.io/> and <https://pypi.org/project/PySide6/>.
- **FFmpeg:** the bundled FFmpeg build may include GPL components (such as the x264
  encoder). The FFmpeg source code is available at <https://ffmpeg.org/download.html>
  and at <https://github.com/imageio/imageio-ffmpeg>.

Full license texts are included in the components' own packages and on their websites.
