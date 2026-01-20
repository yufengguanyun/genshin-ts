# Changelog

## v0.1.3

- The type system now automatically constrains node availability between Beyond Mode and Classic Mode
- Support placeholder methods like dict(0) and list(0) to allow empty argument pins in some nodes
- Added more detailed hover docs and usage notes for helper functions like raw/float/int/guid/list/dict
- Added a new Classic Mode node: `Revive Active Character`
- Fixed an error when creating the `Teleport Player` node in Classic Mode

## v0.1.2

- g.server() now accepts a mode field to switch between Beyond Mode and Classic Mode
- Added 14 new server nodes introduced in version 6.3, plus related entity helper properties and methods such as .activeCharacter and .classicModeId
- The type system does not yet distinguish node availability by mode; all nodes can be injected regardless of mode and must be used with care

## v0.1.1

- Initial release
