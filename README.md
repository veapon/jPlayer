#Fork from <a href="https://github.com/happyworm/jPlayer">Jplay</a>

#Change log:
* Add 'repeat one' playlist option.

``` javascript

	var options = {
		playlistOptions: {
			autoPlay: true,
			loopOnPrevious: true,
			repeatone: true,
		},
		...
	};

	var myPlayer = new jPlayerPlaylist({cssSelector}, [volPlaylist], options);
```