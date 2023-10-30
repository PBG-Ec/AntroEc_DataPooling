This dataset integrates more than three decades of public health
databases focusing on the Ecuadorian population. It combines individual
data from six distinct datasets, encompassing a total of 379939
individuals and 69 variables. This consolidated database includes
anthropometric measurements, along with socio-economic characteristics
of both households and individuals. Within this database, there are
56759 instances of child-mother pairs, involving children under the age
of 5, as well as 44680 unique mothers. Additionally, the dataset
comprises 278500 other individuals, primarily consisting of individuals
over the age of 5 and Women in Reproductive Age (WRA).

# Sources

The dataset was created using the data collected from the following
national health surveys:

-   DANS 1986: Diagnóstico de la situación alimentaria, nutricional y de
    salud de la población ecuatoriana menor de cinco años (Wilma B.
    Freire et al. 1988),
-   ENDEMAIN 1999: Encuesta Demografía y de Salud Materna e Infantil
    (Catón, Inés, and Stupp 2005),
-   ENDEMAIN 2004: Encuesta Demografía y de Salud Materna e Infantil
    (Ordóñez, Stupp, and Monteith 2005),
-   ENSANUT 2012: Encuesta Nacional de Salud y Nutrición (Freire et al.
    2014),
-   ECV 2014 : Encuesta Nacional de Condiciones de Vida (INEC 2014),
-   ENSANUT 2018 : Encuesta Nacional de Salud y Nutrición 2018 (INEC,
    n.d.) .

# Available data

The total sampled population of children under 5 years old remained
below 10,000 from 1986 to 2012. Subsequently, there was a notable
increase in the 2014 and 2018 surveys. Additionally, anthropometric data
for other population groups has shown a steady increase from 2004 to
2018.

<table class="table" style="margin-left: auto; margin-right: auto;">
<caption>
Total of observations
</caption>
<thead>
<tr>
<th style="text-align:left;">
Group
</th>
<th style="text-align:left;">
1986
</th>
<th style="text-align:left;">
1999
</th>
<th style="text-align:left;">
2004
</th>
<th style="text-align:left;">
2012
</th>
<th style="text-align:left;">
2014
</th>
<th style="text-align:left;">
2018
</th>
<th style="text-align:left;">
Total
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;">
Mothers
</td>
<td style="text-align:left;">
5408
</td>
<td style="text-align:left;">
2177
</td>
<td style="text-align:left;">
3963
</td>
<td style="text-align:left;">
7451
</td>
<td style="text-align:left;">
8996
</td>
<td style="text-align:left;">
16685
</td>
<td style="text-align:left;">
44680
</td>
</tr>
<tr>
<td style="text-align:left;">
Child\<5yo
</td>
<td style="text-align:left;">
7802
</td>
<td style="text-align:left;">
3056
</td>
<td style="text-align:left;">
5147
</td>
<td style="text-align:left;">
8964
</td>
<td style="text-align:left;">
11400
</td>
<td style="text-align:left;">
20390
</td>
<td style="text-align:left;">
56759
</td>
</tr>
<tr>
<td style="text-align:left;">
Other
</td>
<td style="text-align:left;">
179
</td>
<td style="text-align:left;">
20718
</td>
<td style="text-align:left;">
7006
</td>
<td style="text-align:left;">
44214
</td>
<td style="text-align:left;">
89298
</td>
<td style="text-align:left;">
117085
</td>
<td style="text-align:left;">
278500
</td>
</tr>
<tr>
<td style="text-align:left;">
Total
</td>
<td style="text-align:left;">
13389
</td>
<td style="text-align:left;">
25951
</td>
<td style="text-align:left;">
16116
</td>
<td style="text-align:left;">
60629
</td>
<td style="text-align:left;">
109694
</td>
<td style="text-align:left;">
154160
</td>
<td style="text-align:left;">
379939
</td>
</tr>
</tbody>
</table>

# Anthropometric data

Anthropometric indicators were calculated for three age groups
separately: 0 to under 5 years, 5 to 19 years and 20 to 59 years.
Standardized table and calculation methodology employed in the first two
groups were conducted with igrowup (Stunting:Haz\<-2, OW:2\>zBMI\>=3,
OB:zBMI\>3) and who2007 (OW:1\>zBFA\>=2, OB: zBFA \>2) package provided
by the WHO \[5\]. For the third group from 20 to 59 years, BMI was
calculated and cut-offs published by the WHO were applied to evaluate
overweight and obesity (OW:25\>=BMI\>30, OB:BMI\>=30). For each survey
the availability of pregnancy state (*embrz*) provided a filter to
exclude all women in pregnancy from anthropometrics status estimation.
Anthropometric indicators were computed separately for three distinct
age categories: 0 to under 5 years, 5 to 19 years, and 20 to 59 years.
The standardized table and calculation approach employed for the first
two age groups were executed using the “igrowup” package
(Stunting:Haz\<-2, OW:2\>zBMI\>=3, OB:zBMI\>3) and the “who2007” package
(OW:1\>zBFA\>=2, OB: zBFA \>2), both provided by the World Health
Organization (Onis et al. 2006).

