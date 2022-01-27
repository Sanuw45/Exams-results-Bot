<h1 align="center">Donents.lk Bot</h3>
<p align="center">
 <a href="https://github.com/UvinduBro/Exams-results-Bot">
<img src="https://socialify.git.ci/UvinduBro/Exams-results-Bot/image?description=1&descriptionEditable=Sri%20Lanka%20Exam%20Results%20Bot%20%F0%9F%93%83%0AThis%20Bot%20can%20Collect%20Grade%205%20%2C%20O%2FL%20%2C%20A%2FL%20results%20%F0%9F%93%9Ain%20Second.%0APowered%20by%20Department%20Of%20Examination&font=Raleway&forks=1&issues=1&language=1&logo=https%3A%2F%2Fwww.uvindubro.tk%2Flogo.png%2Fsticker.png&owner=1&pattern=Diagonal%20Stripes&pulls=1&stargazers=1&theme=Dark" alt="Exams-results-Bot" width="640" height="320" />
 </a>
</p>
<p align="">

    <a href="https://heroku.com/deploy?template=https://github.com/Sanuw45/Exams-results-Bot">

    <img src="https://github.com/nikhileashy/justfor_testing/blob/main/herokudeploy-01-cropped.svg" alt="herokudeploy-01" border="0" height="90" width="285"></a>

</p>




## How to use the bot
 
`/start` : Start Donents.lk Bot.

`/help` : More information about Donents.lk Bot.

`/al` `INDEX_NUMBER` : Get A/L Exam Results.

`/ol` `INDEX_NUMBER` : Get O/L Exam Results.

`/g5` `INDEX_NUMBER` : Get Grade 5 Scholarship Exam Results.

<br>

# What does it show ?
* Grade 5 Scholarship Exam Results
* O/L Exam Results
* A/L Exam Results

<br>
<br>

## Contributors

![GitHub Contributors Image](https://contrib.rocks/image?repo=UvinduBro/Exams-results-Bot)

<br>

## Specially Thanks

[GD Hiruna](https://github.com/hirunaofficial) Tell me about the API

<br>


##  Developers
* Me [UvinduBro](https://github.com/UvinduBro)


<br>

## Apache License 2.0

###  Special Notice for the Sri Lankan කාලකණ්ණී

![image](https://user-images.githubusercontent.com/79355885/129180032-66681914-e515-4c5e-a9ea-719e042fd46b.png)



<br><br><br>


## Getting Data From Department of Examinations API

### AL Results
URL : https://www.doenets.lk/result/service/AlResult/{INDEX}

```{
examination: "G.C.E. (A/L) EXAMINATION",
year: "2020",
name: "PARANA GAMAGE NAVINI RAVISHKA PRIYANTHA",
indexNo: "1329054",
nic: "200179304010",
districtRank: "1 (NEW)",
islandRank: "2 (NEW)",
marks: null,
status: null,
zScore: "2.9604",
stream: "BIOSYSTEMS TECHNOLOGY",
subjectResults: [
{
subjectName: "INFORMATION & COMMUNICATION TECHNOLOGY",
subjectResult: "A"
},
{
subjectName: "BIO SYSTEMS TECHNOLOGY",
subjectResult: "A"
},
{
subjectName: "SCIENCE FOR TECHNOLOGY",
subjectResult: "A"
},
{
subjectName: "COMMON GENERAL TEST",
subjectResult: "066"
},
{
subjectName: "GENERAL ENGLISH",
subjectResult: "A"
}
],
studentInfo: [
{
param: "Examination",
value: "G.C.E. (A/L) EXAMINATION"
},
{
param: "Year",
value: "2020"
},
{
param: "Syllabus",
value: "NEW"
},
{
param: "Name",
value: "PARANA GAMAGE NAVINI RAVISHKA PRIYANTHA"
},
{
param: "Index Number",
value: "1329054"
},
{
param: "NIC Number",
value: "200179304010"
},
{
param: "District Rank",
value: "1 (NEW)"
},
{
param: "Island Rank",
value: "2 (NEW)"
},
{
param: "Z-Score",
value: "2.9604"
},
{
param: "Subject Stream",
value: "BIOSYSTEMS TECHNOLOGY"
}
]
}
```


### OL Results
URL : https://www.doenets.lk/result/service/OlResult/{INDEX}

```{
examination: "G.C.E. (O/L) EXAMINATION (After Rescrutiny)",
year: "2019",
name: "PAVANI HIRUSHIKA RAJAPAKSHE",
indexNo: "90114523",
nic: null,
districtRank: null,
islandRank: null,
marks: null,
status: null,
zScore: null,
stream: null,
subjectResults: [
{
subjectName: "BUDDHISM",
subjectResult: "A"
},
{
subjectName: "SINHALA LANGUAGE & LITT.",
subjectResult: "B"
},
{
subjectName: "ENGLISH LANGUAGE",
subjectResult: "B"
},
{
subjectName: "MATHEMATICS",
subjectResult: "A"
},
{
subjectName: "HISTORY",
subjectResult: "A"
},
{
subjectName: "SCIENCE",
subjectResult: "B"
},
{
subjectName: "MUSIC (ORIENTAL)",
subjectResult: "A"
},
{
subjectName: "BUSINESS & ACCT. STUDIES",
subjectResult: "A"
},
{
subjectName: "HEALTH & PHYSICAL EDUCAT.",
subjectResult: "B"
}
],
studentInfo: [
{
param: "Examination",
value: "G.C.E. (O/L) EXAMINATION (After Rescrutiny)"
},
{
param: "Year",
value: "2019"
},
{
param: "Name",
value: "PAVANI HIRUSHIKA RAJAPAKSHE"
},
{
param: "Index Number",
value: "90114523"
},
{
param: "NIC Number",
value: ""
}
]
}
```

### GRADE 5 SCHOLARSHIP Results
URL : https://www.doenets.lk/result/service/GvResult/{INDEX}

```{
examination: "GRADE 5 SCHOLARSHIP EXAMINATION (AFTER APPEALS)",
year: "2020",
name: "HEWA PEDIGE GEEMAL SADEEPA DHARMASIRI",
indexNo: "5504562",
nic: null,
districtRank: "169",
islandRank: null,
marks: "169",
status: null,
zScore: null,
stream: null,
subjectResults: [
{
subjectName: "Mark",
subjectResult: "169"
}
],
studentInfo: [
{
param: "Examination",
value: "GRADE 5 SCHOLARSHIP EXAMINATION (AFTER APPEALS)"
},
{
param: "Year",
value: "2020"
},
{
param: "Name",
value: "HEWA PEDIGE GEEMAL SADEEPA DHARMASIRI"
},
{
param: "Index Number",
value: "5504562"
},
{
param: "District / Medium Cut off Mark",
value: "169"
}
]
}
```
