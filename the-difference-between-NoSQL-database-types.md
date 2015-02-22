+## Key/Values
+  - Best example is Redis
+  - In practice this looks like caching SQL data tables
+  - Example use case is Amazon top seller lists. 
+    - Rather than ping the SQL database 100,000 times per second
+    - Maybe Amazon is ok with only updating every minute
+    - Redis holds/serves the tables
+
+## Big Table 
+ - Best example is Cassandra (not the one from Wayne's World)
+ - Good for a ton of write tasks
+    - Ingest twitter firehose
+    - Record real-time trading data
+    - This provides "linear write scalability"
+    - The vast majority of startups or companies with "Data Science" use Cassandra underneath Hadoop
+
+## Document 
+  - Best example is MongoDB
+  - Mongo is schemaless and embedable
+    - Embedable may not be that good in practice (like hard coding in a model)
+    - [This is their website, btw](www.mongodb.com)
+
+## Graph 
+  - Best example is Neo4J
+  - Great for graph-shaped problems
+    - Recommendation engines, ratings systems, social media, etc
  
Got all that?
![alt text](http://media.giphy.com/media/6y17pgEsBdN7y/giphy.gif "Hilarious Mind Blown Gif")


  
