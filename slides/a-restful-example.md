##  A RESTful Example

Simple sample

* List: GET /jokes
* Create: POST /jokes
* Show: GET /jokes/1
* Update: PUT /jokes/1
* Delete: DELETE /jokes/1

note:

curl http://lets-talk-apis.herokuapp.com/jokes
curl -X POST --data 'joke[joke]=Why did the chicken get to the other side&joke[punchline]=To get to the other side' http://lets-talk-apis.herokuapp.com/jokes
curl -X PUT --data 'joke[joke]=New Joke&joke[punchline]=Punchline' http://lets-talk-apis.herokuapp.com/jokes/1
curl -X DELETE http://lets-talk-apis.herokuapp.com/jokes/1
