# Library Apple relinking materials

[Library support](https://ryanemmick.com/library) · [Build 52 downloads](https://github.com/emmick4/library-apple-relink/releases/tag/0.5.28-52)

This repository distributes the open-source playback-library sources and application object files needed to relink Library for iPhone and iPad with modified LGPL libraries. It does not provide a Library account or access to household media.

The **0.5.28 (52)** release contains two archives that extract into the same directory. Download both, verify the supplied SHA-256 checksums, then read `README.txt` and the source index. The relink kit includes application objects, selected iOS arm64 static libraries, headers, resources, notices, and relinking and own-signing scripts. The source archive includes the matching upstream releases, build scripts, patches, and dependency sources with their provenance.

The app and controls extension have been relinked using these materials and Xcode 27.0. Device installation with another Apple team is documented separately; publisher signing credentials are not part of the downloads. The source index records the upstream uavs3d build recipe's floating-branch provenance limit. A complete upstream library rebuild and bit-for-bit reproduction of every library are not claimed.

Application-object permissions and third-party licenses are included with the downloads. See the [GNU LGPLv3](https://www.gnu.org/licenses/lgpl-3.0.html) for its combined-work provisions.

Questions: [library@emmick.co](mailto:library@emmick.co).
