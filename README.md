#Fork from <a href="https://github.com/happyworm/jPlayer">Jplayer</a>

#Changelog:
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