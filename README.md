# ing-web-v1

Convert Timezone

```javascript
const tz = require('tz');

date = new Date();

convertedDate = tz(date, 'Asia/Jakarta'); // Refer to https://en.wikipedia.org/wiki/List_of_tz_database_time_zones for timezone strings

console.log(date) // 2022-01-11T14:19:13.870Z
console.log(convertedDate) // 2022-01-11T21:19:13.000Z
```
