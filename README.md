# sage

Assignment -7
Topic-COVID-19
Name -Yashdeep patwa 
roll no-19/11/EC/056
Date-12/04/2020

Ex 1. Explain 5 reasons you think Covid vaccines could take 12-18 months to develop. The 5 reasons should be based on the way experiments are designed. All news reports/studies you mention should be referenced. Do not use more than 200 words. 

 Analysing the previous pandemic situation and viewing the outcomes ,
we can get some tentative idea for the following pandemic/epidemic .

1.Procedure of Generation of vaccine 
several points to take care of before and after generation of vaccine 
such as-
    • 1.vaccines must be safe 
    • 2.vaccines must be effective 
    • 3.vaccines must be manufactured 
    • 4.vaccines must be regulated. 

Source - https://en.wikipedia.org/wiki/Vaccine 
2.Performing tests
    • Normally, developing a vaccine against a disease takes several years due to lengthy clinical trials and strict regulatory approvals.
    • In vaccine research and development, rapidly means in a year’s time and not soon enough for this outbreak. 
    • Trials involve testing the vaccine on several tens of thousands of people. But to reach this stage, the vaccine makers have to clear many hurdles.
Source - https://ourworldindata.org/coronavirus-testing 
      
3.International efforts to create coronavirus vaccine
A number of biotech companies, government agencies, universities and other organizations have partnered across the world in an effort to find a coronavirus vaccine. One of the largest efforts is coordinated by the Coalition for Epidemic Preparedness Innovations, a global partnership that works with companies, public organizations and philanthropic groups to speed development of vaccines. It's based in Oslo, Norway.
Source - https://www.usnews.com/news/best-countries/articles/2020-02-27/countries-struggle-to-develop-a-vaccine-for-the-new-coronavirus 

4.Previous situations
Development of vaccines is slow. Another Themis Bioscience vaccine, this one against Chikungunya, has reached a much advanced stage of Phase III trials. Dr Tauber says their Chikungunya vaccine, which has been under development for the past seven years, will be ready by 2023.
COVID-19 vaccine developers have been given a target of producing a vaccine within 12–18 months whilst historically vaccines have taken 15–20ears to develop. Some diseases still do not have vaccines despite decades ofwork. For example, over 100,000 children die each year from respiratorydisease caused by another RNA virus, RSV (respiratory syncytial virus, a cause ofwheeze and pneumonia). Despite 50 years of research and 18 products indevelopment, no RSV vaccine is currently available.
Source - http://www.rfi.fr/en/science-and-technology/20200307-coronavirus-why-vaccine-will-take-least-12-months 

5.Implementation time 
Although-Because of the devastating impact of Covid-19, all the stakeholders, from companies to regulatory agencies, will act faster and a vaccine could be on the market next year. A precedent was set in the case of the H1N1 flu when these timelines were accelerated.
Source -https://www.webmd.com/cold-and-flu/flu-guide/h1n1-flu-virus-swine-flu 



Ex 2. Gather total number of cases of Covid data from Covid India Wiki. Place in an excel/google sheets document, and save your sheet as a csv ﬁle. List the data in Sagemath. Do the same for your state’s data. My suggestion is to maintain the data in an excel ﬁle every day. 

India’s data -

import csv

with open("covid12_04.csv",'r') as csv_file:
    csv_reader = csv.reader(csv_file)
    
    for line in csv_reader: 
        print(line)

['Dates ', 'India']
['01/30/20', '1']
['02/02/20', '2']
['02/03/20', '3']
['03/02/20', '5']
['03/03/20', '6']
['03/04/20', '28']
['03/05/20', '30']
['03/06/20', '31']
['03/07/20', '34']
['03/08/20', '39']
['03/09/20', '44']
['03/10/20', '50']
['03/11/20', '60']
['03/12/20', '73']
['03/13/20', '81']
['03/14/20', '97']
['03/15/20', '107']
['03/16/20', '118']
['03/17/20', '137']
['03/18/20', '151']
['03/19/20', '173']
['03/20/20', '223']
['03/21/20', '283']
['03/22/20', '360']
['03/23/20', '434']
['03/24/20', '519']
['03/25/20', '606']
['03/26/20', '694']
['03/27/20', '834']
['03/28/20', '918']
['03/29/20', '1024']
['03/30/20', '1251']
['03/31/20', '1397']
['04/01/20', '1834']
['04/02/20', '2069']
['04/03/20', '2547']
['04/04/20', '3072']
['04/05/20', '3577']
['04/06/20', '4281']
['04/07/20', '4789']
['04/08/20', '5274']
['04/09/20', '5865']
['04/10/20', '6761']
['04/11/20', '7529']
['04/12/20', '8447']


MadhyaPradesh’s data-

import csv

with open("covid_MadhyaPradesh7.csv",'r') as csv_file:
    csv_reader = csv.reader(csv_file)
    
    for line in csv_reader: 
        print(line)

['dates ', 'M.P cases ']
['01/30/20', '0']
['02/02/20', '0']
['02/03/20', '0']
['03/02/20', '0']
['03/03/20', '0']
['03/04/20', '0']
['03/05/20', '0']
['03/06/20', '0']
['03/07/20', '0']
['03/08/20', '0']
['03/09/20', '0']
['03/10/20', '0']
['03/11/20', '0']
['03/12/20', '0']
['03/13/20', '0']
['03/14/20', '0']
['03/15/20', '0']
['03/16/20', '0']
['03/17/20', '0']
['03/18/20', '0']
['03/19/20', '0']
['03/20/20', '0']
['03/21/20', '4']
['03/22/20', '4']
['03/23/20', '6']
['03/24/20', '7']
['03/25/20', '14']
['03/26/20', '20']
['03/27/20', '30']
['03/28/20', '30']
['03/29/20', '30']
['03/30/20', '47']
['03/31/20', '47']
['04/01/20', '66']
['04/02/20', '99']
['04/03/20', '104']
['04/04/20', '104']
['04/05/20', '165']
['04/06/20', '165']
['04/07/20', '229']
['04/08/20', '229']
['04/09/20', '259']
['04/10/20', '259']
['04/11/20', '443']
['04/12/20', '564']




Ex 3. Make a histogram using the Covid sata for total number of cases using Sage

India’s data 
import csv
final = []

with open("covid12_04.csv",'r') as csv_file:
    csv_reader = csv.reader(csv_file)
    
    for line in csv_reader: 
        try:
            f = float(line[1])
            r = int(f)
            
        except ValueError:
            pass 
        
        else:
            final.append(r)
            
print(final)
histogram(final,bins=20,color='grey',rwidth=0.8)


[1, 2, 3, 5, 6, 28, 30, 31, 34, 39, 44, 50, 60, 73, 81, 97, 107, 118, 137, 151, 173, 223, 283, 360, 434, 519, 606, 694, 834, 918, 1024, 1251, 1397, 1834, 2069, 2547, 3072, 3577, 4281, 4789, 5274, 5865, 6761, 7529, 8447]






















Ex 4. Find the average (mean), median, and standard deviation of the Covid data. Plot the day-wise number of total cases and mark the average. On the same plot, make a normal plot with the same mean and standard deviation, but scaled with the average of your data (multiply by mean of your data). Does the Covid data satisfy a normal distribution? 


India’s data
import csv
final = []

with open("covid12_04.csv",'r') as csv_file:
    csv_reader = csv.reader(csv_file)
    
    for line in csv_reader: 
        try:
            f = float(line[1])
            r = int(f)
            
        except ValueError:
            pass 
        
        else:
            final.append(r)
            
print(final)
histogram(final,bins=20,color='grey',rwidth=0.8)

