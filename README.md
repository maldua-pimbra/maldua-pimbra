# maldua-pimbra - Patched Zimbra repos (Main repo)

This organisation will have Zimbra repos patches with **community based changes (mainly security fixes) which are not found in the upstream repos in a timely manner**.

Some of these repos will be fetched from [Zimbra FOSS Builder](https://github.com/maldua/zimbra-foss-builder).

In the future we might add some scripts to this repo so that we are able to find or create this differences from Zimbra Network Edition binaries.
This is similar to what this [Zimbra.org forum thread: FOSS - How to patch/build source to include missing commits for 10.1.5/6](https://forums.zimbra.org/viewtopic.php?t=73348) describes.

## Patches policy

- Patches will be minimal so that Zimbra builds based on those patches are as similar as possible as their Zimbra NE counterparts.

## How to use

If you have a Zimbra build wrapper script you can check [maldua-pimbra-config repo](https://github.com/maldua-pimbra/maldua-pimbra-config/) to learn on how to integrate Pimbra onto your system.

## Similar alternatives

- Manual CVE-2025-27915 patch: [FOSS - How to patch/build source to include missing commits for 10.1.5/6](https://forums.zimbra.org/viewtopic.php?t=73348)
- [Ianw1974's zimbra-build-scripts](https://github.com/ianw1974/zimbra-build-scripts) uses an alternate method of applying changes based on a [patches directory](https://github.com/ianw1974/zimbra-build-scripts/tree/558ae8cdcf97ff2e1cad277e1c9484a6d2c8d8fe/patches).
