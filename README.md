# Distributed Ticket Booking System

## Overview
This project simulates a distributed theater ticket booking system with multiple ticket counters operating concurrently under weak consistency conditions.

The system demonstrates how distributed nodes handle booking and cancellation requests locally before synchronizing with a shared global state using synchronization locks.

## Concepts Implemented
- Weak Consistency
- Concurrency
- Synchronization Locks
- Shared State Management
- Overbooking Protection
- Distributed System Simulation
- Audit Logging
- Local vs Global State Synchronization

## Features
- Multiple ticket counters operating in parallel
- Local booking/cancellation queues
- Synchronization rounds with locking mechanisms
- Weak consistency simulation with stale reads
- Overbooking prevention
- Global audit logging
- Final invariant consistency validation

## Technologies Used
- Python
- Google Colab
- Distributed Systems Concepts
- Concurrency & Synchronization

## Example Output
- Local counter operations
- Synchronization rounds
- Global seat updates
- Final consistency validation report

## Project Status
Completed
