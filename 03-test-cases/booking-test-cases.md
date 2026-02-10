# Booking Test Cases

## TC-01: Prevent double booking for the same time slot

**Preconditions:**
- Service exists
- Time slot is available
- No existing bookings for the selected time

**Steps:**
1. Client A selects a service
2. Client A selects an available time slot
3. Client A successfully completes the booking
4. Client B selects the same service
5. Client B checks the list of available time slots

**Expected Result:**
- The booked time slot is no longer displayed as available
- Client B cannot select or book the same time slot

## TC-02: Validate client contact data during booking

**Preconditions:**
- Service exists
- Time slot is available

**Steps:**
1. Client selects a service
2. Client selects an available date and time
3. Client proceeds to the booking form
4. Client enters invalid or incomplete contact data (e.g. empty phone field, invalid phone format)
5. Client attempts to proceed with booking

**Expected Result:**
- The system displays a validation error
- Booking cannot be completed with invalid contact data