[1, 2, 3, 5, 6, 28, 30, 31, 34, 39, 44, 50, 60, 73, 81, 97, 107, 118, 137, 151, 173, 223, 283, 360, 434, 519, 606, 694, 834, 918, 1024, 1251, 1397, 1834, 2069, 2547, 3072, 3577, 4281, 4789, 5274, 5865, 6761, 7529, 8447]




mean(final)
1463.51111111


median-
meadian(final)
283


standard deviation -
std(final)
2261.35697015
















New cases – India 

import csv
final = []

with open("covid12_04new.csv",'r') as csv_file:
    csv_reader = csv.reader(csv_file)
    
    for line in csv_reader: 
        try:
            f = float(line[1])
            r = int(f)
            
        except ValueError:
            pass 
        
        else:
            final.append(r)

t = mean(final)
print(float(t))
m=median(final)
print(m)
a = variance(final)
b = sqrt(a)
print(float(b))
sd = std(final)
print(float(sd))
plot(t,xmax=45)+bar_chart(final,color='orange',width= 0.9,legend_label = "$covid$")

187.711111111
60
267.416309952
267.416309952
















scaled data 

import csv
final = []

with open("covid12_04newscaled.csv",'r') as csv_file:
    csv_reader = csv.reader(csv_file)
    
    for line in csv_reader: 
        try:
            f = float(line[3])
            r = int(f)
            
        except ValueError:
            pass 
        
        else:
            final.append(r)

t = mean(final)
print(float(t))
m=median(final)
print(m)
a = variance(final)
b = sqrt(a)
print(float(b))
sd = std(final)
print(float(sd))
plot(t,xmax=45)+bar_chart(final,color='orange',width= 0.9,legend_label = "$covid$")


35234.7333333
11262
50196.7175047
50196.7175047















Ex 5. Deﬁne functions that are measure of the moving average. Say A1(d) is the average of total cases the ﬁrst d days. Similarly, let A2(d) be the average of new cases for the ﬁrst d days. Make a list plot (with lines joined) of both the plots and note your observations.

India’s data 
import csv
final = []

with open("covid12_04.csv",'r') as csv_file:
    csv_reader = csv.reader(csv_file)
    for line in csv_reader: 
        try:
            f = float(line[1])
            r = int(f)
            
        except ValueError:
            pass 
        
        else:
            final.append(r)
            
t3 = moving_average(final,4)
list_plot(t3,color = "grey",plotjoined=true)










New cases -India 
import csv
final = []

with open("covid12_04new.csv",'r') as csv_file:
    csv_reader = csv.reader(csv_file)
    
    for line in csv_reader: 
        try:
            f = float(line[1])
            r = int(f)
            
        except ValueError:
            pass 
        
        else:
            final.append(r)
            
t3 = moving_average(final,4)
list_plot(t3,color = "grey",plotjoined=true)








comment-
       1.Moving average taken for 4 days at a time.
       2.consecutive 4 days avg is increasing and hence moving the graph one step upward after every 4 days.
       

---------------------------------------------------------------------------------------------------------------------------



Assignment – 9 
Name -Yashdeep patwa 
roll no -19/11/EC/056
Date -26/04/2020

Ex 1. Covid Study
(a.) Update the data from last week on India’s and your state’s covid cases. Make bar charts with both your state’s data and India’s data with the updated data. Comment on any trends in weekly rate of increase.
(b.) Study the data for the total number of cases and deaths from the US, based on what we have studied so far. Report on your observations regarding how the rate of growth of cases is changing in the past several weeks.

a)
India’ data-

import csv
final = []

with open("covid19_04.csv",'r') as csv_file:
    csv_reader = csv.reader(csv_file)
    
    for line in csv_reader: 
        try:
            f = float(line[1])
            r = int(f)
            
        except ValueError:
            pass 
        
        else:
            final.append(r)
            
print(final)
bar_chart(final,color='grey',width= 0.9,legend_label = "$Indiacovid$")

[1, 2, 3, 5, 6, 28, 30, 31, 34, 39, 44, 50, 60, 73, 81, 97, 107, 118, 137, 151, 173, 223, 283, 360, 434, 519, 606, 694, 834, 918, 1024, 1251, 1397, 1834, 2069, 2547, 3072, 3577, 4281, 4789, 5274, 5865, 6761, 7529, 8447, 9352, 10815, 11933, 12759, 13835, 14792, 16116]

















MadhyaPradesh’s data-

import csv
final = []

with open("covid_MadhyaPradesh8.csv",'r') as csv_file:
    csv_reader = csv.reader(csv_file)
    
    for line in csv_reader: 
        try:
            f = float(line[1])
            r = int(f)
            
        except ValueError:
            pass 
        
        else:
            final.append(r)
            
print(final)
bar_chart(final,color='grey',width= 0.9,legend_label = "$MadhyaPradesh$")

[0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 4, 4, 6, 7, 14, 20, 30, 30, 30, 47, 47, 66, 99, 104, 104, 165, 165, 229, 229, 259, 259, 443, 564, 604, 730, 987, 1120, 1308, 1355, 1407]


































b)





















Source- https://www.worldometers.info/coronavirus/country/us/

comment-
by looking at this two curves one can say that they are following exponantial trend which means both number of cases(total) and deaths are increasing.


Ex 2. Limit Theorems
(a.) Let p(k) denote the probability of getting k heads in 20 tosses of a fair coin. Graph (k,220p(k)) for k = 0,1,2,...,20.
(b.) Write a function to simulate a coin tossing experiment. Let H be denoted by 1 and T by 0. Let S(n) be a function which gives the number of heads in an experiment of n tosses of the coin, i.e., the sum of what you obtain in n trials. Take n = 20, and perform the experiment ten thousand times. Plot k against the number of times the value of S(20) comes to k. Make a dictionary X with X[k] equal to number of times you get k. Plot (k,X[k]).
1
(c.) Guess a form/parameters of the normal curve that ﬁts both of the above situations. That is, guess a function of the form f(x) = AeBx2+Cx+D
which ﬁts the above data. Plot your guess along with the above curves. Explain how you guessed the function, with reference to ideas from the textbook. The guess should be made based on theoretical considerations, not by computer.


a)

lst = []

for i in range(20):
     C = Combinations(range(20),i)
     
#      print(i,C.cardinality())
     lst.append((i,C.cardinality()))
    
print(lst)

list_plot(lst,color="grey",plotjoined = true,thickness=1)
        
[(0, 1), (1, 20), (2, 190), (3, 1140), (4, 4845), (5, 15504), (6, 38760), (7, 77520), (8, 125970), (9, 167960), (10, 184756), (11, 167960), (12, 125970), (13, 77520), (14, 38760), (15, 15504), (16, 4845), (17, 1140), (18, 190), (19, 20)]
























b)

lst = []
con = []
for j in range(10000):
     t = sum(randint(0,1) for i in range(20))
     lst.append(t)
     
print(lst)


for k in range(20):
    count = 0
    for i in range(10000):
        if k == lst[i]:
            
        
            count = count + 1
    
    con.append(count)
    
print(con)

print("")

print("final list generated")

print("")
final = []
for i in range(20):
    final.append((i,con[i]))
    
    
print(final)
    

*output data is very big 

list_plot(final,color="black",plotjoined=true)




















Ex 3. For all the following, explain your observations, if any, with reference to the topics covered in the book. This question uses the function S(n) written above.
(a.) If we make n trials, we expect S(n) to be approximately n/2. Let E(n) be a function that gives the error n/2−S(n). Modify the function you made to output a list with elements (10n,E(10n)). Plot (10n,E(10n)), for 0 ≤ n ≤ 1000.

(b.) Take n = 100, and ﬁnd the value of s(n) := 50−S(n). Repeat this experiment 10000 times, and plot a histogram of the data. 

