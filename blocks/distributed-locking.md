# Summary of "How to do Distributed Locking" by Martin Kleppmann

## Overview
- The article discusses the challenges and misconceptions around implementing distributed locking, specifically criticizing the Redlock algorithm proposed for Redis.

## Key Points
- Distributed locking is complex due to network delays, process pauses, and clock inaccuracies, which can lead to unsafe data manipulations.
- Kleppmann argues that the Redlock algorithm fails to ensure safe distributed locking because it does not handle these issues effectively.
- Instead of relying on Redlock, he recommends using systems like ZooKeeper, which use fencing tokens to ensure safe operations, or sticking to simpler single-instance locks for non-critical tasks.

For more details and an in-depth analysis, read the full article [here](https://martin.kleppmann.com/2016/02/08/how-to-do-distributed-locking.html).
