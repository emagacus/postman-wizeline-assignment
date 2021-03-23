# Wizeline Postman assignment

Qa automation certification challenge

## Requirements

* node Js
* newman
* newman-reporter-htmlextra

Use the package manager [npm](https://www.npmjs.com/) to install newman and newman-reporter-htmlextra.

```bash
npm install -g newman
npm install -g newman-reporter-htmlextra
```

## Usage

Execute at root level

To run in windows

```bash
 npx newman run 'environments/Todoist.json' -e 'collections/qa_todoist.json' -r 'htmlextra' --reporter-htmlextra-export report.html 
```

To run in Mac OS / Linux

```bash
 newman run 'environments/Todoist.json' -e 'collections/qa_todoist.json' -r 'htmlextra' --reporter-htmlextra-export report.html 
```


## Reports

Report is generated as Report.html 

## License
[ Unlicense](https://unlicense.org/)
