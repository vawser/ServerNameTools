#----------------------------------------
# Description
#----------------------------------------
hkxpack-souls alpha 3 (Ds3 Only)

Fixed class definitions for ds3 using defs from HKX2. Should now properly support all havok files.

Fixed a bug where file extensions were not case insensitive which would lead to hkxpack not working for ragdoll files (extension .HKX) unless the file was renamed

alpha 2 had a known issue with reading and writing hkbFootIKControlsModifiers. If you used hkxpack previously to edit behavior files it is recommended to copy the hkbFootIKControlsModifier from the vanilla file and repack with the new version to fix IK issues.

When unpacking behavior files from previous versions of hkxpack hkbManualSelectorGenerators might have an incorrect value for their endOfClipEventId field. These should all be set to -1 to mimic vanilla (can be done using search and replace).

#----------------------------------------
# Credits
#----------------------------------------
The12thAvenger
katalash