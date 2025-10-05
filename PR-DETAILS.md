# Turnstile FSM Smart Contract System

## Overview
Implementation of a secure turnstile finite state machine with integrated payment processing for controlled access systems.

## Features
- **State Management**: Robust FSM with locked/unlocked states and automatic timeout
- **Payment Processing**: Secure coin-based payment validation and collection
- **Access Control**: Role-based permissions for operators and collectors
- **Event Logging**: Comprehensive tracking of all turnstile operations

## Technical Implementation
- Two core smart contracts: `turnstile-fsm.clar` and `coin-payment-processor.clar`
- Clean Clarity syntax with comprehensive error handling
- Automated state transitions with configurable unlock duration
- Secure principal-based authorization system

## Testing & Validation
- All contracts pass `clarinet check` validation
- TypeScript unit tests included for comprehensive coverage
- Integration testing with Clarinet development environment

## Contract Details
1. **turnstile-fsm.clar**: Core state machine logic with operator controls
2. **coin-payment-processor.clar**: Payment validation and collection management

## Security Features
- Principal-based access control
- Input validation for all public functions
- Safe state transitions with proper error handling
- Protected admin functions with role verification