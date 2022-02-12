# kcse_result_analysis
K.C.S.E RESULTS ANALYSIS.
This dataset involved supervised learning using labeled data.
Started by taking a quick look at the data structure and getting a quick description of the data.
There are 36 instances in the dataset (small dataset). All attributes have 36 non-null values meaning there is no missing features. All attributes except gender are numerical (integers). Gender having this data in csv form is text meaning it is a categorical attribute. I first looked into the overview of the data and the looked at the numerical attributes of the dataset looking at the specific grade mean, standard deviation…
To picture the data graphically, I used histograms using matplotlib.
I plotted graphs as shown below to get various correlations between the genders and various grades. The images show how the best and worst grades evolved over the years for both genders.
 
<img width="791" alt="2022-02-12 (19)" src="https://user-images.githubusercontent.com/65388647/153728131-22a32fc7-0672-4956-99fc-178ff9a03da4.png">

To continue the correlation search, I looked into the correlation between different grades. Below is an example of the correlation between grade A and other grades.
<img width="358" alt="2022-02-12 (17)" src="https://user-images.githubusercontent.com/65388647/153728150-852790aa-69a9-406f-8880-9ad0590c2faf.png">
 
Since the dataset is small, the correlation can be easily computed between every pair of attributes.  In this case we see the correlation of grade A and all other grades. When close to 1, it means there is a strong positive correlation. for example, grade A- tends to go up when A goes up. When coefficient is close to -1, it means there is a strong negative correlation (you cans see a small negative correlation between grade E and A. A has a tendency to go down when E increases.)
Another way to check for correlation between attributes is to use Pandas' scatter matrix function
To get to the main analysis of the data;
After getting the total values per year, one can observe from the graphs, an increase of students taking the exam over the years.
I mainly worked with showing the correlation of one grade to various genders per year, as shown in the example below.
 <img width="701" alt="2022-02-12 (34)" src="https://user-images.githubusercontent.com/65388647/153728169-8f7d71cd-0578-4694-910a-a923b7d7f982.png">

Lastly, I graphically showed a general view of the data 
<img width="416" alt="2022-02-12 (21)" src="https://user-images.githubusercontent.com/65388647/153728195-5b67b4a1-2aca-4a75-b518-5b2ac37aef83.png">

P.S – More analysis like data entry can be found in the code.

