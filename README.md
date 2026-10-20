# SYSWERX audit anchors

One file per day under `anchors/`, written once by the SYSWERX server after its nightly audit chain check and never edited. Each file holds the Merkle root of every case audit chain head as of that night, the number of cases and teams behind it, and an ECDSA P-256 signature over those fields.

What it proves: that a chain head existed by that day. A case file exported from SYSWERX carries a seal with its inclusion proof; paste it at https://syswerxintel.com/audit-seal.html, or verify this day's file there, against the public key at https://syswerxintel.com/api/audit/key (fingerprint on https://syswerxintel.com/trust.html). GitHub's commit timestamps are the outside record that the file arrived on its day.

Nothing here identifies a case, a researcher or a team.

