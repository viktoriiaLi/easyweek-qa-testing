# Test Scope

This document defines the functional areas that are prioritized for testing based on business risks and system criticality.

## In Scope

### 1. Appointment booking conflict prevention
- Prevention of double booking for the same time slot and service
- Validation of system behavior when multiple booking attempts occur simultaneously

### 2. Client contact data validation
- Validation of phone number input during the booking process
- Prevention of bookings with invalid or missing contact information

### 3. Service compatibility rules
- Validation of business rules for booking multiple services
- Prevention of booking incompatible services at the same time

## Out of Scope
- Performance testing
- Security testing
- Mobile application testing
