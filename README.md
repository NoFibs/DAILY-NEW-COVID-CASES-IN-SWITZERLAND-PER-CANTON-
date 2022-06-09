# DAILY-NEW-COVID-CASES-IN-SWITZERLAND-PER-CANTON-

GROUP PROJECT @HSG
CREATED BY ADRIATIK NIMANAJ, DAVID FÄSSLER, FLORIAN NIKQI /
10. JUNE 2022 /
Lecturer: Dr. Mario Silic

# Covid is changing our lives drastically
Covid has definitively changed the way we live, work, travel, pay and protect ourselves. Through the Corona virus, we have seen that we can quickly end up in a pandemic due to the strong global network. Major changes were also carried out in schools and universities, for example. The switch to virtual channels has well advanced during this period of time, which can also be seen in the course ,,Introduction to Programming’’, where the course is held completely online. Nevertheless, it is becoming increasingly apparent that we must live with the virus, especially during the cold season. This requires continuous monitoring to be able to react depending on the number of cases. 

# Importance of measuring and comparability of covid cases 
An increasing number of Covid-19 cases allows conclusions to be drawn about how many hospital and intensive care patients can be expected. This allows for more concrete, better and more efficient planning and preparation, in order to prevent overloading the healthcare system. As a result, it is important to be able to compare case numbers at cantonal level. This prevents an excessive number of cases in a canton, which would lead to an overload of the intensive care units. With this knowledge, patients can be shifted cantonally, to guarantee health care for everyone.

# Sense and purpose of the code 
For this matter, we have created a code that retrieves the Swiss Covid numbers from the BAG database and shows them in a graphic. Individual cantons can be hidden by left-clicking on the respective canton. This also makes waves and seasonality visible, which is often discussed in corona research.

# Some information about the specific files 
The "Read Me" file contains introductory information such as the sense and purpose of the code. This serves as an introduction to the topic. The requirement file contains very important requirements that must be observed in order to get the code to work. The various packages must be installed in PyCharm! Finally, there is the code file, which contains the actual code.The specific instructions to get the code running are included in the form of comments in the code itself.

# Why do we need smoothing?

    In general, the data contains some unwanted noise which has to be filtered out.

    So by smoothing data we will receive a better representation of our data,

    which then will have less noise (unwanted data) and a better understandable data, which

    allows us to build some hypothesis or discover some patterns, trends or further knowledge.




# How does the window size affect the result?

    with an increasing window size, we will get a smoother data.

    Since we are smoothing by the mean value, an increasing number of the window size results in

    greater number of values which we calculate the mean over it.

    i.e with window size 3: the value would be the avg of previous 3 values ,

    with 10 we are computing the mean over the previous 10 values and so on.



DataTime library is used to transform the dates from the DataFrame to have a DateTime formatt, since bokeh can only handle this data type.
