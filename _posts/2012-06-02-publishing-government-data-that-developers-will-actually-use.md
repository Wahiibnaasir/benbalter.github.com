---
title: Publishing Government Data That Developers Will Actually Use
description: Despite increasing public support (as well as a number of executive mandates) publishing public data in a machine-readable format is not as simple as pressing the "publish" button. Why? Equally important as exposing the information itself is fostering a vibrant developer ecosystem around it. By making the publishing agency, not the public, responsible for making information immediately useful, government can lower the barriers associated with consuming its data and introduce additional citizen services at little to no cost to the agency.
---

Despite increasing public support (as well as a number of executive mandates) publishing public data in a machine-readable format is not as simple as pressing the "publish" button. Why? Equally important as exposing the information itself is fostering a vibrant developer ecosystem around it. By making the publishing agency, not the public, responsible for making information immediately useful, government can lower the barriers associated with consuming its data and introduce additional citizen services at little to no cost to the agency.

### 1. Garbage in, garbage out

Good, clean data may be surprisingly difficult to come by, especially when working with government systems that have been coupled together over decades. Data standards and conventions change, mechanisms of data collection evolve, and the data itself may be interpreted differently as new policies are introduced. As a result consistent practices, like naming conventions or data formats, often go overlooked. Where practical, take steps to normalize the data prior to release, rather than pushing the responsibility off to be inefficiently repeated by each application individually.

### 2. Eat your own dog food

When organizations consume the products they create, they empirically deliver better, more reliable, and more innovative products. You'd never seek to buy a car from a dealer that's never driven one, yet we often expect the public to build applications based on APIs (Application Programming Interfaces – how computers talk to one another) published by organizations that have never had to consume their own data. Rather than solving the same problem twice, start by exposing all relevant data through public APIs and then work backward to build internal applications that rely on those externally facing data feeds.

### 3. Data as a citizen service

It is tempting to try and meet open data benchmarks, at least on face, by publishing snapshots of large data sets. Yet multi-gigabyte database exports do little to encourage external development, especially when such data-dumps are delayed and infrequent. Imagine the usefulness of a Facebook feed that showed your friends' activity from last month. data sets should be directly exposed so that the public has access to live, real-time data, either in its entirety, or through proper access controls. This not only allows agencies to deliver more useful information, but also reduces the need to store the same data in multiple formats and in multiple locations.

### 4. Curate discrete pieces of data

APIs are most useful when they do the heavy lifting for those consuming them, especially in terms of sifting through large amounts of data. In practical terms that means returning data to the most discrete level possible, be it a single row, rather than merely returning a subset of the dataset, or even returning a single cell. Seemingly obvious but often overlooked, a query for the broadband speeds at a given address, for example, should return only the data relating to that address, not the entire city or even state-wide dataset. By allowing developers to query the data directly that means they will need less development time on their end, and thus a higher likelihood that an application will be built.

### 5. Serve data in multiple formats

When providing a service, whether you are a waiter or a CIO, "the customer is always right." In the context of APIs, that means you need to return the information in the developers' native tongue, not the server's. For some languages, heavyweight methods like XML may make sense, for others, especially mobile applications, JSON or JSONP may be preferred. Be prepared to return data in multiple formats, even as those formats continue to evolve.

### 6. Minimize the handshake learning curve

Authentication may often be necessary, but the pain associated with it does not have to. Ensure that developers can easily register API keys, with minimal effort and without delay, and rely on common authentication frameworks (for example, OAuth 2.0) to minimize the learning curve. Similarly, whenever practical, provide common API wrappers and other software development kits in multiple languages.

### 7. Encourage adoption through documentation

Often, the most overlooked aspect of exposing data is documentation. Describe the structure of the data fully, including how to interpret it, and ensure that any technical documentation such as lists of methods and sample code is both complete and accurate. The only thing worse than not having documentation is having wrong documentation. The best APIs even provide Wikis to allow developers to share tools and best practices with one another.

### 8. Follow industry standards and convention

Although APIs may just be beginning to take foothold in government, a set of best practices have quietly evolved in the private sector over the past several years. What may seem like small, technicalities, such as a truly RESTful API or using proper HTTP methods like GET, POST, PUT, and DELETE, for example, can mean the difference between useful and useless.

### 9. Bake in Analytics

When it comes to garnering support for future efforts, nothing can be more powerful than raw numbers. From the ground up, bake in analytics on both the application level (what applications are querying the API?), and across APIs on the dataset levels (what APIs are being used?). This will help establish data-driven priorities, such as what type of data may be a good candidate for future APIs.

### 10. Location, location, location

With the "consumerization" of mobile, data sets are increasingly becoming location based. It's not what data sets are out there, but rather, what data sets are out there about my immediate world. Likewise, government data sets are increasingly about where, just as much as it is about what. It's important that this reality be taken into account when building APIs by incorporating geospatial lookups within the API, such a relying on MongoDB or other location-aware data structures.

Exposing data as a service is quickly becoming an industry-standard practice. Many popular startups owe their success to the vibrant app communities that surround them, grown simply by lifting some of the burden off of developers' shoulders. Government agencies may not yet be able to publish data with the mere click of a button, but when done right from the start, exposing additional data sources may be a more trivial task than many expect, and will in turn deliver value to citizens in ways today unimagined by agencies.

*This is an excerpt of an article originally published in the June 2012 issue of [Government CIO Magazine](http://www.governmentciomagazine.com).* **[Continue Reading →](http://www.governmentciomagazine.com/2012/06/ten-steps-publishing-government-data-developers-will-actually-use#blog-content)**
