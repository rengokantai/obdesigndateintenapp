# obdesigndateintenapp



## 3. Storage and Retrieval
In paticular, there is a big difference between storage engines that are optimized for transactional workloads and those that
are optimized for analytics.






## 10. Batch Processing

We distinguish three different types of systems:
#### Service(online)

When one is received, the service tries to handle it as quickly as possible and sends a response back.  
Response time is the primary measure of performance of a service, and availablity is often very important.

### Batch processing system(offline)

### Stream processing systems(near-real-time systems)


###### 392
If you want to omit CSS files, 
```
'$7 !~ /\.css$/ {print $7}'
```


## 12. The Future of Data Systems
### Data Integration
storage engines


#### Combining Specialized Tools by Deriving Data

##### Reasoning about dataflows
If it is possible for you to funnel all user input through a single system that decides on an ordering
for all writes, it becomes much easier to derive other representations of the data by processing the 
writes in the same order


### Polls
What is the Poll Loop
- Consumers can fetch messages from multiple sources
- A poll is an event loop
  - Partition assignment
  - Message fetching
  - Rebalancing
  - Coordination

- Note: each consumer should run in seperate thread
