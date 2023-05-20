### 9 minutes with **Haoel** in October 2017
----

#### About APM

> Q&A about cloud-native application APM

**Me:** Could you please share your basic understanding of cloud-native APM (Application Performance Monitoring) and distributed tracing?

**Haoel**: My understanding is that cloud-native APM and distributed tracing is a technology used for tracking and managing the execution flow of requests within a microservices environment, with the aim of monitoring application performance and identifying potential issues.

**Me:** That's correct, cloud-native APM and distributed tracing is primarily used to track requests in a microservices environment and identify potential performance bottlenecks or sources of errors. What type of tracing tools are you using?

**Haoel**: We primarily use Jaeger and Zipkin for distributed tracing.

**Me:** In your tools, how do you go about collecting tracing data? Do you use standards like OpenTracing?

**Haoel**: Yes, we use the OpenTracing standard for data collection, as it can help reduce the switching costs between different tools.

**Me:** Indeed, such standards can make tracing easier. What challenges have you encountered during the tracing process?

**Haoel**: The main challenges we've faced are the massive generation of data, which leads to difficulties in storage and analysis. Additionally, asynchronous communication between microservices also increases the complexity of tracing.

**Me:** Those are indeed common challenges. How do you effectively address these challenges?

**Haoel**: We use sampling and aggregation to reduce the volume of data we need to handle. We've also incorporated asynchronous communication handling into our tracing.

**Me:** Those strategies seem quite effective. During the tracing process, how do you ensure data integrity and accuracy?

**Haoel**: We ensure data quality through validation and cleansing, and we also carry out periodic data audits.

**Me:** Ensuring data integrity and accuracy is indeed important. How do you perform data analysis and visualization?

**Haoel**: We perform visual analysis using the interfaces provided by our tools, and also employ data analysis tools for deeper analysis.

**Me:** Data visualization is an effective method that helps us better understand tracing data. Do you use tracing data for problem troubleshooting and performance optimization? What are some of your experiences in this area?

**Haoel**: Yes, we use tracing data to troubleshoot performance issues. By examining the execution paths and latencies of requests, we can identify performance bottlenecks. Furthermore, tracing data also helps us understand how our systems operate, enabling us to optimize performance.

**Me:** Those are some excellent experiences. What do you see as the future trends in distributed tracing?

**Haoel**: I believe that as microservices become more prevalent, distributed tracing will become increasingly important. I also look forward to more open-source tools and standards that can reduce the complexity of tracing.

**Me:** Those indeed seem like promising future trends. Finally, what improvements could be made to distributed tracing in your team or project?

**Haoel**: We aim to further optimize the processing and analysis of tracing data, so that we can identify problems faster. Additionally, by improving the accuracy and completeness of our data collection, we hope to enhance our tracing capabilities.

R.I.P.
