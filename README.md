# Micromodal vs Parcel vs IE 11

Demo of problems when building Micromodal with Parcel for IE 11.

Parcel cannot figure out how to handle Micromodal because there's no `engines` specified in `package.json`, so it spits it out as-is. This causes browsers that don't support features like backticks and spread to choke.
