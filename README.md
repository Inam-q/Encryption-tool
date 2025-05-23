# Encryption-tool
# Word VBA Encryption Tool

⚠️ **Warning**: This tool encrypts files for educational purposes only. Use only on test systems you own.

## Prerequisites
1. **Java 24** ([Download](https://www.oracle.com/java/technologies/javase-downloads.html))
2. Windows OS (64-bit)

## Setup
1. **Create the target folder** (Required for encryption):
   ```cmd
   mkdir C:\SecuritySimulation
   ```
   - Add test files (e.g., `test1.txt`) to this folder.

2. **Download files**:
   - `main.exe`
   - `lib/jacob.jar`
   - `jacob-1.21-x64.dll`

## Usage
1. Place all files in the **same folder**.
2. Run:
   ```cmd
   main.exe
   ```
   - This will encrypt files in `C:\SecuritySimulation`.

3. **Decryption**:
   - When prompted, enter the decryption key:
     ```
     NoOneWasHere
     ```

## File Structure
```
project/
├── main.exe            (Main program)
├── jacob-1.21-x64.dll  (Required for Word automation)
└── lib/
    └── jacob.jar       (Support library)
```

## Legal Disclaimer
This tool is for **educational/research purposes** only. The creator assumes no liability for misuse. Always obtain proper authorization before testing on any system.
