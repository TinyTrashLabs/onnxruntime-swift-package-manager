# Tiny Trash Labs mirror

A copy of `microsoft/onnxruntime-swift-package-manager`, which started returning 404
around 2026-11-18. Its binary archives on `download.onnxruntime.ai` also stopped
serving (the host's TLS certificate no longer matches its name).

Branch `ttl/1.20`, tag `1.20.1`: upstream `1.20.0` (12ce737) with the two binary
targets pointed at this repo's GitHub release. The archives were rebuilt from a
cached extraction of the original 1.20.0 / 0.13.0 pod archives (same xcframeworks,
re-zipped, so the checksums differ from upstream's). No source changes.

MIT licensed, as upstream (see LICENSE).
