# Performance Insights API<a name="USER_PerfInsights.API"></a>

The Amazon RDS Performance Insights API provides visibility into the performance of your RDS instance, when Performance Insights is enabled for supported engine types\. Amazon CloudWatch Logs provides the authoritative source for vended monitoring metrics for AWS services\. Performance Insights offers a domain\-specific view of database load measured as average active sessions and provided to API consumers as a two\-dimensional time\-series dataset\. The time dimension of the data provides database load data for each time point in the queried time range\. Each time point decomposes overall load in relation to the requested dimensions, such as `SQL`, `Wait-event`, `User`, or `Host`, measured at that time point\.

For more information, see the [Amazon RDS Performance Insights API Reference](https://docs.aws.amazon.com//performance-insights/latest/APIReference/Welcome.html)\.