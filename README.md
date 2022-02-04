# Collection Run With Newman & HTML Report Generate

## Prerequisite
1. Node JS
2. Visual Studio Code

## How to run the collection with newman
1. Clone the repo
2. Run cmd in the root folder
3. Then give the following command in cmd

```
npm init -y
```
```
npn i newman
```
```
npx newman run .\Collection\DmoneyAPICollection -e .\Collection\DmoneyAPIEnvironment -n 1
```

## How to generate report with newman
1. Run cmd in the root folder
2. Then give the following command in cmd

```
npm i newman-reporter-htmlextra
```
```
node ./report.js
```

## Screenshots of the Newman Report
![1](https://user-images.githubusercontent.com/96170694/152589598-cf941aa9-1406-4e99-a165-2bd856f4821d.JPG)

