# Detecting (Malicious) Unicode in GitHub PRs

Demonstrates GitHub Actions workflow for Detecting (Malicious) Unicode in GitHub PRs

<p align="center">
  <a href="https://tech.michaelaltfield.net/bidi-unicode-github-defense/"><img src="bidi-unicode-github-defense_featuredImage2.jpg?raw=true" alt="Detecting Malicious Unicode in GitHub Pull Requests"/></a>
</p>

For more information, see this article:

 *  https://tech.michaelaltfield.net/bidi-unicode-github-defense/

# Demo

See the following PRs for this repo, which demonstrate the detection of malicious unicode that were attempted to be merged into `main` from user-contributed, malicious branches

 * https://github.com/maltfield/detect-malicious-unicode/pull/1
 * https://github.com/maltfield/detect-malicious-unicode/pull/2

The comments in the PRs were made by the following GitHub Actions workflow:

 * https://github.com/maltfield/detect-malicious-unicode/blob/main/.github/workflows/unicode_warn.yml

## In the wild

The following GitHub CI workflows have been integrated into other projects' GitHub repos to detect malicious unicode characters

 * [BusKill](https://github.com/BusKill/buskill-app/blob/c764ea7fd649f0f576e68ba9272cd8b3ed36f167/.github/workflows/unicode_warn.yml)

# License

The contents of this repo are dual-licensed. All code is GPLv3 and all other content is CC-BY-SA.


