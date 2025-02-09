# openBEM report

The script extracts data from the open EPC data and generates a report about a local authority when given the certificates.csv file is given as an input.

The report includes:
- The total number of EPCs carried out in the local authority
- A graph of the number of EPCs against property type (house, flat, massionette, Bunaglow, Park home)
- A graph of the number of EPCs at energy ratings against number of records

Commands:
```
python3 open_bem.py -i /path/to/certificates.csv
```

Future improvements:
- Add more plots - I've structured the code using classes so that the code can be appended to easily.
- Allow more than one local authority to be run in one time
- Improve command input so you only have to pass in name of authority
