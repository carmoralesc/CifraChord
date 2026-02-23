# CifraChord

# 🎵 ChordPro Converter Extension

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)]
[![Platform](https://img.shields.io/badge/platform-Chrome%20%7C%20Brave%20%7C%20Edge-green.svg)]

Convert chord sheets from popular websites like Ultimate Guitar, LaCuerda.net, and Cifra Club into modern, fully compatible ChordPro format automatically.

---

## ✨ Features

- ✅ Automatic conversion to modern ChordPro format
- ✅ Full transposition compatibility
- ✅ Proper measure separators (`[|]`)
- ✅ Section conversion using `{comment: Section Name}`
- ✅ Removes invalid or legacy tags like:
  - `{start_of_verse}`
  - `{end_of_chorus}`
  - `{soc}`
  - `{eoc}`
- ✅ Fixes formatting issues from:
  - Ultimate Guitar
  - LaCuerda.net
  - Cifra Club
- ✅ Removes unwanted blank lines inside sections
- ✅ Preserves musical structure and alignment
- ✅ Supports slash chords (`D/F#`, `A/C#`, etc.)
- ✅ Supports instrumental measures
- ✅ Automatic detection of supported websites
- ✅ Built-in transposition support

---

## 🌐 Supported Websites

- Ultimate Guitar  
  https://www.ultimate-guitar.com

- LaCuerda.net  
  https://lacuerda.net

- Cifra Club  
  https://www.cifraclub.com  

---

## 📦 Installation (Developer Mode)

1. Clone or download this repository
   ´git clone https://github.com/carmoralesc/CifraChord.git´

2. Open 
Chrome, Brave, or Edge

3. Go to:
   chrome://extensions/

4. Enable:
   Developer mode

5. Click:
   Load unpacked

6. Select the extension folder

---

## 🚀 Usage

1. Go to a supported chord website
2. Click the extension icon
3. The page will automatically convert to ChordPro format
4. Copy or export the result

---

## 🎼 Output Example

Input:
  G                C
Amazing grace how sweet the sound

Output:
´{comment: Verso}
A[G]mazing grace how s[C]weet the sound


Instrumental example:
´[|][D][-][-][-][|][Dsus][-][-][-][|]´


---

## ⚙️ ChordPro Compliance

This extension follows modern ChordPro standards:

- Fully transposable chords
- Measure-based formatting
- Compatible with:

  - Charts by WorshipTools
  - OpenLP
  - OnSong
  - SongBook
  - EasyWorship
  - ProPresenter (via conversion)

Official specification:  
https://www.chordpro.org/chordpro/

---

## 🧠 Smart Formatting Rules

The converter automatically:

- Removes blank lines inside sections
- Adds proper spacing between sections
- Fixes malformed chord syntax
- Converts legacy formats
- Detects instrumental measures
- Preserves alignment

---

## 🔒 License

MIT License

Copyright (c) 2026 Carlos Morales

See LICENSE file for details.

---

## 👨‍💻 Author

Carlos Morales

GitHub:  
https://github.com/carmoralesc

---

## 🤝 Contributing

Pull requests are welcome.

For major changes, please open an issue first.

---

## ⭐ Support

If this project helps you, please consider giving it a star ⭐ on GitHub.

---

## 🔮 Future Features

- Export to .cho file
- Batch conversion
- Auto-save library
- Integration with WorshipTools
- Tone selector UI
- Multi-language UI support

---

## ⚠️ Disclaimer

This tool does not host or distribute copyrighted content.  
It only converts user-accessible chord sheets into ChordPro format.

---

## 🎯 Mission

Provide musicians with the most accurate and modern ChordPro conversion tool available.
