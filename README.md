# WinPass11 - Windows 11 Hardware Requirements Bypass

A lightweight, automated batch script to bypass strict system requirements when installing or upgrading to **Windows 11** on older or officially "unsupported" PC hardware.

🚀 What does this script do?
When executed, it automatically and safely modifies the Windows Registry (adding parameters to the `LabConfig` key). This instructs the Windows 11 installer to completely skip checking for the following components:
• TPM 2.0 (BypassTPMCheck)
• SecureBoot (BypassSecureBootCheck)
• RAM size (BypassRAMCheck)
• CPU compatibility (BypassCPUCheck)

🛠 How to use it?
1. Download and extract the ZIP archive.
2. Copy the `bypass.bat` file to your Windows 11 bootable USB flash drive.
3. During Windows 11 installation, if you see the "This PC can't run Windows 11" screen, press Shift + F10 to open the Command Prompt.
4. Run this script by typing `bypass.bat` and pressing Enter.
5. The script will display: "Проверка железа успешно отключена! Теперь запускай setup.exe".
6. Close the Command Prompt and proceed with the installation smoothly!

🔗 For Developers & Automation Tools
You can easily fetch and deploy this script directly into your custom OS installers, game launchers, or automation tweaks via GitHub Raw links.
