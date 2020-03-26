# ISCN registry
This a repository to reserve a code for ISCN registry which is a service provider for ISCN registration. The registry should provide service to register a digital content with metadata that follows the [ISCN specification](https://github.com/likecoin/iscn-specs) and to query.

## Description
Find the table of reservation at [registry_code.csv](https://github.com/likecoin/iscn-registry/blob/master/registry_code.csv) or [wiki page](https://github.com/likecoin/iscn-registry/wiki).

### Reserving the new code
To reserve the new code for ISCN registry, please follow the following steps:

1. Fork this repository
1. Update the 3 fields in [registry_code.csv](https://github.com/likecoin/iscn-registry/blob/master/registry_code.csv)
    1. `code`: The ISCN registry reservation code, it must be a positive integer
    1. `name`: The name of the ISCN registry
    1. `description`: A brief description of the ISCN registry
1. Create a pull request

The code reservation based on ***First come, first reserve*** policy.

## License
This repository is only for documents. All of these are licensed under the [CC-BY-SA 4.0 license](https://github.com/likecoin/iscn-registry/blob/master/LICENSE), © 2020 LikeCoin Foundation Ltd.
