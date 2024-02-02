# Queue Management System

This project implements a queue management system that allows customers to register and receive tickets, and staff members to manage the queue.

## Components

### Register.jsx

- Allows customers to request a ticket by clicking on a button (Print functions need to be implemented)
- Displays the number that the customer will receive

### Index.jsx

- Displays the registered list of tickets
- Staff members can call the next number using the call button
- Staff members can recall the current number using the repeat call button
- Provides a clear queue button to remove all registered tickets
- Provides a reset queue button to reset the ticket numbers (starting from 1)

### Display.jsx

- Displays the current ticket number
- When a new number is called, an animated transition occurs for 2 seconds