(c.) The experiment is: pick n numbers (with replacement) from {2,3,5,7} and ﬁnd the sum, denoted by S2(n). Write a function that takes an input n and returns S2(n) after performing this experiment. Taking n = 100, repeat the experiment N times. Let X(k) be the function deﬁned by
X(k) := Number of times S2(100) = k.
Make a list plot of the list consisting of (k,X(k)). Repeat this experiment for as many times as it takes (by increasing the value of N) for a pattern to emerge.

a)

lst = []
for i in range(1000):
    t = sum(randint(0,1) for j in range(10*i))
    
    e = (10*i)/2 - t
    lst.append(e)
    
final = []

for i in range(1000):
    final.append((i*10,lst[i]))
    
print(final)

list_plot(final,color = "blue",plotjoined = true)
























b)

lst = []
for i in range(10000):
    t = sum(randint(0,1) for i in range(100))
    
    s = 50 - t
    lst.append(s)
    
histogram(lst,bins=[-20,-15,-10,-5,0,5,10,15,20],color='red',rwidth=0.8)


    





















c)

lst = [2,3,5,7]
l = []
con = []
final = []
for i in range(1000):
    s = sum(random.choice(lst) for i in range(100))
    l.append(s)
    
for j in range(200,700):
    count = 0
    for i in range(1000):
        if j == l[i]:
            count = count + 1
            
    con.append(count)
    
for i in range(500):
    final.append((i+200,con[i]))
    
print(final)

list_plot(final,color= "red",plotjoined = true)






















-----------------------------------------------------------------------------------

Assignment -10
Name – Yashdeep patwa 
roll no -19/11/EC/056
Date - 03/05/2020


Ex 1. Covid Study 
(a.) Update your data for state and country and make bar charts. Comment on any trends that you are seeing now, based on the kinds of analysis we have done in the past. Make charts for new cases in addition to total cases.
(b.) Explain, with reference to ideas from the book how you would go about sampling a population to check if community transmission of Covid19 has begun. Please refer to page numbers when referring to the book. Do not pick ideas from google. Write in your own words. I am not bothered about your language skills, but do care about your thinking skills.

a)  India’s data 
import csv
final = []

with open("covid03_05.csv",'r') as csv_file:
    csv_reader = csv.reader(csv_file)
    
    for line in csv_reader: 
        try:
            f = float(line[1])
            r = int(f)
            
        except ValueError:
            pass 
        
        else:
            final.append(r)
            
print(final)
bar_chart(final,color='grey',width= 0.9,legend_label = "$Indiacovid$")

[1, 2, 3, 5, 6, 28, 30, 31, 34, 39, 44, 50, 60, 73, 81, 97, 107, 118, 137, 151, 173, 223, 283, 360, 434, 519, 606, 694, 834, 918, 1024, 1251, 1397, 1834, 2069, 2547, 3072, 3577, 4281, 4789, 5274, 5865, 6761, 7529, 8447, 9352, 10815, 11933, 12759, 13835, 14792, 16116, 17656, 18985, 20471, 21700, 23452, 24942, 26917, 28380, 29974, 31787, 33610, 35365, 37776, 40263]









comment- Increasing graph. 
following exponential trend.

MadhyaPradesh’s data-

import csv
final = []

with open("covid_MadhyaPradesh10.csv",'r') as csv_file:
    csv_reader = csv.reader(csv_file)
    
    for line in csv_reader:
        try:
            f = float(line[1])
            r = int(f)
            
        except ValueError:
            pass 
        
        else:
            final.append(r)
            
print(final)
bar_chart(final,color='grey',width= 0.9,legend_label = "$MadhyaPradesh$")

[0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 4, 4, 6, 7, 14, 20, 30, 30, 30, 47, 47, 66, 99, 104, 104, 165, 165, 229, 229, 259, 259, 443, 564, 604, 730, 987, 1120, 1308, 1355, 1407, 1485, 1540, 1592, 1695, 1852, 1952, 2096, 2168, 2368, 2561, 2660, 2719, 2719, 2846]















comment- Increasing graph. 
following exponential trend.

New cases data -India

import csv
final = []

with open("covid03_05new.csv",'r') as csv_file:
    csv_reader = csv.reader(csv_file)
    
    for line in csv_reader:
        try:
            f = float(line[1])
            r = int(f)
            
        except ValueError: 
            pass 
        
        else:
            final.append(r)
            
print(final)
bar_chart(final,color='grey',width= 0.9,legend_label = "$Newcases$")

[0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 4, 4, 6, 7, 14, 20, 30, 30, 30, 47, 47, 66, 99, 104, 104, 165, 165, 229, 229, 259, 259, 443, 564, 604, 730, 987, 1120, 1308, 1355, 1407, 1485, 1540, 1592, 1695, 1852, 1952, 2096, 2168, 2368, 2561, 2660, 2719, 2719, 2846]















b)
 Increasing nature of graph shows that the disease is spreading from start of first case.
The rate at which this is spreding and the number of cases increasing in the area with just 1 -2 cases  shows that this can be transferred from person to person.
First we will see the number of cases on a particular day and after this we will analyse consecutively.
And then note all the cases within 1 week or 2 week. We will get idea of effect of disease in population area.


Ex 2. (Normal Distribution) Let
f(x) = ce−(x−a)2 2b2 .
(a.) Let a = 0, b = 1. Using Sage, ﬁnd the value of c such that the area under the curve of f(x) is 1. (Note: In Sage oo is short for inﬁnity, and -oo for minus inﬁnity. Do not use python libraries.)
(b.) Using the values of a, b and c from part (a.), plot the curve y = f(x). Find the area under the curve for the following intervals. Express the area as a percentage of the total area. Express your answer in probability notation, assuming this is a probability density function. The intervals are: (−∞,∞),(−∞,−2),(−∞,−1),(−∞,0),(−∞,1),(−∞,2),(−1,1),(−2,2),(1,∞),(2,∞). Some of these can be found by symmetry. Explain why the graph is symmetric across the y axis.
(c.) Take diﬀerent values of a, b and c, and ﬁnd areas under appropriate intervals as in (b.). Again, ﬁnd the ratios of the relevant areas to the total area. Explain your ﬁndings in a sentence and two. Give reference (page numbers/examples) in the book where the book has explained your ﬁndings.

a)

a = 0
b = 1

t = integrate(exp(-((x-a)^2)/(2*(b^2))),x,-oo,oo)
c = float(1/t)
print(c)
0.398942280401    #value of c 

b)
a = 0
b = 1
plot(0.398942280401*exp(-((x-a)^2)/(2*(b^2))))             0.398942280401 = value of c \












a = 0
b = 1
c = 0.398942280401
area_total = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,oo))
t = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,oo))
per = (t/area_total)*100
print("percentage ")
print(per)
percentage 
100.0

a = 0
b = 1
c = 0.398942280401
area_total = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,oo))
t = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,-2))
per = (t/area_total)*100
print("percentage ")
print(per)
percentage 
2.27501319482


a = 0
b = 1
c = 0.398942280401
area_total = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,oo))
t = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,-1))
per = (t/area_total)*100
print("percentage ")
print(per)
percentage 
15.8655253931

a = 0
b = 1
c = 0.398942280401
area_total = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,oo))
t = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,0))
per = (t/area_total)*100
print("percentage ")
print(per)
percentage 
50.0

a = 0
b = 1
c = 0.398942280401
area_total = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,oo))
t = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,1))
per = (t/area_total)*100
print("percentage ")
print(per)
percentage 
84.1344746069

a = 0
b = 1
c = 0.398942280401
area_total = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,oo))
t = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,2))
per = (t/area_total)*100
print("percentage ")
print(per)
percentage 
97.7249868052

