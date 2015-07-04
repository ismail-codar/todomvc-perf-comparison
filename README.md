# TodoMVC Benchmark

Performance benchmarks for various TodoMVC implementations

##Runing on your locale
* Run: npm install -g simple-server
* Navigate: todomvc-benchmark folder
* Run: simple-server public 8000
* Open: localhost:8000/index.html

## Results 

*  OS X 10.8: MacBook Air,Core i5 @1.8GHz)
* Windows Vista: Pentium T4200 2GHz

### Overall:

Mercury, Vue and Mithril are king. Elm is a close fourth, except on IE9 where it is very slow. 

Ember is the slowest overall; Angular, React and Backbone are trailing too.

### Chrome 36, OS X
![Chrome](Chrome.png)

### Firefox 31, OS X
![Firefox](Firefox.png)

### Safari 6.1, OS X
![Safari](Safari.png)

### Chrome 36, Windows Vista

![Vista-Chrome](Vista-Chrome.png)

### IE9, Windows Vista

Note that the Angular Benchmark is not working ATM, in IE9, hence the ridiculous score.

![Vista-IE9](Vista-IE9.png)
