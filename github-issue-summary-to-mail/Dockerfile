
# Use the official Ballerina image
FROM ballerina/ballerina:latest

# Set the working directory inside the container
WORKDIR /app

# Copy the entire project into the container
COPY . /app

# Set the entry point to run the Ballerina program with the compiled project
CMD ["bal", "run", "target/bin/github_issue_summary_to_email.jar"]