a = 0
b = 1
c = 0.398942280401
area_total = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,oo))
t = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,2))
per = (t/area_total)*100
print("percentage ")
print(per)
percentage 
68.2689492137

a = 0
b = 1
c = 0.398942280401
area_total = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,oo))
t = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-2,2))
per = (t/area_total)*100
print("percentage ")
print(per)
percentage 
95.4499736104

a = 0
b = 1
c = 0.398942280401
area_total = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,oo))
t = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,1,oo))
per = (t/area_total)*100
print("percentage ")
print(per)
percentage 
15.8655253931

a = 0
b = 1
c = 0.398942280401
area_total = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,oo))
t = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,2,oo))
per = (t/area_total)*100
print("percentage ")
print(per)
percentage 
2.27501319482

Since , a = 0 if we put x = -x  f(x)=f(x) that why graph is symmetric about y axis .
Function is even when x = 0.


c)
1.Most of the area is in between (-2,2).Graph looks like probability density function graph.
2.Changing value of c does not change probability.
3.Changing value of a changes nature of function it is no more even.
4.Changing value of b changes the slope of f(x)

a = 4
b = 0.9
plot(0.398942280401*exp(-((x-a)^2)/(2*(b^2))))















a = 4
b = 0.9
c = 0.398942280401
area_total = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,oo))
t = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,oo))
per = (t/area_total)*100
print("percentage ")
print(per)
percentage 
100.0
a = 4
b = 0.9
c = 0.398942280401
area_total = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,oo))
t = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,-2))
per = (t/area_total)*100
print("percentage ")
print(per)
percentage 
1.30839166662e-09


a = 4
b = 0.9
c = 0.398942280401
area_total = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,oo))
t = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,-1))
per = (t/area_total)*100
print("percentage ")
print(per)
percentage 
1.38365089139e-06

a = 4
b = 0.9
c = 0.398942280401
area_total = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,oo))
t = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,0))
per = (t/area_total)*100
print("percentage ")
print(per)
percentage 
0.000440596370265

a = 4
b = 0.9
c = 0.398942280401
area_total = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,oo))
t = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,1))
per = (t/area_total)*100
print("percentage ")
print(per)
percentage 
0.0429060333197

a = 4
b = 0.9
c = 0.398942280401
area_total = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,oo))
t = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,2))
per = (t/area_total)*100
print("percentage ")
print(per)
percentage 
1.3134145691

a = 4
b = 0.9
c = 0.398942280401
area_total = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,oo))
t = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-1,1))
per = (t/area_total)*100
print("percentage ")
print(per)
percentage 
0.0429046496688

a = 4
b = 0.9
c = 0.398942280401
area_total = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,oo))
t = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-2,2))
per = (t/area_total)*100
print("percentage ")
print(per)
percentage 
1.31341456779

a = 4
b = 0.9
c = 0.398942280401
area_total = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,oo))
t = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,1,oo))
per = (t/area_total)*100
print("percentage ")
print(per)
percentage 
99.9570939667

a = 4
b = 0.9
c = 0.398942280401
area_total = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,-oo,oo))
t = float(integrate(c*exp(-((x-a)^2)/(2*(b^2))),x,2,oo))
per = (t/area_total)*100
print("percentage ")
print(per)
percentage 
98.6865854309

Most of the area percentage is in positive x – axis 
:)
Ex 3. For this question, use the ﬁle midterm.csv which contains scores of all students in the course. The grades are for the ﬁrst midterm (pre-lockdown) and are worth 25% of the total grade. Of this 15 marks are from the Minor, and 10 from Assignments and Quizzes. The questions pertain to ideas you may have learnt earlier too. Statistical analysis of any new data set begins by doing the kind of things you have been asked to do from Assignment 7 onwards (beginning with Chapter 1 of the book).
1
(a.) Read the data into a list. (Do not read the data from the list twice in this assignment.) Do the initial analysis of this data, such as ﬁnding mean, SD, number of observations, plot histograms, etc. Comment on your ﬁndings.
(b.) I claim that students who work hard on Assignments and Quizzes (represented by Internal) do well in the minor. Use the techniques you have learnt to comment on the truth of this claim.
(c.) Make a random sample of 20 students from the data for the total score. Find the sample mean and SD, and from this make a prediction of the actual sample mean with a 95% conﬁdence interval. Repeat this experiment ﬁve times and state all the results. Compare your results with the actual sample mean.
(d.) Generate a set of scores of a test with maximum marks 25 as follows. Suppose there are ﬁve questions on a test, each for 5 marks. The possible score in each question is {0,1,2,3,4,5}. Suppose a grader picks a number randomly from this set for each question, and then sums them up to obtain a score from 25. Let us call this a random midterm score. Generate a random sample of length 120 taking such random midterm scores and call it RandomScores. This represents the scores of 120 students in the midterm, if I had graded each of 5 questions randomly. Analyze this data as in (a.) and repeat the experiment of (c.).(e.) Compare the results of parts (c.) and (d.) and note ﬁve points (referring to the book) what you have understood from this experiment.
a)

import csv
lst = []

with open("midterm.csv") as file:
    csv_reader = csv.reader(file)
    
    for line in csv_reader:
        try:
            f = float(line[3])
            
            
        except:
            pass 
        
        else:
           
            lst.append(f)
                
print(lst)
[15.0, 9.0, 7.0, 10.0, 4.0, 9.0, 9.0, 12.0, 11.0, 0.0, 15.0, 9.0, 11.0, 6.0, 16.0, 16.0, 8.0, 7.0, 7.0, 8.0, 10.0, 12.0, 7.0, 9.0, 7.0, 13.0, 17.0, 7.0, 8.0, 12.0, 5.0, 16.0, 15.0, 8.0, 12.0, 10.0, 12.0, 13.0, 15.0, 6.0, 9.0, 5.0, 5.0, 9.0, 6.0, 16.0, 1.0, 13.0, 14.0, 16.0, 7.0, 8.0, 8.0, 21.0, 12.0, 8.0, 7.0, 4.0, 7.0, 2.0, 17.0, 4.0, 10.0, 8.0, 7.0, 9.0, 11.0, 6.0, 14.0, 5.0, 10.0, 13.0, 12.0, 13.0, 14.0, 13.0, 9.0, 7.0, 6.0, 9.0, 6.0, 5.0, 10.0, 16.0, 8.0, 10.0, 8.0, 8.0, 6.0, 9.0, 9.0, 17.0, 13.0, 8.0, 7.0, 8.0, 10.0, 21.0, 8.0, 9.0, 5.0, 9.0, 17.0, 12.0, 2.0, 6.0, 4.0, 4.0, 21.0, 10.0, 15.0, 8.0, 9.0, 8.0, 23.0, 5.0, 11.0, 3.0, 7.0, 11.0]
mean(lst)
9.7
r = variance(lst)
print(sqrt(r))
4.34170705692

histogram(lst,bins=20)



        
        
        


        





b)  Internals
import csv 
internal = []

with open("midterm.csv") as file:
    csv_reader = csv.reader(file)
    
    for line in csv_reader:
        try:
            f = float(line[1])
            r = int(f)
            
            
        except:
            pass 
        
        else:
           
            internal.append(r)
                
print(internal)

final = []
for i in range(119):
    final.append((i+1,internal[i]))
    
print(final)
a = list_plot(final,plotjoined = true )

