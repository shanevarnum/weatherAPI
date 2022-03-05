# WeatherApplication
# Start:
nodemon server.js
# Server 
NodeJs+Express
npm install --save express
# Client 
EJS (Embedded Javascript).
## Install: 
npm install ejs --save
## Set up: 
app.set('view engine', 'ejs')
# POST Route
npm install body-parser --save:
const bodyParser = require('body-parser'); // ... // ... app.use(bodyParser.urlencoded({ extended: true }));

# API 
let url = `http://api.openweathermap.org/data/2.5/weather?q=${city}&units=Metric&appid=${apiKey}`
'Metric' for Celsius.
