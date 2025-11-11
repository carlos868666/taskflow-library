# TaskFlow API Documentation

## Task Methods

### constructor(title, description)
Creates a new task

### updateStatus(status)
Updates task status

### setPriority(priority)
Sets task priority. Valid values: 'low', 'medium', 'high', 'urgent'
Returns: boolean - true if priority was set
