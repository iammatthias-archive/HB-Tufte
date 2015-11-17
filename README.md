This is Tufte-CSS and HarpJS.

Tufte CSS provides tools to style web articles using the ideas demonstrated by Edward Tufte’s books and handouts. HarpJS is a static web server / site generator with built in preprocessing.

I started with the standard HB-Blog boilerplate, then stripped out the unessential files, and dropped in Tufte-CSS for a spiffy new layout.

```
$ sudo npm install -g harp
$ git clone https://github.com/iammatthias/HB-Tufte.git
$ harp server
```

Basic functionality is there, but is missing paged articles, and solid navigation.  


To-do: Move general style over to a fork of [Baseline](https://github.com/rosshj/baseline)
