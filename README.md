# RawBrowse AI models

Core AI runtime bundles for RawBrowse: DataComp CLIP and Meta SAM 3.

RawBrowse reads `manifest.json` from this repository’s `main` branch. Model files are hosted as release assets; the manifest restores their bundle-relative paths and records sizes and SHA-256 checksums.

The models-v2-2026-10-08 release contains freshly converted PhotoAIKit bundles. Source exporters use their own pinned Python dependencies; PhotoAIKit’s Swift CoreAI pin is 1953c4f90ba0214c1abc7bebcb9be5107e329a46. Full inference validation in RawBrowse remains to be completed.

Licence texts accompany each model in its Notices directory. SAM 3 requires acceptance of the SAM License in RawBrowse. Copied provenance and notice release paragraphs describe historical Apple-hosted artifacts; their archive hashes and processing records do not describe these new GitHub release files. The live manifest records the exact published file checksums.

See the [RawBrowse build guide](https://github.com/rsyncOSX/RawBrowse/blob/main/Docs/aimodelsdownload.md).
