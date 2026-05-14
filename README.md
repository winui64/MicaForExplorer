<h3 align=center><u>Efficient & User-Oriented</u> software used to apply Mica, & Acrylic effects to Windows Explorer.</h3>
<h2 align=center>Overview & Information</h2>

> **Notice:** This software is provided "as is" and without warranty of any kind. Use at your own risk  
> **Support:** This software is actively developed for use with Windows 10, & 11

### Prerequisites
- **Python 3.12+** ([python.org](https://www.python.org/))
- **pip** (comes with Python)
- **PyQt6** and **PyInstaller**

### Steps
1. **Clone the Repository**
   ```sh
   git clone https://github.com/DRKCTRLDEV/Mica4U.git
   cd Mica4U
   ```
2. **Install Dependencies**
   ```sh
   pip install -r requirements.txt
   # Or manually:
   pip install PyQt6 PyInstaller
   ```
3. **Build the Executable**
   ```sh
   ./build.ps1
   # Or manually:
   pyinstaller build/Mica4U.spec
   ```
   The executable(s) will be in `build/output/`.
   > **Versioning:** You can specify a version as an argument: `./build.ps1 x.x.x`

4. **Run the Application**
   For development, launch `main.py`:
     ```sh
     python main.py
     ```
     > **Note:** To use in this form, you must run as administrator and have a `portable.ini` file in the same directory. You can also build the portable version and substitute `Mica4U.exe` with `main.py`, but this will not auto-elevate.
   Or run the built executable from `build/output/`.

<h2 align=center>License & Credits</h2>

- Licensed under [LGPL v3](https://www.gnu.org/licenses/lgpl-3.0)
- Constructed with [Python 3.12.0](https://www.python.org/), [PyQt6 6.9.0](https://pypi.org/project/PyQt6/), [PyInstaller 6.13.0](https://pypi.org/project/PyInstaller/), & [InnoSetup 6.4.3](https://jrsoftware.org/)
- SVG icons provided by [FontAwesome](https://fontawesome.com)
- Core XAML theming forked from [Maplespe](https://github.com/Maplespe)/[ExplorerBlurMica](https://github.com/Maplespe/ExplorerBlurMica) Project
- GUI & Automation coded by yours truly, [𝓓𝓡𝓚](https://github.com/DRKCTRLDEV)
