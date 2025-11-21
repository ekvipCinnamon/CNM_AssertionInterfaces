# CNM AssertionInterfaces lib

## Overview

This is a TwinCAT 3 library project that provides an abstract Assertor class. It can be extended to use the assertions and throw events in case an assertion was wrong.

## Version Information

- **Version:** 0.1.1.0
- **Release Date:** 2025
- **Format:** Markdown (.md)
- **Language:** English

## Documentation Location

You will find the detailed library documentation at the [cinnamon docs](https://static.ekvip.de/docs/CNM_AssertionInterfaces/0.1.1.0/)

## Purpose

Assertions enforce invariants during runtime. They expose design faults early by halting or flagging when a condition that must always be true is violated. Typical uses: validating state-machine transitions, confirming sensor range assumptions, guarding against impossible branches, checking configuration constants, verifying communication payload structure, preventing silent overflow or wraparound in arithmetic, and locking down preconditions before executing safety-relevant logic.

## License

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

## Copyright

© 2025 ekvip automation GmbH

**Contact Information:**
- Email: cinnamon@ekvip.com
- Website: www.ekvip.com

## Usage

1. Install the library using the TwinCat library repositiory
2. add the library as reference to your PLC project
3. Follow the guidelines for your TwinCAT 3 development projects

## Contributing

For questions, feedback, or contributions, please contact:
- Email: cinnamon@ekvip.com

## Changelog

### Version 0.1.1.0
*	Build with TwinCAT version 4026.19
*	Used TwinCAT libraies:
	*	Tc2_Standard 3.4.*
	*	Tc2_System 3.9.*
	*	Tc2_Utilities 3.10.*
* 	Used CNM libraries:
	*	CNM_AbstractObject 1.*
	*	CNM_ReturnTypes 1.*
	*	CNM_UnicodeUtilities 0.1.*
*	library namespace is *CNM_AssertionInterfaces*
*	library placeholder is *CNM_AssertionInterfaces*
*	libaray category is ekvip|base|utilities

---

**Disclaimer:** This documentation is provided "as is" without warranty of any kind. Users are responsible for ensuring compliance with their specific development requirements and standards.