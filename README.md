# ODL-Toaster
An example to understand the MD-SAL infrastructure within the OpenDaylight controller

[INFO] ------------------------------------------------------------------------

[INFO] Reactor Summary:

[INFO]

[INFO] ODL :: com.ps.odl :: odltoaster-api ................ SUCCESS [05:21 min]

[INFO] ODL :: com.ps.odl :: toaster-provider .............. SUCCESS [ 50.565 s]

[INFO] ODL :: com.ps.odl :: toaster-consumer .............. SUCCESS [ 14.785 s]

[INFO] ODL :: com.ps.odl :: odltoaster-cli ................ SUCCESS [ 19.545 s]

[INFO] ODL :: com.ps.odl :: odltoaster-features ........... SUCCESS [16:32 min]

[INFO] ODL :: com.ps.odl :: odltoaster-karaf .............. SUCCESS [04:04 min]

[INFO] ODL :: com.ps.odl :: odltoaster-artifacts .......... SUCCESS [  4.055 s]

[INFO] ODL :: com.ps.odl :: odltoaster-it ................. SUCCESS [04:03 min]

[INFO] odltoaster 0.1.0-SNAPSHOT .......................... SUCCESS [01:16 min]

[INFO] ------------------------------------------------------------------------

[INFO] BUILD SUCCESS

[INFO] ------------------------------------------------------------------------

[INFO] Total time: 34:28 min

├── api
├── artifacts
├── cli
├── features
├── it
├── karaf
├── toaster-consumer
├── toaster-provider
│   ├── pom.xml
│   ├── target
│   └── src
│       └── main
│           ├── java
│           │   └── com
│           │       └── ps
│           │           └── odl
│           │             └── impl
│           │               └── OpendaylightToaster.java
│           │               └── ToasterProviderRuntimeMXBean.java
│           ├── resources
│           │   └── org
│           │       └── opendaylight
│           │           └── blueprint
│           │               └── toaster-provider.xml

└── target
└── src

