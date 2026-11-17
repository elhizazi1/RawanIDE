# License decision required

The app source archive did not establish an existing project license. Do not publish a new LICENSE without the owner's explicit choice and a dependency/license audit.

**Candidate:** GPL-3.0-or-later, if you want modifications and redistribution of the application source to remain under GPL. Review compatibility with bundled dependencies, assets, and contributor ownership first.

To adopt it, review `LICENSE_GPL-3.0_CANDIDATE.txt`, rename it to `LICENSE`, and add `SPDX-License-Identifier: GPL-3.0-or-later` to relevant metadata. A license file alone does not establish that all third-party components are covered.

If this repository distributes only APK binaries and not the corresponding source, GPL compliance may require providing complete corresponding source and build instructions.
