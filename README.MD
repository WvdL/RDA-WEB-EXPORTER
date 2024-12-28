# RDA-WEB-EXPORTER

A **single-page HTML/JavaScript** (partial) port of the [RDAExplorer](https://github.com/lysanntranvouez/RDAExplorer) application, intended to read and export data from RDA files. The original RDAExplorer is a Windows application that can read and save the RDA file format used in Anno 1404, 2070, 2205, and 1800.


![img.png](img.png)

## Why I Made This

I only tested this for **Anno 1404 History Edition**, running on **Wine on macOS**.  
This single-page web exporter was primarily created to suit my personal use case on a Mac environment, where running the original Windows-based RDAExplorer was annoying.

- Author: **Ward van der Linden**
- Project Name: **RDA-WEB-EXPORTER**

> **Important**  
> This project is not affiliated with Ubisoft.  
> Anno, Blue Byte, Ubisoft, and the Ubisoft logo are trademarks of Ubisoft Entertainment in the US and/or other countries.

---

## Features

- **Single-HTML File**: Contains all JavaScript/CSS needed to load RDA files in your browser.
- **Read/Export**: Provides a minimal GUI to open and extract contents from an RDA file.
- **Cross-Platform**: Should run on any modern browser with proper File API support. Tested on macOS (via Chrome/Firefox).

---

## Usage

1. **Download** the `RDA-WEB-EXPORTER.html` file.
2. **Open** it in a modern browser (Chrome, Firefox, Edge, Safari, etc.).
3. **Load** an RDA file from your local machine using the built-in interface.
4. **Export** or inspect the file’s contents as needed.

> **Disclaimer**: This has only been tested thoroughly on Anno 1404 History Edition files under Wine on macOS (Apple Silicon).  
> Results may vary with other Anno versions or environments. Use at your own risk!

---

## Acknowledgments

- **Deciphering Algorithm**:  
  The core algorithm for reading, decrypting, and processing RDA files is adapted from [RDAExplorer](https://github.com/lysanntranvouez/RDAExplorer).
- **Contributors to RDAExplorer**:
    - [@lysanntranvouez](https://github.com/lysanntranvouez)
    - [@FroggieFrog](https://github.com/FroggieFrog)

---

## License

This project is available under both **MIT** and **BSD 3-Clause** licenses, per the original RDAExplorer. See [LICENSE](LICENSE) for full details.

---

## Disclaimer

This software is **not** affiliated with Ubisoft. It is provided “as is” with **no warranty** of any kind. Please read the full license text for all disclaimers and terms.

**Enjoy exploring your RDA files!**