[6, 5, 5, 4, 1, 4, 5, 5, 5, 0, 6, 1, 3, 3, 6, 5, 4, 2, 1, 5, 2, 4, 3, 3, 5, 7, 2, 1, 4, 2, 6, 4, 5, 5, 6, 3, 2, 6, 5, 4, 2, 1, 5, 4, 6, 1, 6, 7, 7, 5, 2, 3, 7, 4, 5, 3, 2, 3, 0, 7, 0, 3, 2, 0, 6, 3, 2, 6, 1, 3, 6, 5, 4, 7, 4, 4, 3, 4, 2, 3, 2, 5, 7, 5, 5, 5, 5, 2, 4, 3, 6, 5, 3, 0, 2, 6, 8, 2, 5, 2, 2, 4, 2, 2, 2, 1, 2, 7, 3, 6, 2, 3, 3, 9, 3, 3, 1, 3, 6]

[(1, 6), (2, 5), (3, 5), (4, 4), (5, 1), (6, 4), (7, 5), (8, 5), (9, 5), (10, 0), (11, 6), (12, 1), (13, 3), (14, 3), (15, 6), (16, 5), (17, 4), (18, 2), (19, 1), (20, 5), (21, 2), (22, 4), (23, 3), (24, 3), (25, 5), (26, 7), (27, 2), (28, 1), (29, 4), (30, 2), (31, 6), (32, 4), (33, 5), (34, 5), (35, 6), (36, 3), (37, 2), (38, 6), (39, 5), (40, 4), (41, 2), (42, 1), (43, 5), (44, 4), (45, 6), (46, 1), (47, 6), (48, 7), (49, 7), (50, 5), (51, 2), (52, 3), (53, 7), (54, 4), (55, 5), (56, 3), (57, 2), (58, 3), (59, 0), (60, 7), (61, 0), (62, 3), (63, 2), (64, 0), (65, 6), (66, 3), (67, 2), (68, 6), (69, 1), (70, 3), (71, 6), (72, 5), (73, 4), (74, 7), (75, 4), (76, 4), (77, 3), (78, 4), (79, 2), (80, 3), (81, 2), (82, 5), (83, 7), (84, 5), (85, 5), (86, 5), (87, 5), (88, 2), (89, 4), (90, 3), (91, 6), (92, 5), (93, 3), (94, 0), (95, 2), (96, 6), (97, 8), (98, 2), (99, 5), (100, 2), (101, 2), (102, 4), (103, 2), (104, 2), (105, 2), (106, 1), (107, 2), (108, 7), (109, 3), (110, 6), (111, 2), (112, 3), (113, 3), (114, 9), (115, 3), (116, 3), (117, 1), (118, 3), (119, 6)]










Minors
import csv 
minor = []

with open("midterm.csv") as file:
    csv_reader = csv.reader(file)
    
    for line in csv_reader:
        try:
            f = float(line[2])
            r = int(f)
            
            
        except:
            pass 
        
        else:
           
            minor.append(r)

print(minor)
final1= []
for i in range(119):
    final1.append((i+1,minor[i]))
    
print("")
print(final1)

list_plot(final1 , plotjoined = true)
[9, 4, 3, 6, 3, 5, 4, 7, 6, 0, 9, 8, 8, 3, 10, 11, 4, 5, 6, 3, 8, 7, 4, 6, 7, 8, 10, 6, 8, 8, 3, 10, 10, 3, 7, 5, 8, 11, 9, 2, 6, 3, 4, 4, 2, 9, 6, 8, 9, 2, 6, 5, 15, 8, 3, 4, 2, 4, 2, 10, 4, 8, 6, 7, 4, 8, 4, 8, 5, 6, 7, 7, 9, 7, 9, 4, 4, 3, 7, 3, 3, 6, 9, 3, 5, 3, 3, 5, 6, 6, 12, 8, 6, 6, 6, 4, 14, 6, 5, 3, 6, 13, 10, 0, 4, 3, 2, 14, 7, 9, 7, 6, 5, 15, 1, 8, 3, 5, 5]

[(1, 9), (2, 4), (3, 3), (4, 6), (5, 3), (6, 5), (7, 4), (8, 7), (9, 6), (10, 0), (11, 9), (12, 8), (13, 8), (14, 3), (15, 10), (16, 11), (17, 4), (18, 5), (19, 6), (20, 3), (21, 8), (22, 7), (23, 4), (24, 6), (25, 7), (26, 8), (27, 10), (28, 6), (29, 8), (30, 8), (31, 3), (32, 10), (33, 10), (34, 3), (35, 7), (36, 5), (37, 8), (38, 11), (39, 9), (40, 2), (41, 6), (42, 3), (43, 4), (44, 4), (45, 2), (46, 9), (47, 6), (48, 8), (49, 9), (50, 2), (51, 6), (52, 5), (53, 15), (54, 8), (55, 3), (56, 4), (57, 2), (58, 4), (59, 2), (60, 10), (61, 4), (62, 8), (63, 6), (64, 7), (65, 4), (66, 8), (67, 4), (68, 8), (69, 5), (70, 6), (71, 7), (72, 7), (73, 9), (74, 7), (75, 9), (76, 4), (77, 4), (78, 3), (79, 7), (80, 3), (81, 3), (82, 6), (83, 9), (84, 3), (85, 5), (86, 3), (87, 3), (88, 5), (89, 6), (90, 6), (91, 12), (92, 8), (93, 6), (94, 6), (95, 6), (96, 4), (97, 14), (98, 6), (99, 5), (100, 3), (101, 6), (102, 13), (103, 10), (104, 0), (105, 4), (106, 3), (107, 2), (108, 14), (109, 7), (110, 9), (111, 7), (112, 6), (113, 5), (114, 15), (115, 1), (116, 8), (117, 3), (118, 5), (119, 5)]













Internals + Minors
list_plot(final,color = "black",plotjoined = true,legend_label = "$internal$" )+list_plot(final1,color = 'red',plotjoined = true,legend_label = "$minor$" )

c)
1)
t = [random.choice(lst) for i in range(20)]
print(t)
print('')
m = mean(t)
print(m)
print('')
r = variance(t)
print(sqrt(r))

#confidence interval

sd = 4.34170705692

z = 1.96  #95 % confidence interval

e = z*sd
p = float(sqrt(20))
print(p)

l = e/p

print("population mean")
print(9.7)

print("lower limit")
print(m-l)
print("upper limit")
print(m+l)

output--[1.0, 13.0, 16.0, 17.0, 11.0, 8.0, 9.0, 10.0, 0.0, 16.0, 8.0, 9.0, 6.0, 5.0, 5.0, 7.0, 13.0, 16.0, 21.0, 10.0]

10.05

5.44324786946
4.472135955
population mean
9.70000000000000
lower limit
8.14716298493792
upper limit
11.9528370150621

2)
t = [random.choice(lst) for i in range(20)]
print(t)
print('')
m = mean(t)
print(m)
print('')
r = variance(t)
print(sqrt(r))

#confidence interval

sd = 4.34170705692

z = 1.96  #95 % confidence interval

e = z*sd
p = float(sqrt(20))
print(p)

l = e/p

print("population mean")
print(9.7)

print("lower limit")
print(m-l)
print("upper limit")
print(m+l)

output--[4.0, 7.0, 2.0, 1.0, 9.0, 4.0, 12.0, 5.0, 8.0, 17.0, 7.0, 16.0, 16.0, 5.0, 9.0, 17.0, 9.0, 3.0, 9.0, 11.0]

8.55

4.99973683518
4.472135955
population mean
9.70000000000000
lower limit
6.64716298493792
upper limit
10.4528370150621

3)
t = [random.choice(lst) for i in range(20)]
print(t)
print('')
m = mean(t)
print(m)
print('')
r = variance(t)
print(sqrt(r))

#confidence interval

sd = 4.34170705692

z = 1.96  #95 % confidence interval

e = z*sd
p = float(sqrt(20))
print(p)

