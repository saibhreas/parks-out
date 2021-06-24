# parks-out
Had multiple Heroku deployment issues.  This is th latest Repository build.  Clearing JSON and JSON pakcage lock, as well as GET / pathing issues.

the following is the heroku error
  *2021-06-24T00:38:01.599311+00:00 
heroku[router]: 
  at=error 
  code=H10 
  desc="App crashed" 
  method=GET 
  path="/" 
  host=parkoutjctest.herokuapp.com request_id=6cea1f10-8188-4134-a61d-4c6e879a418b 
  fwd="173.54.171.158" 
  dyno= connect= service= status=503 bytes= protocol=https
  
2021-06-24T00:38:01.831121+00:00 
heroku[router]: 
  at=error 
  code=H10 
  desc="App crashed" 
  method=GET 
  path="/favicon.ico" 
  host=parkoutjctest.herokuapp.com request_id=9bc56d90-638d-4f67-a265-e09ee28373ae 
  fwd="173.54.171.158" 
  dyno= connect= service= status=503 bytes= protocol=https
Code H10.  did npm i and  npm install dotenv.  if this does not help then I will refactor code into clean files.

![screenshot](./public/img/error1Heroku.png)

Reloade .env npm to no avial.  it says its lodaded but cannot get past node.  I deleted and re-entered ""start": "node server.js".  did a clean start/ rewrote connections file.
