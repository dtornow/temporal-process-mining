# Temporal Process Mining

This Jupyter Notebook executes process mining on temporal workflow executions

## Definition

Process mining algorithms find a suitable process model that describes the order of events or activities that are observed during a process execution.

## Getting Started

Clone repository and execute

```
docker run --rm -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes -v "${PWD}":/home/jovyan dtornow/temporal-notebook:1.0
```

Navigate to

```
http://localhost:8888
```