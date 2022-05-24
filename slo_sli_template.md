# API Service

| Category     | SLI                                                      | SLO                                                                                                         |
|--------------|----------------------------------------------------------|-------------------------------------------------------------------------------------------------------------|
| Availability | total # of succcessful request / total # request >= 0.99 | 99%                                                                                                         |
| Latency      | 90th Percentile latency over 5 min < 100ms               | 90% of requests below 100ms                                                                                 |
| Error Budget | # error request / # request <= 0.2                       | Error budget is defined at 20%. This means that 20% of the requests can fail and still be within the budget |
| Throughput   | Total # of request per minute >= 300                     | 5 RPS indicates the application is functioning                                                              |
