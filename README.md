# To test

* Open index.html in browser (file:///path/to/index.html)
* Open dev tools
* Bluebird CDN is loaded
* The two console logs are a Bluebird promise and one of the prototype functions belonging to the promise
* amCharts is loaded
* The next two console logs show that the basic global promise is still a Bluebird promise but the Promise.prototype.then function has changed
