# DataScience_Project 1
This repository contains the work for Project 1 in Data Science, related to the topic of dataframes in Bahasa. from the data science training I underwent at DigitalSkola.

### Please read this note to understand the file [SANBOX] DS PROJECT 1.ipynb.

Basically, what we are doing here is preparing data for the analysis of laptop usage in society, using the dataset [Complete]Laptop_Price.csv.

### Step 1:
If you're interested in this topic, the first step is to click on the dataset file [Complete]Laptop_Price.csv to view the dataset we have.

### Step 2:
After understanding the dataset we have, go directly to the file [SANBOX] DS PROJECT 1.ipynb. This will guide you through the steps of preparing and visualizing the data.

#### **Notes:** Skip the sections in Colab until Data Cleaning + Feature Engineering (FE).

#### **Laptop ID:** What we do in the Laptop ID section is remove the laptop ID. This is done because the laptop_id doesn't have any meaning in the data, so its role can be replaced with the index.

#### Screen Resolution: What we do in this section is extract the screen resolution, such as '2560x1600', using regex. We also categorize the screens into two groups, touch screen and non-touch screen.

#### CPU: What we do in the CPU section is separate the CPU speed frequency.

#### RAM: RAM is the same, we separate the number from the GB part for analysis. The way to separate it is also using regex. Then we rename the column using the pandas .rename({}) function.

#### Memory (Drive): In the memory section, it's a bit complex because we separate the memory allocation, whether the laptop has dual memory or not. We also extract the size of the storage, like '128', by changing its format to an integer for analysis.

#### Weight: In this section, we only separate the weight number from the 'kg' string.

#### CPU & GPU Manufacturing Companies: Here, we sort the CPU and GPU. There will be three types of CPUs: Intel, AMD, and Samsung. Then the GPU section will have Intel, Nvidia, and AMD.

Then, for the file that has undergone cleaning, you can view it at [Cleaned]Laptop_Price.csv. That's all for dataset preparation.
