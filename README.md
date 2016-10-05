# Docker Images: Piwik

## Description

## Build

Build from docker file

```
$ docker build -t sbaerlocher/piwik .
```

Build from docker registry

```
docker pull sbaerlocher/piwik
```

## run

```
docker run --restart=always -d \
    --name piwik  \
    -h piwik.sbaerlo.ch \ 
    -v /:/ \
    -p : \
    sbaerlocher/piwik
```

### Options


| Name                  | Values               | Behaviour                                                                          |
|:---------------------:|:--------------------:|:-----------------------------------------------------------------------------------|
|                       |                      |                                                                                    |
|                       |                      |                                                                                    |
|                       |                      |                                                                                    |
|                       |                      |                                                                                    |
|                       |                      |                                                                                    |
|                       |                      |                                                                                    |
|                       |                      |                                                                                    |
|                       |                      |                                                                                    |


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

(c) 2016, Simon Bärlocher