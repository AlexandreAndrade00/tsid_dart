## 0.0.4

- Resolved Error in case of web.
  - Problem was about range of number
  - Resolved by replacing int to BigInt for web [lib/src/tsid_web.dart](tsid_web.dart)
  - Some types are mismatched in tsid_default.dart and tsid_web.dart
    - Probably 'BigInt' will be used instead of 'int' for public methods