# Spring Security + JWT demo 

### Step 1

A `/authenticate` API endpoint
- Accepts user ID and password
- Returns JWT as response

### Step 2

Intercept all incoming requests
- Extract JWT from the header
- Validate and set in execution context