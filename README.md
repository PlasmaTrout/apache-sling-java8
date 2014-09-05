apache-sling-java8
==================

This repository profile resources to set up a docker base apache-sling development image on ubuntu. To run it all you need is to:

    docker run -i -t -p 8080:8080 plasmatrout/apache-sling

The system console can be found at:

at [http://localhost:8080/system/console][1] on linux or [http://192.168.59.103:8080/system/console][2] on windows

The username and password are left default for the console as *admin/admin*

No content is pushed in this images and navigating the root of the site should present the Apache Sling splash content and default login areas.


  [1]: http://localhost:8080/system/console
  [2]: http://192.168.59.103:8080/system/console
  
The jar file in the build directory of this project is a java8 build. When its refreshed it will trigger a rebuild of the docker image.

