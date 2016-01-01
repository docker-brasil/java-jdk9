# java-jdk9

A Docker image for use as a JShell playground

## Pull the image

    docker pull parana/java-jdk9

## Using the Image

    docker run -i -t --rm parana/java-jdk9

## Open a JShell session

    import java.util.stream.*
    IntStream.range(0, 10).map(x->x*x).forEach(System.out::println)
    /save script-01.repl 
    /exit
