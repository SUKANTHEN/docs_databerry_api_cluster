
# DataBerry API Cluster 
### " For a Safe, Secure and Positivity enriched Digital World "

DataBerry Cluster offers wide range of APIs pertaining to multiple domains primarily built on core vision of problem solving. 

<ol> 1) DataBerry-Text Quality Analysis API for <b>Real-time Data Quality Validation</b> </ol>
<ol> 2) DataBerry Personal Identifier API for <b>Real-time Personal Information Identification</b> </ol>
<ol> 3) DataBerry Text Translator API for <b>Real-time translation of text into multiple languages</b> using Google Translate library </ol>
<ol> 4) DataBerry- Text Cleaner API for <b>Automated Data Cleaning in input text query</b>. </ol>
<ol> 5) DataBerry-Detoxifier API for <b>Toxic Comments Removal for input text</b> </ol>
<ol> 6) Domain Specific <b>Sentiment Classification</b> </ol>

Choose specific end-points that match your requirements from DataBerry cluster.

## API Reference

### DataBerry Cluster API


| Endpoint        | Method   |   Description              |
| :--------       | :------- | :------------------------- |
| `/text_quality` | `POST`   | Text Quality Analysis API |
| `/personal_identifier`| `POST` | Personal Identifier API |
| `/translate` | `POST` | Text Translator API | 
| `/datacleaner` | `POST` | Text Data Cleaner API | 

## 1) Text Quality Analysis API
Given a text input, the API will return 
- Query Language
- Number of Words
- Query Length
- Gibberish Score
- Toxicity Level / Score
- Text Sentiment Score

Input URL
```console
URL Link : https://databerry_cluster.com/text_quality
```

JSON Input
```console
{"text": "The patient ordered a pizza and soon after eating it went to ICU in the most dreadfully horrible way and much more story to go."}
```

JSON Output:
```
{
    "count_of_words": 26,
    "count_unique_words": 24,
    "language": "english",
    "query_length": 127,
    "toxicity": 0
}
```

## 2) Personal Identifier API
Given a text input, the API will extract all `personal information` such as
- Dates (Y-M-D Format)
- Email
- Gender
- Names
- Geo-location
- Phone Number

Input URL
```console
URL Link : https://databerry_cluster.com/personal_identifier
```

JSON Input
```console
{"text":"Hi Sukanthen,i was born on Oct 15 1999 in Neyveli, @ sukanthen1999@gmail.com. I am a male human with phone number 2A +1-541-754-3010."}
```

JSON Output:
```
{
    "dates": "1999-10-15",
    "email": "sukanthen1999@gmail.com.",
    "gender": "male",
    "phone_number": "+1-541-754-3010"
}
```

## 3) DataBerry Cluster Cleaner API
Given a text input, the Cleaner API will remove unwanted `stopwords`, `html tags` and `user-defined words` from the input text.


## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sukanchamp/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/sukanthen)


