# masterhr-licences

Signed licence revocation list read by MasterHR-OS.

`revoked.json` contains only one-way fingerprints, signed with the vendor's key. It reveals no licence numbers, customers or data, and cannot be changed by anyone else: MasterHR-OS ignores any list that is not signed by the vendor or is older than the last one it saw.
