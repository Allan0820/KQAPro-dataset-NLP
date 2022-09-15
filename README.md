# KQAPro-dataset-NLP
This repository consists of all the operations done on the KQAPro dataset - https://github.com/shijx12/KQAPro_Baselines

JQ CLI for JSON processing has been used to process the files in the raw_data folder into the data_processed folder for easy readablity and usage. 

# Using JQ CLI for JSON file preprocessing 

A windows 11 use case is shown below.

**Step 1**: Download JQ from the official site for your respective OS - https://stedolan.github.io/jq/

**Step 2**: Create a folder in the C drive named jq and paste the executable file that you downloaded into the folder. Rename the file as jq (Error1: beware the file is by default an exe file so do not save it as 'jq.exe' save it only as 'jq')

**Step 3**: Set your path variable to the URL of the executable file.

**Step 4**: Open your directory on cmd where the json file is stored and type the following command - jq . currentfilename.json > targetfilename.json

**Step 5**: Replace currentfilename with the file name that you want to format replace targetfilename with the final file name that you want your data formatted in
