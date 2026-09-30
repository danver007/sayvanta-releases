# Sayvanta releases

This public repository holds only what installed copies of Sayvanta and the Sayvanta website need
to find and verify releases:

- signed macOS disk images and Windows installers, attached to GitHub Releases;
- `appcast.xml` for macOS updates (EdDSA-signed update entries);
- `release.json`, an Ed25519-signed manifest the website and the Windows updater verify;
- the Windows update feed (`releases.win.json` and full packages);
- release notes, taken from the product changelog.

It contains no application source code. Releases are published by an automated, fully tested
pipeline from a verified draft; published versions are never modified. Always download Sayvanta
from its website or the latest release here, and let the app update itself.

## License

Sayvanta is proprietary software. The binaries published here are provided so you can install and
update Sayvanta, subject to the Sayvanta license terms, which will be published with the first
public release. Third-party components and their licenses are listed in the notices shipped with
the application.
