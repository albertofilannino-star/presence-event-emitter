# Protocol overview

This document describes the external communication behavior of the device.

## Scope
The protocol defines how presence events are transmitted from the device to a backend system.
It does not define business logic, validation rules or data interpretation.

## Responsibilities
- Device: emit presence events over the network
- Backend: receive events, assign timestamps, validate and persist

## Stability
The protocol is designed to be simple and stable over time.
Backward compatibility is preferred over feature expansion.

