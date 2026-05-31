# dep-scan-malicious-demo

Test repository for the Maze dependency scanner.

This repo intentionally references a known malicious npm package
(`buffer-utilities@1.0.0`, listed as MAL-2026-5087 in the OSV
Malicious Packages feed) so the scanner has a malicious_package
finding to surface.

Do NOT run `npm install` against this lockfile.
