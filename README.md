# Islandora Owner Permissions

## NOTE:

This repository is deprecated. Please see [its new location as a submodule](https://github.com/discoverygarden/islandora_access_override/tree/7.x/modules/islandora_owner_permissions)
of [islandora_access_override](https://github.com/discoverygarden/islandora_access_override).

## Introduction

Creates several permissions that allow owners of objects and their proxies to
perform management acts on those objects when they do not have blanket write
access to the repository.

Caution using this module in a multisite environment is recommended. The Drupal
user name that is used as the Fedora object's owner can exist as two different
users in different sites giving each user access to the other's objects.

## Requirements

This module requires the following modules/libraries:

* [Islandora](https://github.com/islandora/islandora)

## Installation

Install as usual, see
[this](https://drupal.org/documentation/install/modules-themes/modules-7) for
further information.

## Configuration

This module uses the core user autocomplete for the `Owner Proxy` form element.
if you want to take advantage of this autocomplete the user will need the
permission `View user profiles`.

## Troubleshooting/Issues

This module mirrors core permissions and does not create new conventions. Since
in the Islandora permissions set to access the UI to purge an object one must
have permissions to manage its properties the same is true with the permission
set provided by this module.

Having problems or solved a problem? Contact
[discoverygarden](http://support.discoverygarden.ca).

## Maintainers/Sponsors

Current maintainers:

* [discoverygarden](http://www.discoverygarden.ca)

## Development

If you would like to contribute to this module, please check out our helpful
[Documentation](https://github.com/Islandora/islandora/wiki#wiki-documentation-for-developers),
[Developers](http://islandora.ca/developers) section on Islandora.ca and
contact [discoverygarden](http://support.discoverygarden.ca).

## License

[GPLv3](http://www.gnu.org/licenses/gpl-3.0.txt)
