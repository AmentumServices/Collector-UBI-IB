# What is this?

This is a project that automatically collects artifacts to ease in air-gapped transfer from the internet.

It runs actions on Push or on Mondays at 00:00 and creates a release.

In this case, it collects the source code repositories and the associated container images via skopeo for:

- dso.mil IronBank UBI9 Hardened container image
- dso.mil IronBank UBI9-Minimal Hardened container image
- dso.mil IronBank UBI9-Micro Hardened container image
- dso.mil IronBank UBI8 Hardened container image
- dso.mil IronBank UBI8-Minimal Hardened container image
- dso.mil IronBank UBI8-Micro Hardened container image
