
# Digital Forensics Projects Collection

A series of hands-on digital forensics projects covering **volatile & non-volatile data acquisition**, **disk analysis**, **OS forensics**, **Active Directory investigations**, and **mobile device forensics**.

## 📁 Project List

### 1. **Computer Forensics Essentials**
#### Part A: Live Acquisition of Volatile Data
- Captured RAM from a live system using CLI tools
- Analyzed memory dumps with Bulk Extractor
- Documented order of volatility (Registers → RAM → Swap → Disk → Remote logs)
- **Tools Used**: `DumpIt`, `Bulk Extractor`, `Volatility`

#### Part B: Dead Acquisition of Non-Volatile Data
- Created forensic images via FTK (removable drive scenario)
- Built Paladin live USB for non-removable drive scenarios
- **Key Features**: Write-blocking procedures, hash verification

#### Part C: Disk Forensic Analysis
- Analyzed a mass shooting case scenario
- Extracted Windows Registry hives using FTK/Autopsy
- Ripped artifacts with RegRipper
- **Critical Findings**: Timeline reconstruction of suspect activities

---

### 2. **Operating System Forensics**
- Manual data recovery via header/footer signatures
- Created `dd` images of formatted USB devices
- Recovered deleted `.jpg`/`.png` files through hex analysis
- **Technical Detail**: Sector-by-sector recovery methodology

---

### 3. **Advanced Forensics**
#### Active Directory Case Study
- Timeline analysis of NTDS.DIT files
- Artifact correlation for incident reconstruction

#### Cloud Forensics (Google Drive)
- Documented installation/uninstallation artifacts
- Mapped file upload/download traces
- Analyzed anti-forensic tool residues
- **Log Sources**: `%AppData%`, registry keys, SQLite databases

---

### 4. **Mobile Forensics**
- Performed logical acquisition via ADB (Android)
- Extracted backup files from iOS devices
- Analyzed backup structures using `SQLite Browser`, `plist` readers
- **Device Models**: [Specify your test devices]

---

## 🛠️ Toolset
| Category          | Tools Used                          |
|-------------------|-------------------------------------|
| Memory Forensics  | Volatility, Bulk Extractor, DumpIt  |
| Disk Imaging      | FTK Imager, Paladin, `dd`           |
| Analysis          | Autopsy, RegRipper, Plaso           |
| Mobile            | ADB, iTunes, Cellebrite UFED (opt.) |
| Cloud             | DB Browser for SQLite, Registry Explorer |

---

## 📝 Key Learnings
- Developed chain-of-custody documentation skills
- Mastered forensic image acquisition (E01, DD, AFF formats)
- Practiced artifact analysis from multiple OS sources
- Gained hands-on experience with commercial & open-source tools

## 🚀 How to Use
1. Clone repository: `(https://github.com/Codingabbad/Forensics-Projects.git)`
2. Refer to individual project folders for:
   - Detailed reports (PDF/DOCX)
   - Tool configuration guides
   - Evidence handling protocols

## 📜 License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
Free For Public use  
**Ethical Note**: All work conducted on legally obtained devices with proper authorization.

Would you like me to:
1. Add specific tool command examples?
2. Include a forensic checklist template?
3. Create a separate "Findings Interpretation" section?
4. Add a FAQ for common forensic challenges?
