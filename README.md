<h1><img width = 55 height = 55 src="https://github.com/imranture/E4-TimeStamper/blob/master/image/e4timestamper-logo-12012024.png"> E4 TimeStamper</h1>

[![version](https://img.shields.io/badge/release-win%20v0.4-blue)](https://github.com/imranture/E4-TimeStamper/releases/tag/v0.3-beta) [![version](https://img.shields.io/badge/release-macOS%20v1.0-red)](https://github.com/imranture/E4-TimeStamper/releases/tag/macOS-v1.0)

## What is it?
E4 TimeStamper automatically add timestamps to physiological data derived from Empatica's [E4 wristbands](https://www.empatica.com/research/e4/).

## How does it work? 
E4 TimeStamper extracts selected E4 zip file(s) and automatically timestamps each sample in each physiological data file (ACC.csv, BVP.csv, EDA.csv, HR.csv, IBI.csv and TEMP.csv) based on preferred timezone and date & time format, following the [guideline](https://support.empatica.com/hc/en-us/articles/201608896-Data-export-and-formatting-from-E4-connect-) provided by Empatica.

## Download & Installation
**`Windows`** : Download from [this link](https://github.com/imranture/E4-TimeStamper/raw/master/setup/win/E4-TimeStamper_Installer_v0-3.exe). Double click `E4-TimeStamper_Installer_v0-3.exe` and follow the instructions to install E4 TimeStamper.

**`macOS`** : Download from [this link](https://github.com/imranture/E4-TimeStamper/raw/master/setup/mac/E4-TimeStamper_macOS_v1-0.zip). Unzip `E4-TimeStamper_macOS_v1-0.zip` and drag the app file to Applications folder. Tested on macOS Sonoma 14.0!

## Instructions
#### Step 1:  Select E4 zip file(s)
Click `Browse` button and select only E4 zip file(s) containing physiological data you want to timestamp.

<img src="https://github.com/imranture/E4-TimeStamper/blob/master/instructions/select_e4_zip_files.gif"/>

#### Step 2:  Choose (or type) timezone
Choose (or type) timezone based on the location where physiological data was collected.

<img src="https://github.com/imranture/E4-TimeStamper/blob/master/instructions/choose_timezone.gif"/>

#### Step 3:  Enter date and time formats
Specify the format of how physiological data should be timestamped. You may refer to [this cheatsheet](https://devhints.io/datetime) to learn how to do formatting.

<img src="https://github.com/imranture/E4-TimeStamper/blob/master/instructions/enter_date_and_time_formats.gif"/>

#### Final Step: Run!
When you are ready, click `Run` button. Once it is done, you will receive a warning message informing that your E4 Files with timestamps are created in their relevant folders within the same directory with your selected E4 zip file(s).

Remember that E4 files are usually very large files, so timestamping process may take a while depending the number of selected files. Please be patient. It will do the heavy job for you.

---
### Do you like it? Support via https://www.buymeacoffee.com/imran
---

## License
This software is an open-source project released under [GNU General Public License v3.0](https://github.com/imranture/E4-TimeStamper/blob/master/LICENSE), provided "as-is," without any warranty; without even the implied warranty of merchantability or fitness for a particular purpose.\
In no event shall the author be held liable for any damages arising from the use of this software.

Permission is granted to anyone to use this software for any purpose, including commercial applications, and 
to modify and redistribute it provided that the following conditions are met:

1. All redistributions of source code files must retain all copyright notices that are currently in
   place, and this list of conditions without modification.

2. All redistributions in binary form must retain all occurrences of the above copyright notice and
   web site addresses that are currently in place.

3. The origin of this software must not be misrepresented; you must not claim that you wrote the
   original software. If you use this software to distribute a product, an acknowledgment in the
   product documentation would be appreciated.

4. Modified versions in source or binary form must be plainly marked as such, and must not be
   misrepresented as being the original software.

Except where otherwise noted, all of the documentation and software is copyrighted by Imran Ture.\
Copyright &copy; 2020 Imran Ture

E4 wristband, developed by Empatica, is a medical-grade wearable device that offers real-time physiological data acquisition, enabling researchers to conduct in-depth analysis and visualization. Please visit [Empatica](https://www.empatica.com) to learn more.

The logo <img width = 25 height = 25 src="https://github.com/imranture/E4-TimeStamper/blob/master/image/e4timestamper-logo-12012024.png"> was created with DALL·E 3.

## Contact
Please do not hesitate to contact me if you require further information about the software, find any issues, or just want to say thanks.\
**Email**: `imran at alumni.rutgers.edu`\
**Website**: https://imranture.com/
