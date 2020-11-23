Before the emergence of handheld smartphones, processing and storage intensive applications such as stream processing, image detection and recognition, survey collection, crowd computing etc.,~\cite{fernando2013mobile} relied on offloading data to remote cloud infrastructures for processing and storage. However, due to low latency requirement, mobile applications evolved to be less dependent on cloud infrastructures, and more dependent on local resources. In this architecture, mobile devices form a local cloud, allowing applications to process and store data locally, commonly known as Mobile Edge Computing (MEC). MEC has many open problems relating to both computation and storage~\cite{shahzadi2017multi}. Computation intensive tasks such as mobile stream processing, big data analysis, real-time face detection and recognition etc, require fast computation with low latency. Storage intensive tasks such as survey collection, geospatial data collection, text and media files storage and any other quantitative and qualitative data storage by users  etc., can easily consume device storage. Network disconnection aggregates the limited resource availability problem by preventing devices to access available edge resources. We observe that, MEC applications require a unified data storage and sharing platform that is resilient to both device and network failures. Such platform will ensure services similar to cloud without reliance to cloud infrastructures.

We present R-Drive, a unified data storage and sharing framework for MEC environment. R-Drive targets both device and network failures in MEC environment and eliminates above mentioned data storage and sharing problems by bringing the cloud services in the edge. R-Drive utilizes the available storage resources of devices in edge to store data in fault tolerant manner. Additionally, R-Drive's distributed directory namespace service allows users/applications to securely share data without additional implementation. Below are the key features of R-Drive system -

- R-Drive supports distributed data storage with encryption and erasure coding, ensuring balanced usage of all available storage resources in edge.
- R-Drive adopts opportunistic network, making the maximum use of available bandwidth, at the same time abstracting network failure from client applications.
- R-Drive incorporates distributed directory namespace service with secure access control list.
- R-Drive presents a data consistency model that is practical and observable for disconnected mobile edge.
- R-Drive supports inter-edge device mobility and data offloading.

Code: private code not available for public use, please contact msagor@tamu.edu and rstoleru@tamu.edu for 
