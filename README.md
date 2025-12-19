# CounterPrint Drivers Repository

This repository contains printer drivers used by CounterPrint.

## Structure

/drivers
Official, approved drivers.
Read-only for client applications.

/pending
Drivers submitted by client installations.
These drivers are NOT used in production until manually reviewed
and moved to /drivers by the maintainer.

## Important

- Client applications can upload drivers ONLY to /pending
- Client applications download drivers ONLY from /drivers
- No automatic approval exists
- Do not manually edit files unless you are the maintainer
