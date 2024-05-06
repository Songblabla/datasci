# DSDE_Project

Welcome to "I don't even know what i'm doing in this DSDE Project" Project !

## Makefile Commands

Here’s how you can use the Makefile to control your Docker containers:

### Starting Services

- **`make run`**: 
  Starts all services defined in the Docker Compose file. This is your go-to command to boot up the entire stack, making all services operational.

### Stopping Services

- **`make down`**:
  Stops all running services and removes the containers to ensure a clean state for the next run. Use this when you are done working or need to bring everything down quickly.

### Cleaning Up

- **`make clean`**:
  Removes all containers, networks, and images created by Docker Compose. This is useful for freeing up space and ensuring that no remnants from previous builds affect your next run.

### Viewing Logs

- **`make logs`**:
  Tails the logs for all containers. It’s an essential command for debugging and monitoring the live output from your services.

### Restarting Services

- **`make restart`**:
  Restarts all the services. This is helpful when you have made changes that require a reboot of the system without needing to completely rebuild the containers.

### Rebuilding Services

- **`make rebuild`**:
  A combination of stopping, cleaning, building from scratch, and starting the services again. Use this command if you've made significant changes to the Docker configurations or source code that need a fresh environment to take effect.

## Conclusion

These Makefile commands are designed to provide shortcuts for managing Docker operations, making it easier to handle complex service configurations and routine tasks without manually typing lengthy Docker commands. Use these to enhance your workflow and maintain your project efficiently.
