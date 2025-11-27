FROM node:16

WORKDIR /usr/src/app

# Copy entrypoint script into container working directory
COPY entrypoint.sh .

# Make script executable
RUN chmod +x entrypoint.sh

# Run script when container starts
ENTRYPOINT ["./entrypoint.sh"]
