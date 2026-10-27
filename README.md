# tier4_autoware_msgs with External Planner
[日本語版READMEはこちら](README_ja.md)

This repository provides additional message definitions required when using the functionality to switch to an external custom planner (`External Planner`) in [Autoware.universe](https://github.com/Toyota/autoware_universe).

For more information about External Planner, please refer to [📖 Autoware.universe](https://github.com/Toyota/autoware_universe).

## Overview

To enable the functionality to switch to an external custom planner (External Planner), the `External` constant has been added to `tier4_planning_msgs/msg/Scenario.msg`.

#### `tier4_planning_msgs/msg/Scenario.msg`

| Constant Name | Type     | Value      | Description           |
| ------------- | -------- | ---------- | --------------------- |
| `EXTERNAL`    | `string` | `External` | ExternalPlanner state |

## License
This project follows the original Autoware.universe project license. See [LICENSE](LICENSE) for details.

## Contribution
Thank you for your interest in this project. We are currently preparing the structure and guidelines to accept external pull requests (planned to start within 2026). In the meantime, please report bugs or request features via Issues.

## Development & Maintenance Members
This project is currently developed and maintained by:

* Yasuaki Miyahara (Toyota Motor Corporation)
* Naoya Hashimoto (Toyota Motor Corporation)
* Shun Takahashi (Toyota Motor Corporation)
* Daichi Tanizaki (Toyota Motor Corporation)

## Contact
Please open an Issue for bug reports or feature requests. We will review and address them as much as possible.
