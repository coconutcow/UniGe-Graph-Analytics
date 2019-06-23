# GraphAnalytics: Assignment One

## Brace, breath, and begin

#### Objective:
Create and analyze your own graph. Understand the underlying concepts concerning Graphs, and be able observe the effects, benefits, and perils of a widely distributed network. 

#### Programming Language:
Python, compiled using Jupyter Notebook

#### Libraries used:
* NetworkX
* Pandas
* MatplotLib
* Numpy
* Random
* Urllib.request

#### Data Source:
[OpenFlights](https://openflights.org/data.html "OpenFlights")

<br>I have used a library named 'urllib.request' in order to extract the file straight from the url thus making this project light, quick, and more efficient to execute.

## The Dataset

RyanAir, Lufthansa, American Airlines, Qatar ?
These are all popular names that are discussed from time to time, and form an integral part of this globalized world.
Airports, Airlines, and Routs, can all play important roles in deciding which country do we go to next. This is an initiative to plot the airports, airlines, and their consequent routes on a global map. The dataset has been keenly observed, and for my purpose has been tailored using python to satisfy the intent. Additionally, the modifications have been made in order to provide the best form of representation of the idea behind this implementation.
There is no need for you to download the dataset. 

## This world is our stage

Implementing the code gives us interesting reults.
The red dots represent the airports, and the black lines represent the routes between two airports.

### The first output looks slightly crude, and difficult to interpret. 
![Graph Image 1](https://lh3.googleusercontent.com/ehUEDBoa_RMTAhjD0PX2Y0YTVlaI8l3gfQ5mpcmTsXaX-j5jUBm5slvLm-Dw_ZCs1symDdJdevr4DqRnAqJSiuRizYHklV-5z4nFc2LSxnIcsQbieoq9dQi9mtZerB0f-_kODxj2vRvIfD88OHC44UIai5Avbr2ISq8-g77rTEvvYJjQjYL19pd7oC4RiOyGr8ofIGpvi6-yZR8jH-ZTyPOxoBFlq0tD7poITlpI5MTvSBc6EpxWYmLsXhRW1wOtcaH-iPvTLRPcLNXfHsZz7QqYwuFBFACsGVmjW99_S3cnsnxovwdYy_e5I9QyUel0RHaPMpSQnpbjwSYZOedj0XkcwmaY3bcT3w9OymvidGS6Y_bqgbCLsQWODF_cGZxSOucX1NcKkX_PWVoa_Cr88DPoBJ3SfkBpSc_AN6AVi0yg6r7N0vgc7QdJpTCeg5itt-RxapZj7i9diA7Mv-Q5bvuafDtWw-_FJ5rpA-uoaKMN46EzmWYK35H1IPG1ooK6oU2gTbmspe3vlrLwB6glTlbqpFugprLhi8ZA4QJuIZmf3l6cmUROxVpFXyZS51eikY-l8F1S8M-_xYFFi5RtuvkeXb-25Kwtz6hrjJpSzganFDqiCjz4VTRndW2uTRyVx3m_PxxcfQOl2jW17fRJpwFYIiP3uA=w474-h319-no)
### Voila! Doesn't it look beautiful ? Utilised some functions provided by the NetworkX and MatplotLib libraries.
![Graph Image 2](https://lh3.googleusercontent.com/yetZpBwSkLUL-3JBp0Erah79lez6dbOZqi5xrftzP0SV-QECl18t1NtLlMG5P1EVAnZ6PXw-YE_Sh2EoHvb9xQN-t3-1c2YLHv-MOOMbrGEx5uSlIHHXKappFjtUrqx-ZuQmpUXfls-DcIsiI4EziU6tuogM-zL6wAxVcjl9HDo343u7kQCP_v7Xhga0FEAw5_U97-DjRepvVQK6k0U7PZp_MNVUZyabMd2fCtbLu1YFCRMC_yZ46uSzGII5wLI0u8L0VynygF9jIVN3skzREqqLh6ngcmwf_XX0Wzd82sp-P6o4gRuoBbyaC0SA2OxUan7421EDIAZSao9xTJNsqOfcY_gwhyYMHqpJkMbWlNVXjwxcxSL8iiq11ZrKAY3BCQXqWdRUQaUzVWcagM1LRqTWQU6tEY0Gmnjl4Mp36ajcE2_3AFz2WPWQ1Z8UUzB6FLlyUVRCnOoPCjy9nTkOHK4HAp0sOjvJI2GZG1hlg1dwC3_VhbBX7Pqk0NycH730aodNqAoTrMbr2yzxhPENkDVnCtCO3sCMhagM8openhTP9anjwhBf6eFDvDQZ668sz1ooWWQh2HbUSXXNm0YG6RTK7NraZv814jNGtJcwyFaMac8It7QN_5VXHI5KQozWlBnDk8OjLOsRQn5pfEKaxBdSU2hS-w=w1018-h745-no)
