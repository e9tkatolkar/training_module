### File IO and formats

1. JSON to CSV
  - Define a function in utils.py that takes the path to a json file
  - Read the json file
  - Write to a csv file that has the same name as the json file but has a new extension of csv instead
  - Do not clobber an existing file with the same name
  - Return the name of the csv file

```
[2]: json_to_csv("abcd.json")
Out: abcd.csv
```

2. CSV to JSON
  - Define a function in utils.py that takes the path to a csv file
  - Read the csv file
  - Write to a json file that has the same name as the json file but has a new extension of json instead
  - Do not clobber an existing file with the same name

```
[3]: csv_to_json("abcd.csv")
Out: abcd.json
```