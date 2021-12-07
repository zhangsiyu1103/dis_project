#1. In manager side,Figure out the fail stop replicating sequence and ring move replicating sequence,
and try to combine them into a single function with multiple step. 
2. In server side, figure out the process of replicating server. How to handle primary and secondary
data migration.
3. Implement the requirement of homework 5 on server side
4. use map of key-data as the data type for shard and hashtable, modify necessay code in table.ivy and 
server process to make it work.
5. remember to divide extract and incoporate to two segment to handle the wrap around in table.ivy
5. Handle all request from manage network and implement queue to block data
#3. The details of frequency detection and threshold, route response to primary before commit, client
#delmap representation and add mod hash function when client send requests.
