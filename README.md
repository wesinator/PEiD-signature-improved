# PEiD-signature-improved

**Deprecation Notice:** YARA rules should be used in place of the legacy PEiD signature format.

See https://github.com/Yara-Rules/rules/blob/60674f7d34c3ec284f4a3bdf9a1ddf1551a1de6d/packers/peid.yar as an example

#

Cleaned up version of the PEiD signature db file

 - Removes false positive Armadillo rules (https://www.zscaler.com/blogs/research/your-windows-8-packed)
 - Standardised encoding to UTF-8
