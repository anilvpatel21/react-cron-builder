# New UI React Cron Builder
React component to build [cron](https://ru.wikipedia.org/wiki/Cron) expression

## installation
```` bash
npm install --save newui-react-cron-builder
````
## demo
[Live demo](https://anilvpatel21.github.io/react-cron-builder/)

## usage
```` ecmascript 6
import CronBuilder from  'newui-react-cron-builder';
import 'newui-react-cron-builder/dist/bundle.css'

<CronBuilder
    cronExpression="*/4 2,12,22 * * 1-5"
    onChange={::console.log}
    showResult={false}
/>
````

component was inspired by [this util](https://github.com/one-more/react-cron-builder)