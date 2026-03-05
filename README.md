<h1 align="center">
  <img src="https://img.shields.io/badge/Objective--C-000000?style=for-the-badge&logo=apple&logoColor=white" alt="Objective-C"/>
  <img src="https://img.shields.io/badge/Xcode-147EFB?style=for-the-badge&logo=xcode&logoColor=white" alt="Xcode"/>
  <img src="https://img.shields.io/badge/macOS-000000?style=for-the-badge&logo=apple&logoColor=white" alt="macOS"/>
  <br>
  <br>
  <code><strong>ObjC_Book_Projects</strong></code>
</h1>

<p align="center">
  <img src="https://img.shields.io/github/license/BitWise-0x/ObjC_Book_Projects?style=flat-square&color=blue" alt="License"/>
  <img src="https://img.shields.io/github/last-commit/BitWise-0x/ObjC_Book_Projects?style=flat-square&color=green" alt="Last Commit"/>
  <img src="https://img.shields.io/badge/language-Objective--C-000000?style=flat-square&logo=apple&logoColor=white" alt="Objective-C"/>
</p>

<p align="center">
  Challenge projects from <em>Programming in Objective-C</em> by Big Nerd Ranch.<br>
  Chapter-by-chapter exercises covering the full Objective-C language and Cocoa fundamentals.
</p>

---

## About

This repository contains solutions to the end-of-chapter challenges from the Big Nerd Ranch *Objective-C Programming* book. Each project is self-contained and organized by chapter, progressing from language basics through memory management, collections, blocks, and Cocoa design patterns.

<br>

## Structure

```
ObjC_Book_Projects/
├── Ch01_*/          Introductory concepts
├── Ch02_*/          Variables, types, and expressions
├── ...              Chapter projects follow book order
└── ChNN_*/          Final chapters
```

<br>

## Requirements

<table>
<tr>
<td width="50%" valign="top">

### Toolchain

<img src="https://img.shields.io/badge/Xcode-147EFB?style=flat-square&logo=xcode&logoColor=white" alt="Xcode"/>
<img src="https://img.shields.io/badge/macOS-000000?style=flat-square&logo=apple&logoColor=white" alt="macOS"/>

- **Xcode** 12 or later
- **macOS** 11 Big Sur or later
- Command Line Tools (`xcode-select --install`)

</td>
<td width="50%" valign="top">

### Running a Project

```bash
# Open in Xcode
open ChXX_ProjectName/ChXX_ProjectName.xcodeproj

# Or build from the command line
xcodebuild -project ChXX_ProjectName.xcodeproj \
           -scheme ChXX_ProjectName build
```

</td>
</tr>
</table>

<br>

## License

MIT License — see [LICENSE](LICENSE) for details.
