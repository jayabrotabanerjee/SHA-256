# SHA Playground

**Author:** Jayabrota Banerjee  
**Course:** CSBS, 3rd Year  
**Roll Number:** 2  

## Overview
SHA Playground is a Python-based desktop application designed to explore SHA-256 hashing. It provides tools for hashing text and files, verifying hashes, cracking simple passwords, and visualizing cryptographic processes. The application features a user-friendly GUI built with Tkinter.

## Features
- **Text Hashing:** Generate SHA-256 hashes from text input.
- **File Hashing:** Compute SHA-256 hashes of files.
- **Hash Matching:** Verify if a text matches a given hash.
- **Hash Cracking:** Simple brute-force cracking of SHA-256 hashes.
- **Visualization:** (Planned) Visual representation of SHA-256 and cryptographic processes.
- **Localization:** Multi-language support (currently English).

## Directory Structure
sha256_playground/
├── core/                # Core functionality
│   ├── hash_utils.py    # Hashing utilities
│   ├── password_cracker.py # Password cracking logic
│   ├── file_handler.py  # File operations
├── ui/                  # User interface components
│   ├── app.py           # Main application window
│   ├── home_page.py     # Home page
│   ├── text_hashing_page.py # Text hashing UI
│   ├── file_hashing_page.py # File hashing UI
│   ├── hash_matching_page.py # Hash matching UI
│   ├── hash_cracking_page.py # Hash cracking UI
│   ├── visualization_page.py # Visualization UI
│   ├── styles.py        # UI styling
├── visualization/       # Visualization tools
│   ├── sha256_visual.py # SHA-256 visualization
│   ├── crypto_visual.py # Cryptographic visualization
├── localization/        # Language support
│   ├── localize.py      # Localization logic
│   ├── en.json          # English translations
├── resources/           # Static resources (images, themes)
├── main.py              # Application entry point
└── requirements.txt     # Dependencies

## Installation
1. Clone the repository:git clone https://github.com/jayabrotabanerjee/SHA-256
cd sha256_playground
2. Install dependencies:pip install -r requirements.txt
3. Run the application:python main.py

## Usage
- Launch the app with `python main.py`.
- Navigate through the home page to access different features.
- Use the respective pages for text/file hashing, hash matching, or cracking.

## Future Improvements
- Enhance visualization with graphical outputs.
- Add support for more hash algorithms (e.g., MD5, SHA-1).
- Improve password cracking efficiency with dictionaries or GPU support.
- Expand localization to additional languages.

## License
This project is for educational purposes and not licensed for commercial use.
