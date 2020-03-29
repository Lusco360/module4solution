# module4solution
//A short program that greets hello or bye

<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>Module 4 Solution Starter</title>
  <script>
    var names = []; // DO NOT REMOVE
  </script>
  <script src="SpeakHello.js"></script>
  <script src="SpeakGoodBye.js"></script>
  <script src="script.js"></script>
</head>
<body>
  <h1>Module 4 Solution Starter</h1>
</body>
</html>

==============================================================================================

(function(window){
  var helloSpeaker = new Object ();
  var speakWord = "Hello";
  helloSpeaker.speak = function (name) {
    console.log(speakWord + " " + name);
  }
  window.helloSpeaker = helloSpeaker;
})(window);

===========================================================================================

(function(window){
  var byeSpeaker = new Object ();
  var speakWord = "Hello";
  byeSpeaker.speak = function (name) {
    console.log(speakWord + " " + name);
  }
  window.byeSpeaker = byeSpeaker;
})(window);

============================================================================================

var names = ["Yaakov", "John", "Jen", "Jason", "Paul", "Frank", "Larry", "Paula", "Laura", "Jim"];
var i;

for (i=0; i<names.length; i++){
  var firstLetter = names[i].charAt(0).toLowerCase();

  if(firstLetter==j){
    byeSpeaker.speak(names[i]);
  } 
  else{
    helloSpeaker.speak(names[i]);
  }

}
