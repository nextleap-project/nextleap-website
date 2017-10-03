---
title: Simpler secure group messaging?

date: 2017-07-20

location: Web

event_url: https://conspicuouschatter.wordpress.com/2017/07/20/simpler-secure-group-messaging-pets17/
---

[New article : Simpler secure group messaging?](https://conspicuouschatter.wordpress.com/2017/07/20/simpler-secure-group-messaging-pets17/)

Advocates for :

- Ditch full plausible deniability; use signatures, and rely on honest parties to delete them upon checking.
- Design systems for optimal operation with group sizes of 3-50. There is no point in having much larger groups, or killing designs on the basis they do not perform when N goes to infinity.
- Rely on an infrastructure server or a leader within the group to offer consistent total ordering to all. Assume that others can detect its liveness through a timeout (synchronous), and either elect or rotate another one in. Or simply, stop the chat session once they become unavailable.
