Zookeeper Benchmark Example
====

This is self contained performance test intended as demonstration
of usage of [Nimble][nimble] framework.

Benchmark could be started via JUnit runner
```
org.gridkit.lab.zktest.ZkBenchRun#start_and_run_locally()
```

Test scenario includes

- setting up and starting three Zookeeper node on local process
- simulating read/write load
- collecting some performance metrics
- reporting aggregated performance summary
- raw data collected in test run is avaialable as `raw-local.csv` after succesful run

 [nimble]: https://github.com/gridkit/nimble