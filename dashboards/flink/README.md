### Dashboards for flink

#### Notes

- This dashboard is based on Google's [Ops Agent](https://cloud.google.com/stackdriver/docs/solutions/agents/ops-agent).
- The full list of metrics supported by the Ops Agent can be found [here](https://cloud.google.com/stackdriver/docs/solutions/agents/ops-agent/third-party/flink#monitored-metrics).

|Flink GCE Overview|
|:------------------|
|Filename: [flink-gce-overview.json](flink-gce-overview.json)|
|This dashboard has charts displaying `CPU Load`, `CPU Time`, `Threads`, `Heap Used`, `Heap Committed`, `Heap Max`, `Nonheap Used`, `Nonheap Committed`, `Nonheap Max`, `Metaspace used`, `Metaspace Committed`, `Metaspace Max`, `Direct Used`, `Direct Total Capacity`, `Mapped used`, `Mapped Total Capacity`, `Garbage Collector Time`, `Garbage Collector Count`, `Flink Memory Managed Used`, `Flink Memory Managed Total`, and `Class Loader` from flink as well as charts of infrastructure related metrics for the running flink VMs: `CPU % Top 5 VMs`, `Memory % Top 5 VMs`, and `Hosts by Region`. There is also a card with links to docs and the flink logs in Cloud Logging.|


|Flink GCE Overview|
|:------------------|
|Filename: [flink-gce-jobs-overview.json](flink-gce-jobs-overview.json)|
|This dashboard has charts displaying `Number of Restarts`, `Last Checkpoint Time`, `Last Checkpoint Size`, `Checkpoints In Progress`, `Checkpoints Completed`, `Checkpoints Failed`, `Task Records In`, `Task Records Out`, `Task Records Dropped`, `Operator Records In`, `Operator Records Out`, and `Operator Records Dropped` from flink. There is also a card with links to docs and the flink logs in Cloud Logging.|