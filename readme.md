# har-to-csv

Convert HAR file to Google/Excel/Numbers/CSV compatible spreadsheet for response size analysis

## Sample

```
➜  ~ har-to-csv < ~/Desktop/har1.har
url,transferred bytes
http://localhost:3000/,2280
http://localhost:3000/_next/static/S0jgIsDYIXMEFZmIlLh0P/pages/index.js,7342
http://localhost:3000/_next/static/S0jgIsDYIXMEFZmIlLh0P/pages/_app.js,1334
http://localhost:3000/_next/static/runtime/webpack-b65cab0b00afd201cbda.js,1118
http://localhost:3000/_next/static/chunks/framework.0f140d5eb2070c7e423d.js,40450
http://localhost:3000/_next/static/chunks/e77fc357760432063120fb33ebcb209c479429eb.413157615658d8422983.js,10862
http://localhost:3000/_next/static/runtime/main-91963396e6efd93d12cc.js,6357
http://localhost:3000/vercel.svg,845
http://localhost:3000/_next/static/S0jgIsDYIXMEFZmIlLh0P/_buildManifest.js,403
http://localhost:3000/_next/static/S0jgIsDYIXMEFZmIlLh0P/_ssgManifest.js,398
http://localhost:3000/favicon.ico,1876
```

## Installation

```bash
npm i -g har-to-csv
```

## Usage 

```bash
har-to-csv < ~/Desktop/har1.har > ~/Desktop/har1.csv
```