For the third age group (20 to 59 years), Body Mass Index (BMI) was
computed, and the BMI thresholds published by the World Health
Organization were used to determine overweight and obesity status
(Overweight: 25 \<= BMI \< 30, Obesity: BMI \>= 30).

In each survey, the availability of pregnancy status (*embrz*) was
utilized as a filter to exclude all pregnant women from the estimation
of anthropometric status.

# Complex Survey design

For each individual database, the original survey design was taken into
account, incorporating sampling weights (*pw*), strata (*strata*), and
primary sampling units (*psu*) into the final consolidated database. The
sampling design ensured that representativeness was achieved at the
provincial level for the most recent surveys (ENDEMAIN 2004, ENSANUT
2012, ENSANUT 2018), and at the geographical domains (Highlands, Coast,
Amazon, Quito and Guayaquil).

Over the years, the size of the surveys grew substantially, covering a
broader geographical area. Notably, in 1986, surveys did not encompass
the Amazon region or the Galapagos Islands due to technical constraints.

In the 2018 survey, there was no self-representation available for the
two main cities in the country: Quito and Guayaquil.

<table class="table" style="margin-left: auto; margin-right: auto;">
<caption>
Observations per Dominion
</caption>
<thead>
<tr>
<th style="text-align:left;">
Region
</th>
<th style="text-align:left;">
Area
</th>
<th style="text-align:left;">
Area
</th>
<th style="text-align:left;">
1986
</th>
<th style="text-align:left;">
1999
</th>
<th style="text-align:left;">
2004
</th>
<th style="text-align:left;">
2012
</th>
<th style="text-align:left;">
2014
</th>
<th style="text-align:left;">
2018
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;">
Sierra
</td>
<td style="text-align:left;">
Urban
</td>
<td style="text-align:left;">
Quito
</td>
<td style="text-align:left;">
2057
</td>
<td style="text-align:left;">
2761
</td>
<td style="text-align:left;">
1223
</td>
<td style="text-align:left;">
3253
</td>
<td style="text-align:left;">
4199
</td>
<td style="text-align:left;">
0
</td>
</tr>
<tr>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
Other
</td>
<td style="text-align:left;">
1237
</td>
<td style="text-align:left;">
4104
</td>
<td style="text-align:left;">
3262
</td>
<td style="text-align:left;">
13067
</td>
<td style="text-align:left;">
19700
</td>
<td style="text-align:left;">
34921
</td>
</tr>
<tr>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
Subtotal
</td>
<td style="text-align:left;">
3294
</td>
<td style="text-align:left;">
6865
</td>
<td style="text-align:left;">
4485
</td>
<td style="text-align:left;">
16320
</td>
<td style="text-align:left;">
23899
</td>
<td style="text-align:left;">
34921
</td>
</tr>
<tr>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
Rural
</td>
<td style="text-align:left;">
Subtotal
</td>
<td style="text-align:left;">
3284
</td>
<td style="text-align:left;">
4602
</td>
<td style="text-align:left;">
4383
</td>
<td style="text-align:left;">
11234
</td>
<td style="text-align:left;">
28427
</td>
<td style="text-align:left;">
23517
</td>
</tr>
<tr>
<td style="text-align:left;">
Costa
</td>
<td style="text-align:left;">
Urban
</td>
<td style="text-align:left;">
Guayaquil
</td>
<td style="text-align:left;">
4343
</td>
<td style="text-align:left;">
8509
</td>
<td style="text-align:left;">
4217
</td>
<td style="text-align:left;">
11404
</td>
<td style="text-align:left;">
24383
</td>
<td style="text-align:left;">
41987
</td>
</tr>
<tr>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
Other
</td>
<td style="text-align:left;">
2182
</td>
<td style="text-align:left;">
4398
</td>
<td style="text-align:left;">
2782
</td>
<td style="text-align:left;">
8996
</td>
<td style="text-align:left;">
19076
</td>
<td style="text-align:left;">
41987
</td>
</tr>
<tr>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
Subtotal
</td>
<td style="text-align:left;">
2161
</td>
<td style="text-align:left;">
4111
</td>
<td style="text-align:left;">
1435
</td>
<td style="text-align:left;">
2408
</td>
<td style="text-align:left;">
5307
</td>
<td style="text-align:left;">
0
</td>
</tr>
<tr>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
Rural
</td>
<td style="text-align:left;">
Subtotal
</td>
<td style="text-align:left;">
2468
</td>
<td style="text-align:left;">
5975
</td>
<td style="text-align:left;">
1786
</td>
<td style="text-align:left;">
4238
</td>
<td style="text-align:left;">
11880
</td>
<td style="text-align:left;">
13531
</td>
</tr>
<tr>
<td style="text-align:left;">
Amazonia
</td>
<td style="text-align:left;">
Urban
</td>
<td style="text-align:left;">
Subtotal
</td>
<td style="text-align:left;">
0
</td>
<td style="text-align:left;">
0
</td>
<td style="text-align:left;">
451
</td>
<td style="text-align:left;">
6816
</td>
<td style="text-align:left;">
5276
</td>
<td style="text-align:left;">
13959
</td>
</tr>
<tr>
<td style="text-align:left;">
</td>
<td style="text-align:left;">
Rural
</td>
<td style="text-align:left;">
Subtotal
</td>
<td style="text-align:left;">
0
</td>
<td style="text-align:left;">
0
</td>
<td style="text-align:left;">
457
</td>
<td style="text-align:left;">
8723
</td>
<td style="text-align:left;">
14042
</td>
<td style="text-align:left;">
21137
</td>
</tr>
<tr>
<td style="text-align:left;">
Galapagos
</td>
<td style="text-align:left;">
Galapagos
</td>
<td style="text-align:left;">
Galapagos
</td>
<td style="text-align:left;">
0
</td>
<td style="text-align:left;">
0
</td>
<td style="text-align:left;">
337
</td>
<td style="text-align:left;">
1894
</td>
<td style="text-align:left;">
1787
</td>
<td style="text-align:left;">
5108
</td>
</tr>
<tr>
<td style="text-align:left;">
Total
</td>
<td style="text-align:left;">
Total
</td>
<td style="text-align:left;">
Total
</td>
<td style="text-align:left;">
13389
</td>
<td style="text-align:left;">
25951
</td>
<td style="text-align:left;">
16116
</td>
<td style="text-align:left;">
60629
</td>
<td style="text-align:left;">
109694
</td>
<td style="text-align:left;">
154160
</td>
</tr>
</tbody>
</table>

