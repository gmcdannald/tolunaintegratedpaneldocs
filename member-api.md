---
title: Member API
has_children: true
nav_order: 2
---

# Member API 

I've added this to start things out. 


## Member GET

A partner can get details for members in the Toluna IP database using an HTTP GET.
URL to GET new member info: http://ip.surveyrouter.com/IntegratedPanelService/api/Respondent

### Parameters:
 
 
 

| Name        | Description          | Required |
|:-------------|:------------------|:------|
| memberCode           | Unique Respondent Code from the Partner | Y  |
| partnerGuid | Unique Partner Code   | Y  |



### Route:
```http

GET http://ip.surveyrouter.com/IntegratedPanelService/api/ Respondent
/?memberCode=1601440000&partnerGuid=CC265C63-F887-4366-9ED1-7B2B3BD94C2B

````

### Sample Response:
``` 
{
    "MemberCode": "1601440000",
    "LanguageID": 2000245,
    "Language": "Français",
    "CountryID": 2000073,
    "Country": "France",
    "GenderID": 2000247,
    "Gender": "Homme",
    "EducationID": 2002274,
    "Education": "Bac+4",
    "IncomeID": 2002335,
    "Income": "Je ne sais pas / préfère ne pas répondre",
    "EthnicityID": 0,
    "Ethnicity": "",
    "RaceID": 0,
    "Race": "",
    "WorkPositionID": 0,
    "WorkPosition": "",
    "Active": true,
    "Email": "",
    "BirthDate": "Tuesday, July 11, 2000",
    "PostalCode": "75001",
    "PanelistStatusTypeID": 0,
    "CultureID": 6,
    "SubProvinceID": "3091832"
}

```


