## 11/02 ~ 11/06

- [Settings]
	- [WIP] [Bug 1219690](https://bugzilla.mozilla.org/show_bug.cgi?id=1219690) - Implement \*test\_settings\_change\_ring\_tone.py\* as an integration test in JavaScript
	- [Reviewing] [Bug 1219688](https://bugzilla.mozilla.org/show_bug.cgi?id=1219688) - Implement \*test\_settings\_change\_keyboard\_language.py\* as an integration test in JavaScript
	- [Invalid] [Bug 1219689](https://bugzilla.mozilla.org/show_bug.cgi?id=1219689) - Implement \*test\_settings\_change\_language\_rtl.py\* as an integration test in JavaScript
	- [Reviewing] [Bug 1179666](https://bugzilla.mozilla.org/show_bug.cgi?id=1179666) - Wi-Fi settings should sort network names alphabetically within each signal bar level
	- [Fixed] [Bug 1202939](https://bugzilla.mozilla.org/show_bug.cgi?id=1202939) - [settings] alphabet order addons
	- [Fixed] [Bug 1218705](https://bugzilla.mozilla.org/show_bug.cgi?id=1218705) - [Settings] The descriptions of "Data Connection" and "Data Roaming" should be illustrated more precisely
	- [Fixed] [Bug 1220195](https://bugzilla.mozilla.org/show_bug.cgi?id=1220195) - WebIDE-installed add-ons don't appear in the add-on settings until Settings is restarted
	- [WIP] [Bug 1208893] (https://bugzilla.mozilla.org/show_bug.cgi?id=1208893) - Add a warning text in Low Storage mode to the storage panels
		- Raised a question on [Bug 1204618] (https://bugzilla.mozilla.org/show_bug.cgi?id=1204618), now waiting for a response

- Planned Tasks
	- Testing
		- [Bug 1218698](https://bugzilla.mozilla.org/show_bug.cgi?id=1218698) - [Settings][Add-On] Add integration test for add-on install and removal
		- [Bug 1219691](https://bugzilla.mozilla.org/show_bug.cgi?id=1219691) - Implement \*test\_settings\_gps.py\* as an integration test in JavaScript
		- [Bug 1219692](https://bugzilla.mozilla.org/show_bug.cgi?id=1219692) - Implement \*test\_settings\_passcode.py\* as an integration test in JavaScript
		- [Bug 1219693](https://bugzilla.mozilla.org/show_bug.cgi?id=1219693) - Implement \*test\_settings\_usb\_storage.py\* as an integration test in JavaScript
	- Refactoring
		- [Bug 1178156](https://bugzilla.mozilla.org/show_bug.cgi?id=1178156) - [Settings][meta] Define modules using new syntax provided by Observable
		- [Bug 973432](https://bugzilla.mozilla.org/show_bug.cgi?id=973432) - [Settings][meta] panel refactor with AMD pattern

## 2015 Q4 Goals

1. Remove blocker issues for the Settings app & others, as measured by blocker burn down and days of blocker turnarounds.
- Implement new features for the Settings app & others, as measured by feature burn down and days of blocker turnarounds. (This goal need clarification if we know what feature to work on)
- Help increase unit/integration test coverage, as measured by # of tests planned and/or written.
