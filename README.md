# Expiry Reminder Script
Summary - A simple script to all the certificates and profiles on Apple Developer Portal which are going to expiry within the given number of days.

### Why do we need this?
- Apple developers have their certificates and profiles on the developer portal.
- Different profiles and certificates have different expiry periods.
- Although Apple does send email notification 30 days before expiry, but we all agree that emails suck!! :innocent:

### What does this script do?
- Fetch all the certificates and profiles and filter them according to the condition - if they are within the expiry period.
- Generate a message and notify the users on Flock Channel. (Get Flocking here: - www.flock.com)