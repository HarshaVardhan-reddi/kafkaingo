# kafkaingo

A generalized Kafka wrapper for Go, built for personal projects and rapid development.

---

## Overview

`kafkaingo` provides a clean, reusable interface for producing and consuming Kafka messages across Go projects. Instead of repeating boilerplate configuration and error handling in every project, this package exposes a consistent, minimal API that can be dropped into any Go service.

---

## Goals

- Abstract away low-level Kafka client details
- Provide a simple producer/consumer interface
- Support consumer groups with offset management
- Handle graceful shutdown via context propagation
- Stay lightweight with minimal dependencies

---

## Status

Under active development. API is not stable yet.

---

## License

MIT
