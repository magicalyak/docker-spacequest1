# docker-spacequest1

Docker image of Space Quest 1 running on js-dos

run the following to build
`docker build -t docker-spacequest1 --build-arg GAME_URL=https://github.com/magicalyak/docker-spacequest1/raw/master/spacequest1.zip --build-arg GAME_ARGS=\"SQ1VGA\INSTALL.EXE\" .`

once you have built the image, run with

`docker run -d -p 8000:8000 docker-spacequest1`
