# Docker Images: Piwik

## Description

Docker Conatiner from Piwik with Redis support.

## Build

Build from docker file

```bash
$ docker build -t sbaerlocher/piwik .
```

Build from docker registry

```bash
docker pull sbaerlocher/piwik
```

## run

```bash
docker run --restart=always -d \
    --name piwik  \
    -h piwik.sbaerlo.ch \ 
    -v /:/ \
    -p : \
    sbaerlocher/piwik
```

### Options

None

#### Example:

```
docker run sbaerlocher/piwik
```

## Changelog

## Author

* [Simon Bärlocher](https://sbaerlocher.ch)
 
## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2017, Simon Bärlocher