# mongodb

This recipe shows a working example of MongoDB on Spin using the official managed image
with an automated backup routine.

Features of this recipe:
  * Persistent storage on Rancher NFS.
  * Login credentials on Rancher Secrets.
  * Optional direct access vi mongo shell from within NERSC networks.
  * Health checking and automatic rescheduling in the event of problems.
  * Enhanced security through a reduced set of capabilities.

To use this recipe, incorporate it into your `docker-compose.yml` and `rancher-compose.yml`,
substituting the appropriate values as described in the comments.
