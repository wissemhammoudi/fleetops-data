# @fleetbase/fleetops-data

[![codecov](https://codecov.io/gh/fleetbase/fleetops-data/graph/badge.svg)](https://codecov.io/gh/fleetbase/fleetops-data)

[Short description of the addon.]


## Compatibility

* Ember.js v4.8 or above
* Ember CLI v4.8 or above
* Node.js v18 or above


## Installation

```
ember install @fleetbase/fleetops-data
```


## Usage

[Longer description of how to use the addon in apps.]

Payloads expose the read-only `service_stops` array from internal API responses.
Each descriptor identifies a route visit by `key`, `role`, `place_uuid`, tracking,
status, and completion, independently of shared place/waypoint record identities.
Use the descriptor key for destination selection; repeated visits to the same
saved place must not be identified by the place ID alone.


## Contributing

See the [Contributing](CONTRIBUTING.md) guide for details.


## License

This project is licensed under the [GNU Affero General Public License v3.0 or later](LICENSE.md) (`AGPL-3.0-or-later`).