l = e/p

print("population mean")
print(9.7)

print("lower limit")
print(m-l)
print("upper limit")
print(m+l)

output--[5.0, 9.0, 21.0, 14.0, 17.0, 8.0, 9.0, 8.0, 12.0, 12.0, 8.0, 6.0, 9.0, 2.0, 7.0, 9.0, 8.0, 15.0, 14.0, 7.0]

10.0

4.46035165005
4.472135955
population mean
9.70000000000000
lower limit
8.09716298493792
upper limit
11.9028370150621

4)
t = [random.choice(lst) for i in range(20)]
print(t)
print('')
m = mean(t)
print(m)
print('')
r = variance(t)
print(sqrt(r))

#confidence interval

sd = 4.34170705692

z = 1.96  #95 % confidence interval

e = z*sd
p = float(sqrt(20))
print(p)

l = e/p

print("population mean")
print(9.7)

print("lower limit")
print(m-l)
print("upper limit")
print(m+l)

output-
[4.0, 8.0, 16.0, 4.0, 13.0, 6.0, 9.0, 15.0, 12.0, 8.0, 8.0, 8.0, 9.0, 9.0, 12.0, 0.0, 7.0, 7.0, 15.0, 16.0]

9.3

4.31765043318
4.472135955
population mean
9.70000000000000
lower limit
7.39716298493792
upper limit
11.2028370150621


5)

t = [random.choice(lst) for i in range(40)]
print(t)
print('')
m = mean(t)
print(m)
print('')
r = variance(t)
print(sqrt(r))

#confidence interval

sd = 4.34170705692

z = 1.96  #95 % confidence interval

e = z*sd
p = float(sqrt(20))
print(p)

l = e/p

print("population mean")
print(9.7)

print("lower limit")
print(m-l)
print("upper limit")
print(m+l)

output-
[8.0, 12.0, 10.0, 10.0, 9.0, 11.0, 8.0, 7.0, 21.0, 9.0, 5.0, 14.0, 16.0, 15.0, 6.0, 12.0, 8.0, 5.0, 13.0, 6.0, 12.0, 15.0, 6.0, 10.0, 21.0, 17.0, 14.0, 0.0, 10.0, 9.0, 7.0, 8.0, 9.0, 16.0, 11.0, 9.0, 12.0, 6.0, 8.0, 7.0]

10.3

4.33944342408
4.472135955
population mean
9.70000000000000
lower limit
8.39716298493792
upper limit
12.2028370150621

--------------------------------------------------------------------------------------------------



d)

lst = [0,1,2,3,4,5]
randomscores = []
marks = []

for i in range(120):
    t = sum(random.choice(lst) for i in range(5))
    randomscores.append((i+1,t))
    marks.append(t)
print(randomscores)


list_plot(randomscores,legend_label = "$randomscores$",color = 'red',plotjoined = true )

t = float(mean(marks))

print("")
print(t)

[(1, 16), (2, 12), (3, 17), (4, 6), (5, 15), (6, 17), (7, 11), (8, 12), (9, 21), (10, 15), (11, 14), (12, 13), (13, 17), (14, 4), (15, 5), (16, 14), (17, 8), (18, 8), (19, 6), (20, 8), (21, 10), (22, 11), (23, 13), (24, 13), (25, 15), (26, 17), (27, 10), (28, 16), (29, 18), (30, 6), (31, 20), (32, 12), (33, 13), (34, 10), (35, 15), (36, 7), (37, 19), (38, 7), (39, 16), (40, 8), (41, 8), (42, 16), (43, 16), (44, 12), (45, 7), (46, 17), (47, 17), (48, 7), (49, 7), (50, 11), (51, 15), (52, 8), (53, 13), (54, 15), (55, 12), (56, 13), (57, 10), (58, 13), (59, 16), (60, 12), (61, 13), (62, 17), (63, 12), (64, 11), (65, 11), (66, 15), (67, 17), (68, 17), (69, 9), (70, 6), (71, 11), (72, 12), (73, 18), (74, 10), (75, 14), (76, 12), (77, 13), (78, 13), (79, 3), (80, 2), (81, 14), (82, 14), (83, 13), (84, 14), (85, 6), (86, 17), (87, 17), (88, 14), (89, 18), (90, 19), (91, 16), (92, 16), (93, 18), (94, 15), (95, 12), (96, 13), (97, 13), (98, 15), (99, 14), (100, 14), (101, 16), (102, 18), (103, 18), (104, 15), (105, 16), (106, 11), (107, 13), (108, 14), (109, 17), (110, 11), (111, 13), (112, 10), (113, 4), (114, 20), (115, 10), (116, 15), (117, 14), (118, 13), (119, 14), (120, 14)]

12.8666666667



import random
lst = [0,1,2,3,4,5]
randomscores = []
marks = []

for i in range(120):
    t = sum(random.choice(lst) for i in range(5))
    randomscores.append((i+1,t))
    marks.append(t)
print(randomscores)

print("mean of random marks")
t = float(mean(marks))
print(t)


[(1, 9), (2, 11), (3, 17), (4, 11), (5, 13), (6, 16), (7, 18), (8, 6), (9, 12), (10, 14), (11, 8), (12, 15), (13, 13), (14, 8), (15, 9), (16, 14), (17, 5), (18, 10), (19, 17), (20, 16), (21, 7), (22, 15), (23, 16), (24, 10), (25, 11), (26, 8), (27, 15), (28, 16), (29, 15), (30, 13), (31, 16), (32, 11), (33, 13), (34, 14), (35, 17), (36, 15), (37, 15), (38, 13), (39, 12), (40, 13), (41, 10), (42, 6), (43, 18), (44, 18), (45, 17), (46, 20), (47, 6), (48, 15), (49, 6), (50, 12), (51, 9), (52, 9), (53, 15), (54, 15), (55, 15), (56, 8), (57, 10), (58, 11), (59, 13), (60, 9), (61, 16), (62, 11), (63, 17), (64, 9), (65, 13), (66, 20), (67, 18), (68, 9), (69, 11), (70, 12), (71, 10), (72, 21), (73, 18), (74, 13), (75, 12), (76, 13), (77, 11), (78, 17), (79, 17), (80, 13), (81, 12), (82, 11), (83, 16), (84, 12), (85, 13), (86, 13), (87, 14), (88, 19), (89, 15), (90, 8), (91, 18), (92, 21), (93, 6), (94, 10), (95, 12), (96, 14), (97, 13), (98, 15), (99, 12), (100, 12), (101, 13), (102, 12), (103, 14), (104, 8), (105, 11), (106, 12), (107, 9), (108, 12), (109, 14), (110, 18), (111, 13), (112, 13), (113, 8), (114, 11), (115, 10), (116, 15), (117, 18), (118, 8), (119, 18), (120, 11)]
mean of random marks
12.8666666667

histogram(randomscores,bins=2)














e)
mean = 9.7     actual mean
mean = 12.86   random mean
1.Random mean (randomly marks given) is greater than actual mean(actual marks scored)
random mean > actual mean 
2.My marks remain same but changes are observerd.
3.avg has increased by 3.16.
4.Some has greater marks in actual score but less when they are distributed randomly.
5.some got more marks as compared to their actual marks.

----------------------------------------------------------------------------------------------------------------------------------------------

Assignment-11
Name -Yashdeep patwa 
Roll no -19/11/EC/056
Date-12/05/2020

Ex 1. (Covid Study (cont.)) Examine/update all the data for your state and country and summarize your work in analyzing Covid19. What are the 5 key ideas you got from your study? If you were the Prime Minister, how would you manage the country during this crisis? Write in your own words and support your arguments with your analysis. 

India’s data -

