``
docker build --build-arg CONFIG_NAME=my-config.xml -t ru.xsires/docker-image:1.0-SNAPSHOT .
``

work correctly

``
./gradlew docker -d
``

fail with

``
ADD failed: stat /var/lib/docker/tmp/docker-builder157707131/config/my-config.xml: no such file or directory
``
