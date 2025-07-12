
# ADMIN - Admin Panel Finder Tool

---

## Overview

**ADMIN** is a fast, threaded **Admin Panel Finder** tool written in Python, designed for Termux and Linux environments. It helps security researchers and ethical hackers quickly scan websites for common admin panels and login pages.

The tool supports multi-threading using `ThreadPoolExecutor` for speed, colorful and clean output with `rich` and `colorama` modules, and displays results inside styled boxes for easy readability.

---

## Installation

### Requirements

- Python 3.6+  
- `requests` library  
- `rich` library  
- `colorama` library  

Install dependencies using pip:

```bash
pip install requests rich colorama
```

---

## Usage
Clone the repository

```bash
git clone --depth=1 https://github.com/JOY-XII/ADMIN.git
```
Open directory

```bash
cd ADMIN 
```

Run the tool by executing the Python script:

```bash
python3 AdminFinder.py
```

You will be prompted to enter the target URL:

```
[?] Enter Target URL: example.com
```

*Note:* You can enter URLs with or without the `http://` or `https://` prefix; the script will handle it.

The tool will then scan a list of common admin panel paths on the target website and display the results in colored, boxed output.

---

## Example Output

```
┌─────────────────────────────────────────────────────────┐
│ http://example.com/admin --> Boom!                                │
└─────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────┐
│ http://example.com/cpanel --> Mother F**Ker Forbidden             │
└─────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────┐
│ http://example.com/login --> Not Found :(                         │
└─────────────────────────────────────────────────────────┘
```

---

## Ethical Disclaimer

**ADMIN** is built for educational and ethical penetration testing purposes only. Always have explicit permission from the target website owner before scanning. Unauthorized scanning or attacks may violate laws and result in penalties.

---

## Author

**JOY-XII**  
*OWNEЯ: BΔΣ MΔX*  

GitHub: [https://github.com/JOY-XII](https://github.com/JOY-XII)  

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Contributions & Support

Contributions, suggestions, and improvements are welcome! Feel free to open issues or pull requests.

If you find this tool helpful, a ⭐ on the repo is appreciated!

---

**Stay safe and hack ethically!** 🚀
