# Wizeline TestCafe challenge

Qa automation certification challenge

## Requirements

* node Js
* testcafe
* testcafe-reporter-html

Use the package manager [npm](https://www.npmjs.com/) to install testcafe and testcafe-reporter-html.

```bash
npm install -g newman
npm install -g newman-reporter-htmlextra
```

## Usage

Execute at root level

To run in windows

```bash
 npx newman run 'environments/Todoist.json' -e 'collections/qa_todoist.json'
```

To run in Mac OS / Linux

```bash
 newman run 'environments/Todoist.json' -e 'collections/qa_todoist.json'
```


## Reports

Report is generated as Report.html 

## License
[ Unlicense](https://unlicense.org/)