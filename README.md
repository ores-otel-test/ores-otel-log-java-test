# ores-otel-log-java-test

Exact-head conformance harness for **java**.

This repository tests both `ores-otel/ores.otel.log` and `ORESoftware/next-loggers.ts` using explicit commit SHAs.
The required native command is recorded in `conformance.json`: `mvn --batch-mode --no-transfer-progress verify`.