import csv
final = []

with open("covid20.csv",'r') as csv_file:
    csv_reader = csv.reader(csv_file)
    
    for line in csv_reader: 
        try:
            f = float(line[1])
            r = int(f)
            
        except ValueError:
            pass 
        
        else:
            final.append(r)
            
print(final)
bar_chart(final,color='grey',width= 0.9,legend_label = "$Indiacovid$")

[1, 2, 3, 5, 6, 28, 30, 31, 34, 39, 44, 50, 60, 73, 81, 97, 107, 118, 137, 151, 173, 223, 283, 360, 434, 519, 606, 694, 834, 918, 1024, 1251, 1397, 1834, 2069, 2547, 3072, 3577, 4281, 4789, 5274, 5865, 6761, 7529, 8447, 9352, 10815, 11933, 12759, 13835, 14792, 16116, 17656, 18985, 20471, 21700, 23452, 24942, 26917, 28380, 29974, 31787, 33610, 35365, 37776, 40263, 42836, 46711, 49391, 52952, 56342, 59662, 62939, 67152, 70756]















MadhyaPradesh’s data-

import csv
final = []

with open("covid20_MadhyaPradesh.csv",'r') as csv_file:
    csv_reader = csv.reader(csv_file)
    
    for line in csv_reader:
        try:
            f = float(line[1])
            r = int(f)
            
        except ValueError:
            pass 
        
        else:
            final.append(r)
            
print(final)
bar_chart(final,color='grey',width= 0.9,legend_label = "$MadhyaPradesh$")

[0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 4, 4, 6, 7, 14, 20, 30, 30, 30, 47, 47, 66, 99, 104, 104, 165, 165, 229, 229, 259, 259, 443, 564, 604, 730, 987, 1120, 1308, 1355, 1407, 1485, 1540, 1592, 1695, 1852, 1952, 2096, 2168, 2368, 2561, 2660, 2719, 2719, 2846, 2942, 3049, 3049, 3138, 3252, 3341, 3614, 3614, 3785]
























New cases data -India

import csv
final = []

with open("covid20_New.csv",'r') as csv_file:
    csv_reader = csv.reader(csv_file)
    
    for line in csv_reader:
        try:
            f = float(line[1])
            r = int(f)
            
        except ValueError:
            pass 
        
        else:
            final.append(r)
            
print(final)
bar_chart(final,color='grey',width= 0.9,legend_label = "$Newcases$")

[1, 1, 1, 2, 1, 22, 2, 1, 3, 5, 5, 6, 10, 13, 8, 16, 10, 11, 19, 14, 22, 50, 60, 77, 74, 85, 87, 88, 140, 84, 106, 227, 146, 437, 235, 478, 525, 505, 704, 508, 485, 591, 896, 768, 918, 905, 1463, 1118, 826, 1076, 957, 1324, 1540, 1329, 1486, 1229, 1752, 1490, 1975, 1463, 1594, 1813, 1823, 1755, 2411, 2487, 2573, 3875, 2680, 3561, 3390, 3320, 3277, 4213, 3604]






















Histogram-India

import csv
final = []

with open("covid20.csv",'r') as csv_file:
    csv_reader = csv.reader(csv_file)
    
    for line in csv_reader: 
        try:
            f = float(line[1])
            r = int(f)
            
        except ValueError:
            pass 
        
        else:
            final.append(r)
            
print(final)
histogram(final,bins=20,color='grey',rwidth=0.8)

[1, 2, 3, 5, 6, 28, 30, 31, 34, 39, 44, 50, 60, 73, 81, 97, 107, 118, 137, 151, 173, 223, 283, 360, 434, 519, 606, 694, 834, 918, 1024, 1251, 1397, 1834, 2069, 2547, 3072, 3577, 4281, 4789, 5274, 5865, 6761, 7529, 8447, 9352, 10815, 11933, 12759, 13835, 14792, 16116, 17656, 18985, 20471, 21700, 23452, 24942, 26917, 28380, 29974, 31787, 33610, 35365, 37776, 40263, 42836, 46711, 49391, 52952, 56342, 59662, 62939, 67152, 70756]























Comment-
Looking at pattern of these graphs they are exponentially following the trend.Total number of cases are increasing day by day.Though number of new cases per day are varying but ultimately it is increasing.
Rapid and continous increase of number of cases will lead to healthcare crises such as number of doctors handeling the pateints , proper vaccine / medicines required to develop the immunity.Hence to ensure proper functioning of healtthcare department the spread of cases must be controlled.
Graphs show exponential increase of cases that seem to be harsh. First of all as a PM I will ensure the proper healthcare facilities are reaching to the people.Basic needs of people will be the first priority.Diseases which spread from one people to other people needs distancing from the infected people, Areas such as stations, airports ,markets etc should be following the social distancing guidelines.
Conclusion-
1.Graph is increasing in nature which means total number covid-cases are increasing.
(after observing 5 graphs of weekly bar chart) 
2.Graph is following exponential function.
3.bar chart of state is also increasing in nature.
 
Ex 2. (z-Test) For this problem, use the midterm data from Ex 3c. in Assignment 10. Take a sample of 20 randomly chosen scores. Create a suitable null hypothesis for the ’real mean’ of the scores. Apply the z-test and interpret your answer. Do the same to the data set generated in Ex 3d. in A10. 

Null hypothesis: H 0:   μ = 9.7
alternative hypothesis: H a : μ  ≠ 9.7

import csv 
lst = []

with open("midterm.csv") as file:
    csv_reader = csv.reader(file)
    
    for line in csv_reader:
        try:
            f = float(line[3])
            r = int(f)
            
            
        except:
            pass 
        
        else:
           
            lst.append(r)
                
            
x = float(mean(lst))
v = variance(lst)
sigma = float(sqrt(v))
print(float(mean(lst)))      
t = [random.choice(lst) for i in range(20)]          #choses 20 random scores from 120 students
print(t)
y = float(mean(t))
print(float(mean(t)))


#z-test
diff_mean = (x-y)*float(sqrt(20))
z = diff_mean/sigma

print(z)
if z>-1.96 and z<1.96:                                  #taking alpha as 0.05
    print("null hypotheses is accepted")
    
else:
    print("null hypotheses is rejected")

9.7
[2, 17, 6, 16, 17, 8, 7, 11, 9, 10, 8, 2, 8, 9, 5, 2, 11, 21, 9, 12]
9.5
0.206008185093
null hypotheses is accepted



Null hypothesis: H 0:   μ = 9.7
alternative hypothesis: H a : μ  ≠ 9.7

lst = [0,1,2,3,4,5]
randomscores = []
marks = []

for i in range(120):
    t = sum(random.choice(lst) for i in range(5))
    marks.append(t)

y = float(mean(marks))
v = variance(marks)
sigma = float(sqrt(v))

# print(marks)
random_scores = [random.choice(marks) for i in range(20)]          #chosing 20 random scores from 120                                                                                                                                              -                                                                                                                    random scored students marks 
print(random_scores)
x = float(mean(random_scores))
print(x)

#z-test
diff_mean = (x-y)*float(sqrt(20))
z = diff_mean/sigma
print(z)
if z>-1.96 and z<1.96:                                      #taking alpha as 0.05
    print("null hypotheses is accepted")
    
else:
    print("null hypotheses is rejected")

[8, 17, 10, 8, 14, 18, 12, 18, 12, 15, 15, 14, 8, 9, 8, 10, 8, 10, 10, 10]
11.7
-0.476128957908
null hypotheses is accepted



