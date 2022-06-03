# We use open source forum service

Date: 2022-06-3

# Status

Accepted

# Context

We need forum to discuss topics between registered and anonymous users

# Decision

For forum, we can implement it from stratch, we can We search for available opensource platforms for forums or we can use forum services from cloud servers. We have selected using open source forum service using same authentication tokens for Spotlight App. We also allow anonymous users to send comments to topics in forums.

# Consequences

Positive:

- We don't need to implement all forum requirements from stratch.
- We don't have to buy something for forum service.

Negative:

- We need a server to maintain and monitor forum updates and security problems.

# Risks:

Using same authentication mechanism might be a security risk.
