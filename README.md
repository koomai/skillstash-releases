# SkillStash — downloads

SkillStash is a macOS app for managing [Agent Skills](https://code.claude.com/docs/en/skills):
one Core Repository of Skills on your machine, installed into whichever projects you point it at.

## Download

Every build is on the [Releases page](https://github.com/koomai/skillstash-releases/releases).
Download `SkillStash-arm64.dmg` from the latest release.

Requires macOS 12 or later on Apple silicon.

## First launch

SkillStash is unsigned, so macOS says it "is damaged and can't be opened".
After dragging it to Applications, run this in Terminal:

```sh
xattr -dr com.apple.quarantine /Applications/SkillStash.app
```

Run it again after installing each new version.

## Issues

Bugs, crashes and feature requests: [open an issue](https://github.com/koomai/skillstash-releases/issues/new).
Include your macOS version and the SkillStash version from the release you installed.

## Licence

Free to use for personal and commercial work. See [LICENSE](LICENSE).
