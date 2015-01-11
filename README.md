Audio-List
---
A simple web component for playlists and audio-elements.

[Demo](http://mp3.w8l.org/droggelbecher/)

Attributes
---

|attr|type|default|
|---|---|---|
|autoplay|bool|true|
|loop|bool|true|
|shuffle|bool|false|
|src|string|./playlist.json|
|callback|string|playlist|

Example
---
index.html

	<play-list src="playlist.json" shuffle="true"></play-list>

playlist.json

	playlist([{
		"title": "Cream - Anyone for Tennis",
		"file": "./mp3/cream/anyonefortennis.mp3"
	}, {
		"title": "Led Zeppelin - Kashmir",
		"file": "./mp3/zeppelin/kashmir.mp3"
	}])
