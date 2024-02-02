# github project 2024-02-02
This is an Open Sceince project about Wikipedia.

## Requirements

Python 3.10^

## Installation
Clone the repository :

```bash
git clone git@github.com:wubba438/Open_Science_B1.git
cd data_science_project
```

Create and activate a virtual envirnment :

```bash
python3 -m venv .my_venv
source .my_venv/bin/activate
```
or

```bash
python -m venv .my_venv
source .my_venv/bin/activate
```

Install dependencies :
make sure you install everything documented in the requirements.txt file

```bash
python -m pip install -r requirements.txt
```


### Files
The codes are located in 3 files. The first 2 files are mainly inherited from the work of another research group, here I have attached the github link to their project : https://github.com/AF-Cabouat/Wikipedia-Block-log

1 Fetch_Block_Log_data.ipynb It does:
- Data scrapping
- Data cleaning
- Check the distribution of "duration" of bocks

2 Analyze_Blocklog data_original.ipynb does:
- Data loading
- Data cleaning
- Data analysis

3 Analyze_Blocklog data.ipynb does:
- Data loading
- Data cleaning
- Data analysis(mainly about the bot administrators)

The data could be found in the "data_original" folder. The folder contains:
- Blocking policy-related pages creation timeline on English Wikipedia.xlsx
- Blocking rationales dropdown menu tags creation timeline.xlsx
- freq_policies_monthly.csv
- MonthlyEditAndEditorsFrom2004-2017.csv

It is worth noting that , due to the limitation of the size of uploading files, we have not managed to include scrapped data done by the previous group and scrapped data done by our group inside.
But you can find these two files, "block_log_data_old.csv" and "block_log_data_new.csv" in the Google drive link we provide below.

The results generated by the data analysis will be stored in the "data_results" folder. We have put the results we got inside but you are more than welcome to replicate it yourself.


Here is the google drive link to our documents
https://drive.google.com/drive/folders/0AHoFsmLXOb3AUk9PVA
