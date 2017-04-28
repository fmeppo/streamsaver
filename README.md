# streamsaver
A set of tools for reliably saving a data stream.

Currently just a placeholder concept.

Several tools (especially backup tools) generate a binary stream - but saving this in an optimal, reliable fashion is often more difficult than it seems.  The stream must survive media failure, internal corruption, and possible manipulation by bad actors.  This toolchain aims to combat this and provide a durable transport format for anonymous binary streams.

Possible stream modification mechanisms include (but are not limited to):
* compression
* encryption
* erasure coding
* embedded checksums and error detection

Several storage vehicles could be included:
* cloud(s)
* files
* raw disks
* host-managed SMR drives
* tape(s)

Additionally, provisions may be added to fold a rudimentary index into the storage medium (allowing for functionality akin to a tape autoloader).  Encryption and authentication provisions may become necessary as well.
