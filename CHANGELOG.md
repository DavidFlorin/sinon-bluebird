# Changelog

3.0.1
---
- Updated Dev Dependencies

3.0.0
---
- Updated peer dependency bluebird to 3.x (still backwards compatible with 2.x)
- Updated to add support up to node 5.x (now supports 0.10 - 5.x)

2.0.0
---
- Removed auto conversion of string in the `.rejects` to Error. So now if you reject a string, the rejected value will remain a string

1.1.1
---
- Added new helper methods for spies to auto unwrap any promise returned from a method or passed into a method. This allows directly comparing values rather than needing to manually unwrap them each time.

1.0.0
---
- Initial release
