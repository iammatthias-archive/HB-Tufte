This is Tufte-CSS and HarpJS.

Tufte CSS provides tools to style web articles using the ideas demonstrated by Edward Tufte’s books and handouts. HarpJS is a static web server / site generator with built in preprocessing.

I started with the standard HarpJS blogHB-Blog boilerplate. I stripped out the unessential files, and dropped in Tufte-CSS for a spiffy new layout.

```
$ sudo npm install -g harp
$ git clone https://github.com/iammatthias/HB-Tufte.git
$ harp server
```

It should all work, but this is definitly a work in progress. 