# Imputation of data

In the 1986 dataset, missing day of birth values for Women in
Reproductive Age (WRA) and children were imputed using the methodology
outlined in the DHS approach (refer to: (Rutstein and Rojas 2006)), with
months being used for missing values. In subsequent surveys, no
additional imputation was conducted due to the comprehensive nature of
the data and the limited impact of missing values.

For the 2012 survey, anthropometric data was evaluated independently of
the reproductive survey. Consequently, a portion of cases did not
contain information about the number of children (2200 cases out of
21296 cases), although this constituted less than the 10% threshold that
would warrant applying an imputation method. An imputation technique
involving chained equations was employed, considering variables such as
age groups, region, education, and crowding. This regression-based
algorithm iteratively filled in missing values across multiple
variables. The approach followed a chained equations strategy, utilizing
fully conditional specification (FCS) in the prediction equations.

# Household material well being index

This index was created by utilizing unmet essential requirements, acting
as a surrogate measure for poverty, with a particular focus on the
tangible dimension. To account for the broad time frame of the data, the
elements were consolidated to encompass data from diverse surveys. The
Unmet Basic Needs (UBN) index offers a means to establish a metric for
well-being grounded in critical physical necessities related to housing
and infrastructure, especially in situations where data is limited (see:
(Hammill 2009)). The components integrated into this index (referred to
as *ics* in the database) were:

-   Crowding more than three persons per room;
-   Housing: living in a house made of irregular materials considering
    floor, walls and house type;
-   Sanitation : not having an indoor flush toilet;
-   Cooking fuel: not using gas or electricity as cooking energy;
-   Water: not having an indoor tubed water;
-   Waste disposal: not accessing to motorized garbage disposal.

Sum of each component (unweigthed) and classification per 2 points
category was calculated to build the final index.

# Reference

Catón, Olmedo Toledo, Herrera Herrera Inés, and Paul Stupp. 2005.
*Encuesta Demografía y de Salud Materna e Infantil ENDEMAIN-99*.

Freire, W., M. Ramírez, P. Belmont, M. Mendieta, K. Silva, N. Romero,
and R. Monge. 2014. *Encuesta Nacional de Salud y Nutrición 2012.
Ensanut-Ecu 2012 (Primera, Vol. Tomo 1). Quito*.

Hammill, Matthew. 2009. “Income Poverty and Unsatisfied Basic Needs.”

INEC. 2014. “Encuesta Nacional de Condiciones de Vida.” Quito, Ec.

———. n.d. “Encuesta Nacional de Salud y Nutrición 2018.
ECU-INEC-DIES-ENSANUT-2018-V1.4.”

Onis, Mercedes de, Cutberto Garza, Adelheid W. Onyango, and Reynaldo
Martorell. 2006. *WHO Child Growth Standards*. Taylor & Francis
Philadelphia, PA.

Ordóñez, J., P. W. Stupp, and R. Monteith. 2005. *Endemain 2004: Informe
Final. Encuesta Demografía y de Salud Materna e Infantil: Informe Final
\[Demographic, Maternal and Infant Health Survey 2004: Final Report\]*.

Rutstein, Shea Oscar, and Guillermo Rojas. 2006. “Guide to DHS
Statistics.” *Calverton, Maryland: ORC Macro*.
<http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.431.8235&rep=rep1&type=pdf>.

Wilma B. Freire, Henry Dirren, José O. Mora, Pedro Arenales, Edmundo
Granda, Jaime Breilh, Arturo Campaña, Rubén Paéz, Luis Darquea, and
Eduardo Molina. 1988. “Diagnóstico de La Situación Alimentaria
Nutricional y de Salud de La Población Ecuatoriana Menor de Cinco Años
(DANS).” Quito, Ecuador.
