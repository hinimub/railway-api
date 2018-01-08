# railway

*An API with various functionalities for indian railways*

## Setup
1. Select "Resources" > "Libraries..." in the Google Apps Script
editor.
2. Enter the project key `1uaNeV8Fn3elRZqfMt10BHc6MdJT6MXDH3I6VZ4AscG3kpWibpDtss9wh` in the "Find a Library" field, and choose "Select". 
3. Choose a version in the dropdown box, and choose railway as the
identifier. 
4. Click the "Save" button.

## Usage
- set API key (MANDATORY)

```js
railway.setApikey('<API key>')
```
You may register for a key at http://www.railwayapi.com/pricing/
<!--
- Check PNR status

Get PNR status using 10 digit PNR No.

```js
railway.checkPnr('<10 digit pnr>', function (err, res) {})
```


- Station name to Code

Get station details of given station and nearby stations using station name with automatic name completion.

```js
railway.stationCode('<station name>', function (err, res) {})
```

- Station Code to Name

Get passed railway station and nearby stations details using station code.

```js
railway.stationName('<station code>', function (err, res) {})
```

- LIVE train status

Get live train status.

```js
railway.liveTrainStatus('<train number>', function (err, res) {})
```

- Train route information

Get train’s route information like the list of stoppages,their locations etc.

```js
railway.trainRoute('<train number>', function (err, res) {})
```

- Trains between stations

Get all trains(numbers) running between a source station and destination.

```js
railway.trainBetweenStations('<source>', '<destination>', function (err, res) {})
```

- Train name/number

Get train name using number and vice versa.

```js
railway.name_number('<train name or number>', function (err, res) {})
```

- Seat Availability

Get Train Seat Availability.

```js
railway.seatAvailability = ('<trainNo>', '<source>', '<destination>', '<date>', '<class>', '<quota>', function (err, res) {})
```

class: valid class code can be fetched from http://www.indianrail.gov.in/class_Code.html

quota(optional: defaults to GN): valid quota code can be fetched from http://www.indianrail.gov.in/quota_Code.html -->
