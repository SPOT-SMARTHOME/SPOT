# SPOT: A Smartphone-Based Platform to Tackle Heterogeneity in Smart-Home Systems

The recent advancements of smart-home technologies, including broad penetration of Internet-connected smart appliances such as remotely controllable LED lights, thermostats, cameras, motion sensors, and door locks, have changed the way we interact with the appliances and perform our daily activities. However, the significant heterogeneity in the emerging smart appliances has led to fragmented smart-home systems in which each single appliance vendor provides proprietary solution for appliance specific connectivity and user experience. In particular, the heterogeneity exists in different aspects of smart appliances such as control apps, communication protocol, messaging schema, data structure and variable naming. To address this challenge, we present SPOT, a smartphone-based platform for multi-vendor smart-home appliances. SPOT consists of several novel mechanisms including open appliance driver models using XML and JAVA annotation, which allow vendor-independent, user-driven device driver implementation, and an appliance-adaptive user interface and appliance/state control. To validate the flexibility and generality of our approach, we have built a SPOT prototype based on 8 real appliances. Our prototype implementation and extensive microbenchmark evaluation demonstrate how such a platform can be realized while incurring low runtime overhead.

SPOT provides a web interface (located at http://spot-smarthome.github.io/SPOT/) to facilitate the process of adding new appliances to the system. By using this web interface, one can genrate the XML drivers by simply filling the web form.
