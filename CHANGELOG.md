# HeyCC Changelog

HeyCC 的产品级公开变更记录。模块变化按 `heycc-plugin` 和 `heycc-cookbook` 分组；未来产品使用各自的 `*-release/CHANGELOG.md`，不会合并到这里。

## [Unreleased]

### heycc-plugin

- Added the initial public marketplace directory structure.
- Added the HeyCC plugin manifest and marketplace schemas.
- Added a minimal plugin template and submission guidance.
- Documented the trust boundary: marketplace metadata cannot execute arbitrary install or probe commands.

### heycc-cookbook

- Added the first plugin browsing, installation, and submission recipes.
- Added the iTermux Bridge platform and installation-boundary recipe.

### Security

- Documented that third-party source, licenses, fixed revisions, and platform constraints must be disclosed before publication.
