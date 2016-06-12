### Dockerised midi2mp3 converter

Converting midi to mp3 made easy :)

Basic usage

```
docker run -it --rm -v $(pwd):/work -w /work mikechernev/midi2mp3 convert myfile.midi

```