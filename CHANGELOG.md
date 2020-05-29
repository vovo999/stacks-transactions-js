# Changelog
All notable changes to the project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

### Added
- Added `parseToCV()` utility function to convert string input to the appropriate Clarity value based on the Clarity ABI type specified by the contract function

### Changed
- tx broadcast now returns a response type which may contain an error

## v0.4.4

### Added
- Ability to broadcast raw transactions using `broadcastRawTransaction()`
- `abiFunctionToString()` method for converting ABI function typedef to Clarity repr string

### Changed
- Changed the format that the type -> string functions output to match Clarity type repr

## v0.4.2 

### Added
- Add cvToString() method for converting ClarityValue objects to their string (source code) representation

### Changed

## v0.4.1 

### Added
- ABI validation for contract-call transactions
- Additional methods added to the StacksNetwork interface

### Changed

