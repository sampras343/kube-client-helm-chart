# Mosquitto Broker Bare Metal

Publish/Subscribe decouples the client that sends a message (the publisher) from the client or clients that receive the messages (the subscribers).

MQTT uses the topic (subject) of the message to determine which message goes to which client (subscriber). A topic is a hierarchically-structured string that can be used to filter and route messages.

This is the basic Mosquitto image with no ACL or TLS enabled.
