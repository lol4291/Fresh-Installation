
# For Fresh-Installs
Use the applications attached here to complete installations

# WARNING: DO THE FOLLOWING STEPS FIRST

1. Go to Start, search Windows Security
2. Click on Virus and Threat Protection.
3. Under Virus & threat protection setting, click Manage settings.
4. Turn off the following:
   * Real-time protection
   * Cloud-delivered protection
   * Automatic Sample Submission
   * Tamper Protection
5. On left hand side, click Firewall & Network Protection
6. Turn off the following:
   * Domain Network
   * Public Network
   * Private Network

Follow these phases:

# PART A) Activate Windows [Win Activation]

Obtained from https://saidit.net/s/sjain_guides/comments/9p3/hwidkms38genmk6_download_and_usage_guide/

Steps

1. Download included RAR file = **[thk.003mk6_pw.zip](https://github.com/lol4291/Fresh-Installation/raw/master/thk.003mk6_pw.zip)**
2. Extract the content. Use password = **123**.
3. Double click and press Yes. If your UAC is set to low, run as Administrator.
4. If running Windows 10 LTSC 2019 v1809, or any server edition of Windows 10, select KMS38. Everything else choose **HWID**.
5. Press Start.
6. Wait for process to finish.
7. Close Program
8. Restart PC/Laptop.

# PART B) Remove Windows Bloatwares

Steps:
1. Right click on the Start Button.
2. Click on Windows Powershell (Admin).
3. Paste in the following line
> powershell -nop -c "iex(New-Object Net.WebClient).DownloadString('https://raw.githubusercontent.com/lol4291/win10script/Modified-to-use/win10debloat.ps1')"
4. Wait for it to complete, it'll take some time.
5. Once completed, it'll ask to press any key and it'll restart.

# PART C) Install and activate Office [Office Installation]

Guide from https://saidit.net/s/sjain_guides/comments/9p0/microsoft_office_201319_simple_method_to_download/

Steps:
1. Download the included rar file = **[Office 2013-2019 C2R Install v6.8.0.zip](https://github.com/lol4291/Fresh-Installation/raw/master/Office%202013-2019%20C2R%20Install%20v6.8.0.zip)**
2. Extract the folder. Use password = **123**.
3. Double click on **O-install.exe**
4. Change the following options:
   * Choose **Microsoft Office 2019**
   * Choose **ProPlus** [Standalone if you only want certain softwares]
   * Choose **x86** or **x64** depending on your system.
   * Choose language
   * Leave update channel as it is.
5. Click Install office and wait to complete.

After Installation:
1. Go to Utilities Tab
2. Tick both **Online KMS** and **Office Reactivation Tasks**.
3. Click on **Office Retail => VL**.
4. Wait for process to complete.
5. Click on Activate Windows.
6. Wait for Process to complete.
7. Close program.

# After Win Activation and/or Office Installation, turn back on all the settings.

1. Go to Start, search Windows Security
2. Click on Virus and Threat Protection.
3. Under Virus & threat protection setting, click Manage settings.
4. Turn on the following:
   * Real-time protection
   * Cloud-delivered protection
   * Automatic Sample Submission
   * Tamper Protection
5. On left hand side, click Firewall & Network Protection
6. Turn on the following:
   * Domain Network
   * Public Network
   * Private Network