Ex 3. (Student’s t-Distribution) The probability density function of the Student’s t-distribution is given by:
f(x) :=
Γ(n+1 2 ) √nπ Γ(n/2)#1 + x2 n#−n+1 2
.
Here n denotes the degrees of freedom. Of the expressions appearing in this pdf, you may not be familiar with the Gamma function. It is also one of the fundamental functions, like polynomials, exponential and logs, and the trigonometric functions. It is deﬁned as Γ(x) :=Z∞ 0 tx−1e−tdt. This is deﬁned only when <(x) > 0, where this notation stands for the real part of the complex number x. One can prove that Γ(x + 1) = xΓ(x)
and then use this property to extend the deﬁnition of the Gamma function for all x except x = 0,−1,−2,···. Right now, don’t worry about all this. Just know that one can calculate with these functions using Sage. (Note that Γ(n + 1) = n!, when n is a non-negative integer.) The distribution function is given by F(x) =Zx −∞ f(x)dx. You can use this to compute at various values of x. The mean of this distribution is 0 and variance is n/(n−2). (a.) Use Sage to verify the entries of Table 1 on page 492.
(b.) Repeat Q2 above with a sample of 5 randomly chosen scores. Use your function in part (a.) to compute the P values. Interpret your answer.

a)

n =1
result =  float(integrate((gamma((n+1)/2)/(sqrt(n*pi))*gamma(n/2))*(1+ x^2/n)^-((n+1)/2),x,-oo,oo))
print(result)
3.14159265359
n =1
result =  float(integrate((gamma((n+1)/2)/(sqrt(n*pi))*gamma(n/2))*(1+ x^2/n)^-((n+1)/2),x,3.08,oo))
print(result)
0.313938213337

0.3139/3.1415          #dividing the area to get value of p

0.0999204201814420      #p-value   approx 10 percent


n =2
result =  float(integrate((gamma((n+1)/2)/(sqrt(n*pi))*gamma(n/2))*(1+ x^2/n)^-((n+1)/2),x,-oo,oo))
print(result)
1.0
n =2
result =  float(integrate((gamma((n+1)/2)/(sqrt(n*pi))*gamma(n/2))*(1+ x^2/n)^-((n+1)/2),x,1.89,oo))
print(result)
0.099666109096

0.099666109096/1.0            #dividing the area to get value of p

0.099666109096             #p-value  approx 10 percent 

similarly we can find for n=3,4,5,.. by changing value of n


b)

import random
import csv 
lst = []

with open("midterm.csv") as file:
    csv_reader = csv.reader(file)
    
    for line in csv_reader:
        try:
            f = float(line[3])
            r = int(f)
            
            
        except:
            pass 
        
        else:
           
            lst.append(r)
                
            
x = float(mean(lst))
v = variance(lst)
sigma = float(sqrt(v))
print(float(mean(lst)))      
t = [random.choice(lst) for i in range(5)]
print(t)
y = float(mean(t))
print(float(mean(t)))
#z-test
diff_mean = (x-y)*float(sqrt(20))
z = diff_mean/sigma

print(z)





9.7
[10, 7, 11, 8, 11]
9.4
0.15450613882         #value of z 

n =5-1
result1 =  float(integrate((gamma((n+1)/2)/(sqrt(n*pi))*gamma(n/2))*(1+ x^2/n)^-((n+1)/2),x,-oo,oo))
print(result1)
1.0
n =5-1
result2 =  float(integrate((gamma((n+1)/2)/(sqrt(n*pi))*gamma(n/2))*(1+ x^2/n)^-((n+1)/2),x,z,oo))
print(result2)
0.442346559428

p_value = result2/result1
print(p_value)
0.442346559428


Ex 4. (z-test for diﬀerences) Apply the z-test for diﬀerences to compare the two datasets in Q2. Make an appropriate Null Hypothesis for the data sets and comment on your results. Take a sample of size 20 again. 

Null hypothesis: H 0:  μ 1  = μ 1 2
alternative hypothesis: H a : μ 1 ≠ μ 2
# μ 1 and μ 2 are mean of population of two datasets


lst = [12, 6, 9, 8, 8, 9, 7, 14, 9, 8, 8, 13, 7, 9, 8, 8, 13, 3, 17, 5]
randomscored_lst = [8, 17, 10, 8, 14, 18, 12, 18, 12, 15, 15, 14, 8, 9, 8, 10, 8, 10, 10, 10]

mean_x = mean(lst)
mean_y = mean(randomscored_lst)

var1 = variance(lst)
var2 = variance(randomscored_lst)

diff_mean = (mean_x - mean_y)*sqrt(20)                #difference of population mean becomes 
error_avg = sqrt(var1^2 + var2^2)                                                                               (assumed)

z = float(diff_mean/error_avg)
print(z)

if z>-1.96 and z<1.96:
    print("null hypotheses is accepted")
    
else:
    print("null hypotheses is rejected")

-0.730567878395
null hypotheses is accepted

Ex 5. (χ2-test for independence) This problem is based on an idea of Soundarajan and Oliver. For this problem, ﬁgure out and use the appropriate R functions from Sage. If that is not feasible, you can look for deﬁnitions of χ2 distribution from Wikipedia (as I did for the t-test above) and implement suitable functions in Sage. The idea is to statistically examine prime numbers. The nth prime number can be easily generated in Sage. We use the command nth prime(n). Note that all prime numbers bigger than 5 will have last digit either 1, 3, 7 or 9. Say a prime has last digit 7. What can be said about the last digit of the next prime number? For example, 7 is a prime with last digit 7. The next prime number is 11 with last digit 1. Similarly 17 is followed by 19. Now the last digit is 9.
(a.) Make a list of the last digits of prime numbers bigger than 5 which has 100,000 entries. (Just show me ﬁrst and last entry.) Call this list prime last digit.
(b.) From this list, make a list prime7 with the digits that follow a 7. For example the ﬁrst 7 is followed by a 1. So 1 should be included in prime7. Statistically analyze prime7 by making a frequency table, bar charts, etc., showing the number of 1s, 3s, 7s, 9s following the 7.
(c.) The list prime7 contains 1, 3, 7 and 9. Use the χ2 test to check whether these digits appear randomly. If they were random, there is a probability of 1/4 for each digit. Follow the analysis of Example 1 on p. 524.

a)

prime_last_digit = []

for i in range(4,100000):
    t = nth_prime(i)%10
    prime_last_digit .append(t)
    
print(prime_last_digit )
    
first entry -7
last entry-9


b)

prime7 = []

prime_last_digit = []

count = 0
for i in range(4,100000):
    t = nth_prime(i)%10
    prime_last_digit.append(t)
    
    count = count + 1

con = 0    
for j in range(99996):
    if prime_last_digit[j] == 7:
        con = con +1
        prime7.append(prime_last_digit[j+1])
        
 print(con)        
print(prime7)


c)

count1 = 0
count2 = 0
count3 = 0
count4 = 0


for i in range(25015):
    if prime7[i] == 1:
        count1 = count1 +1
        
    elif prime7[i] == 3:
        count2 = count2 +1
        
        
    elif prime7[i] == 7:
        count3 = count3 +1
        
    elif prime7[i] == 9:
        count4 = count4 +1
        
        
print("frequency of one")        
print(count1)
print("frequency of three")  
print(count2)
print("frequency of seven")  
print(count3)
print("frequency of nine")  
print(count4)
  
ef = 6253.75                                #(ef = expected frequency)

x1 = (ef - count1)^2
x2 = (ef - count2)^2
x3 = (ef - count3)^2
x4 = (ef - count4)^2

ki_square = (x1+x2+x3+x4)/ef

print(ki_square)
        
frequency of one
6438
frequency of three
6928
frequency of seven
3627
frequency of nine
8022
-184.250000000000
1681.40471716970


--------------------------------------------------------------------------------------------------


    
        









