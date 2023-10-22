# developer-experience-presentation
Presentation of s.lavazais's developer experience

## how to start presentation

you'll need [docker](https://docs.docker.com/get-docker/) :

```shell
docker run --rm -p 1948:1948 -p 35729:35729 -v $(pwd)/Presentation:/slides webpronl/reveal-md:latest /slides --watch
```

or with Makefile:
```shell
make presentation
```

and then go to [`http://localhost:1948/slides.md#/`](http://localhost:1948/slides.md#/)

any help

```shell
make help
```

## contacts

[sylvain LAVAZAIS](mailto:slavazais@pm.me)


