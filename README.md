# Pretty Progress app messages

Public replacement destination for Pretty Progress message data.

Production endpoint:
https://keinois.github.io/pretty-progress-app-messages/PrettyProgressMessages.json

`PrettyProgressMessages.json` preserves the existing public message payload without changing application targeting or localization.

The legacy repository and endpoint remain available for installed apps:
https://rosday.github.io/AppAlert/PrettyProgressMessages.json

There is no automatic mirroring between the two repositories. When publishing message changes, maintain compatible payloads at both endpoints for the client versions that use them. Retaining the legacy repository is intentional; do not rename, unpublish or delete it while installed clients still use its URL.

Creating this repository does not switch installed apps. Client configuration changes and app releases require their own authorization.
