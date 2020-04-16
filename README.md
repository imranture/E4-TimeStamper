# E4 TimeStamper
E4 TimeStamper helps researchers to automatically add timestamps to physiological data derived from Empatica's [E4 wristbands](https://www.empatica.com/research/e4/).

E4 wristband is a medical-grade wearable device that offers real-time physiological data acquisition, enabling researchers to conduct in-depth analysis and visualization. Please visit [Empatica](https://www.empatica.com) to learn more.

## How does it work? 
E4 TimeStamper extracts selected E4 zip file(s) and automatically timestamps each sample in each physiological data file (ACC.csv, BVP.csv, EDA.csv, HR.csv, IBI.csv and TEMP.csv) based on prefereed timezone and date & time format, following the [guideline](https://support.empatica.com/hc/en-us/articles/201608896-Data-export-and-formatting-from-E4-connect-) provided by Empatica.

## Download
**Windows**: Avaliable! Download from [this link](https://github.com/imranture/E4-TimeStamper/raw/master/setup/E4-TimeStamper.exe).\
**Mac**: Not yet, but soon!

## Installation
Double click `E4-Stamper.exe` to install the software to your desktop. Open the installed folder and double click `E4-TimeStamper_v00.exe` to run the software.

## Instructions
#### Step 1:  Select E4 zip file(s)
Click `Browse` button and select only E4 zip file(s) containing physiological data you want to timestamp.
<img src="https://github.com/imranture/E4-TimeStamper/blob/master/instructions/select_e4_zip_files.gif"/>

#### Step 2:  Choose timezone
Choose timezone based on the location where physiological data was collected.
<img src="https://github.com/imranture/E4-TimeStamper/blob/master/instructions/choose_timezone.gif"/>

#### Step 3:  Enter date and time formats
Specify the format of how physiological data should be timestamped. You may refer to [this cheatsheet](https://devhints.io/datetime) to learn how to do formatting.
<img src="https://github.com/imranture/E4-TimeStamper/blob/master/instructions/enter_date_and_time_formats.gif"/>

#### Final Step: Run!
When you are ready, click `Run` button. Once it is done, you will receive a warning message informing that your E4 Files with timestamps are created in their relevant folders within the same directory with your selected E4 zip file(s).

Remember that E4 files are usually very large files, so timestamping process may take a while depending the number of selected files. Please be patient. It will do the heavy job for you.

---
### Do you like it? Consider buying me a coffee: https://www.buymeacoffee.com/imran
---

## License
This software is an open-source project released under GNU General Public License v3.0. You are free to use and distribute it with suitable citation. Keep in mind that there is no warranty, and please do not claim this work as your own.\
Please review the [license file](https://github.com/imranture/E4-TimeStamper/blob/master/LICENSE) for more.

## Contact
Please do not hesitate to contact me if you require further information about the software, find any issues or just want to say thanks.\
**Email**: `imran at alumni.rutgers.edu`\
**Website**: https://imranture.com/
