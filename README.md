# SpareGrid

SpareGrid is an experimental distributed compute platform that turns idle computers into a shared pool of computing resources.

The platform schedules workloads across heterogeneous, intermittently available machines, with a focus on sandbox isolation, fault recovery, and efficient resource utilization.

## Initial scope

Build a central control plane and worker agents capable of scheduling and executing trusted tasks across multiple nodes.

## Long-term goals

- Resource-aware scheduling
- Opportunistic node availability
- Isolated VM sandboxes
- Durable execution and fault recovery
- VM snapshot and restore
- Benchmark-driven performance optimization

## Initial non-goals

- Public, untrusted compute marketplace
- Cross-platform VM migration
- Production-grade multi-tenancy
- GPU workload support
