# Tianqi WHOOP Health 2026 — Privacy Policy

Last updated: November 3, 2026

## Purpose
Tianqi WHOOP Health 2026 is a personal integration intended solely for its owner's use to download and review their own WHOOP data through the official WHOOP API. It is not affiliated with or endorsed by WHOOP.

## Data and authorization
The integration accesses only data authorized through WHOOP OAuth and enabled scopes. Depending on those permissions, this may include profile information, body measurements, cycles, recovery, sleep, and workouts. The owner can decline authorization or revoke access through WHOOP. The integration does not request or store the owner's WHOOP password.

## Storage and use
The intended local setup stores downloaded health data and OAuth credentials on the owner's Mac for personal synchronization and analysis. Health data and credentials must not be committed to this public repository. Data is retained locally until the owner deletes it. The integration does not sell data or use it for advertising, and does not intentionally upload health records to this policy website.

## Service providers
WHOOP processes API and authorization requests under its own policies. GitHub Pages hosts this public policy and may process visitor connection information. If ngrok is used for an HTTPS OAuth callback, it forwards callback traffic, including the temporary authorization code, to the Mac and may process connection metadata under its own policies. Request-content inspection and logging should be disabled for that callback. Local storage does not mean that authorization traffic bypasses these providers.

## Control and deletion
The owner can stop scheduled synchronization, revoke the integration in WHOOP, and delete local downloaded files and credentials. Revoking access does not automatically erase existing local files. Any backups must be deleted separately if complete removal is desired.

## Contact and changes
This integration is operated by the owner of the GitHub account davidztq-design. For non-sensitive questions, use the repository's Issues page: https://github.com/davidztq-design/whoop-personal-privacy/issues . Do not post health information, authorization codes, secrets, or tokens publicly. This policy will be updated when the integration's actual data practices change.
