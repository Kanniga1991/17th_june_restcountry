# 17th_june_restcountry
the name and specific details in json data of rest countries which has 250 array of objects
var xhr = new XMLHttpRequest();
        xhr.open("GET", "https://restcountries.eu/rest/v2/all");
        xhr.onload = function () {
          var data = JSON.parse(this.response); for(var i in data){
          console.log(data[i].name);}
        };
        xhr.send();

------------------------------------------
var xhr = new XMLHttpRequest();
        xhr.open("GET", "https://restcountries.eu/rest/v2/all");
        xhr.onload = function () {
          var data = JSON.parse(this.response); for(var i in data){
          console.log(data[i].region);}
        };
        xhr.send();
  -----------------------------------------------
        var xhr = new XMLHttpRequest();
        xhr.open("GET", "https://restcountries.eu/rest/v2/all");
        xhr.onload = function () {
          var data = JSON.parse(this.response); for(var i in data){
          console.log(data[i].flag);}
        };
        xhr.send();
