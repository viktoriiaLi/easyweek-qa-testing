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
