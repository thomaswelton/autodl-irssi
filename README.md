### Autodl Irssi

Container for the autodl irssi plugin.

## Useage

```
docker run \
	-it -e TERM \
	--name autodl-irssi \
	-v </path/to/watch/directory>:/home/user/watch:rw \
	-v </path/to/autodl/directory>:/home/user/.autodl:rw \
	thomaswelton:autodl-irssi
```