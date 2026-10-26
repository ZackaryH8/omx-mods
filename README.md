# OMX official mods

This repository publishes the mod list shown in every OMX client's **Mods** menu. OMX reads
[`catalog.json`](catalog.json) and installs ZIP packages whose SHA-256 matches the catalog entry.
The first listed package, Intelligent Speed Assistance, is MIT licensed and also ships inside OMX.

To add another author's mod, link its original HTTPS ZIP download in `downloadUrl` when possible.
Set the original author, project homepage, version, and SHA-256 in the catalog. Obtain permission
before copying somebody else's archive into this repository. To publish an update, keep the same
`id`, change `version`, and update `downloadUrl` and `sha256` for the new ZIP.

OMSI content ZIPs contain folders such as `Vehicles`, `maps`, `Sceneryobjects`, or `Splines` at
their root, optionally inside one enclosing folder. OMX code resource ZIPs contain
`omx-resource.json` and their declared assemblies; these apply when OMX next starts. Players can
also install a downloaded ZIP directly from the Mods menu without adding it to this list.
