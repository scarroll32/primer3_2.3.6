Sphere Genomics's fork of Primer3 2.3.6
---------------------------------------

### Changelog
2015-04-04
Increased array size to allow a larger SEQUENCE_EXCLUDED_REGION. This was done to allow more SNPs to be masked via this field, for single run gene level qPCR.
src/libprimer3.h:262:#define PR_MAX_INTERVAL_ARRAY 200 -> increased to 500 

