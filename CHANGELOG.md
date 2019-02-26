# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.4.0] - 8 April 2019

### Added

- Added rubocop-rspec version `1.32.0`
- Added the cop `Capybara/CurrentPathExpectation`
- Added the cop `Capybara/FeatureMethods`
- Added the cop `FactoryBot/AttributeDefinedStatically`
- Added the cop `FactoryBot/CreateList` with `EnforcedStyle: create_list`
- Added the cop `Rails/HttpStatus` with `EnforcedStyle: symbolic`
- Added the cop `RSpec/AnyInstance`
- Added the cop `RSpec/AroundBlock`
- Added the cop `RSpec/Be`
- Added the cop `RSpec/BeEql`
- Added the cop `RSpec/BeforeAfterAll`
- Added the cop `RSpec/ContextWording`
- Added the cop `RSpec/DescribeClass`
- Added the cop `RSpec/DescribeSymbol`
- Added the cop `RSpec/DescribedClass` with `EnforcedStyle: described_class`
- Added the cop `RSpec/DescribeMethod`
- Added the cop `RSpec/EmptyExampleGroup`
- Added the cop `RSpec/EmptyLineAfterExampleGroup`
- Added the cop `RSpec/EmptyLineAfterFinalLet`
- Added the cop `RSpec/EmptyLineAfterHook`
- Added the cop `RSpec/EmptyLineAfterSubject`
- Added the cop `RSpec/ExampleLength` with `Max: 5`
- Added the cop `RSpec/ExampleWithoutDescription` with `EnforcedStyle: single_line_only`
- Added the cop `RSpec/ExampleWording`
- Added the cop `RSpec/ExpectActual`
- Added the cop `RSpec/ExpectChange` with `EnforcedStyle: block`
- Added the cop `RSpec/ExpectInHook`
- Added the cop `RSpec/ExpectOutput`
- Added the cop `RSpec/FilePath` with `IgnoreMethods: false`
- Added the cop `RSpec/Focus`
- Added the cop `RSpec/HookArgument` with `EnforcedStyle: implicit`
- Added the cop `RSpec/HooksBeforeExamples`
- Added the cop `RSpec/ImplicitExpect` with `EnforcedStyle: is_expected`
- Added the cop `RSpec/ImplicitSubject` with `EnforcedStyle: single_line_only`
- Added the cop `RSpec/InstanceSpy`
- Added the cop `RSpec/InstanceVariable` with `AssignmentOnly: true`
- Added the cop `RSpec/InvalidPredicateMatcher`
- Added the cop `RSpec/ItBehavesLike` with `EnforcedStyle: it_behaves_like`
- Added the cop `RSpec/IteratedExpectation`
- Added the cop `RSpec/LeadingSubject`
- Added the cop `RSpec/LetBeforeExamples`
- Added the cop `RSpec/LetSetup`
- Added the cop `RSpec/MessageSpies` with `EnforcedStyle: receive`
- Added the cop `RSpec/MissingExampleGroupArgument`
- Added the cop `RSpec/MultipleDescribes`
- Added the cop `RSpec/MultipleExpectations` with `Max: 5`
- Added the cop `RSpec/MultipleSubjects`
- Added the cop `RSpec/NestedGroups` with `Max: 5`
- Added the cop `RSpec/OverwritingSetup`
- Added the cop `RSpec/Pending`
- Added the cop `RSpec/PredicateMatcher` with `EnforcedStyle: inflected` and `Strict: true`
- Added the cop `RSpec/ReceiveNever`
- Added the cop `RSpec/RepeatedDescription`
- Added the cop `RSpec/RepeatedExample`
- Added the cop `RSpec/ReturnFromStub` with `EnforcedStyle: and_return`
- Added the cop `RSpec/ScatteredLet`
- Added the cop `RSpec/ScatteredSetup`
- Added the cop `RSpec/SharedContext`
- Added the cop `RSpec/SharedExamples`
- Added the cop `RSpec/SingleArgumentMessageChain`
- Added the cop `RSpec/SubjectStub`
- Added the cop `RSpec/UnspecifiedException`
- Added the cop `RSpec/VerifiedDoubles`
- Added the cop `RSpec/VoidExpect`
- Added the cop `RSpec/Yield`

---

## [0.3.1] - 25 January 2019

### Added

- Added the cop `Rails/BelongsTo`
- Added the cop `Rails/IgnoredSkipActionFilterOption`
- Added the cop `Rails/LinkToBlank`
- Added the cop `Style/DisjunctiveAssignmentInConstructor`

### Changed
- Bumped rubocop to version `0.63.0`

---

## [0.3.0] - 18 December 2018

### Added
- Added the cop `Performance/ChainArrayAllocation`
- Added the cop `Performance/OpenStruct`
- Added the cop `Style/IpAddresses`
- Added the cop `Style/MultilineMethodSignature`

### Changed
- Bumped rubocop to version `0.61.1`

---

## [0.2.0] - 24 July 2018

### Added

- Added the cop `Layout/ClosingHeredocIndentation`
- Added the cop `Layout/LeadingBlankLines`
- Added the cop `Lint/ErbNewArguments`
- Added the cop `Lint/SafeNavigationConsistency`
- Added the cop `Lint/SplatKeywordArguments`
- Added the cop `Performance/InefficientHashSearch`
- Added the cop `Performance/UnneededSort`
- Added the cop `Rails/AssertNot`
- Added the cop `Rails/BulkChangeTable`
- Added the cop `Rails/HttpStatus`
- Added the cop `Rails/RefuteMethods`
- Added the cop `Style/AccessModifierDeclarations`
- Added the cop `Style/MethodMissingSuper`
- Added the cop `Style/MissingRespondToMissing`
- Added the cop `Style/UnneededCondition`

### Disabled

- Disabled the cop `Style/UnpackFirst`

### Changed

- Bumped rubocop to version `0.57.2`
- `Style/MethodMissing` is now enabled

---

## [0.1.8] - 20 March 2018

### Added

- Re-enable `Style/FrozenStringLiteralComment` cop to be YC compliant
- Add `training` and `review` as valid environments for the `Rails/UnknownEnv` cop

## [0.1.7] - 15 March 2018

### Added

- We don't care that much about `Style/FrozenStringLiteralComment`. Disabled the cop.

### Changed

- Moved `Lint/EndAlignment` to the new namespace: `Layout/EndAlignment`

## [0.1.6] - 15 March 2018

### Changed

- Removed the `Style/Encoding: EnforcedStyle` option because it's removed

## [0.1.5] - 15 March 2018

### Added

- Introduced the Changelog

### Changed
- Updated Rubocop version to 0.53

---