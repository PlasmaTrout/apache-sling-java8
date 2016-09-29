apache-sling-java8
==================
[![](https://images.microbadger.com/badges/image/plasmatrout/apache-sling-java8.svg)](https://microbadger.com/images/plasmatrout/apache-sling-java8 "Get your own image badge on microbadger.com")

This project provides a stand alone Apache Sling image on Ubuntu. The image utilizes Java 8 for run-time and Apache Sling was recompiled for compatibility.

To get it up and running, from your docker console type:

    docker run -i -t -p 8080:8080 plasmatrout/apache-sling-java8

The system console can be found at:

at [http://localhost:8080/system/console][1] on Linux or http://(you dockerip):8080/system/console on windows. *FYI: On Windows the easiest way I know to get the IP is to open virtual box and go into the instance and run ipconfig -a and use eth1's IP. Mine ended up 192.168.99.100 last time I pulled it.*

The username and password are left default for the console as *admin/admin*

This image is bare bones and navigating to the root index.html should present you with the default Apache Sling page.


  [1]: http://localhost:8080/system/console
  [2]: http://192.168.59.103:8080/system/console
  

