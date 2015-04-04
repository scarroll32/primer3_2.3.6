Sphere Genomics's fork of Primer3 2.3.6
---------------------------------------

### Changelog

Increased array size to allow a larger SEQUENCE_EXCLUDED_REGION
src/libprimer3.h:262:#define PR_MAX_INTERVAL_ARRAY 200 -> increased to 500 to handle gene level qPCR

