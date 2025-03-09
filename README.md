# Juniper Forensic Hashes

## About
This repository aims to provide a centralized and easily accessible collection of cryptographic hashes for Juniper Networks firmware images (and, where possible, individual extracted files) and associated software. These hashes can be used to verify the integrity of firmware images or installed systems, enabling forensic examination.

While Juniper may provide hashes, they are often scattered across various download pages, unavailable for older releases, or require active support contracts for access. This repository aims to consolidate this information for broader community access. Please refer to offical sources whenever possible.

## Files

Files are sorted into directories based on the name of the "operating system" Juniper has assigned to each product.

  - images.csv
    - OS Name
    - Release
    - Description
    - Release Date
    - File Name (If known, may not be exact)
    - File Extension
    - File Size
    - MD5
    - SHA1 (May be missing on older files)
    - SHA256 (May be missing on older files)
    - SHA512 (May be missing on older files)

## Contributing
Contributions are welcome. Please either contact me directly or include a complete chain of provenance with your pull requests.

## Legal
 - Product names mentioned herein may be trademarks of Juniper Networks or other respective owners.
 - This repository owner is not the author of, nor claims any rights or ownership of, the underlying firmware or software.
 - Users are solely responsible for ensuring their use of this data complies with applicable laws and the original license agreements to which they may be bound.
 - This repository owner provides these hashes "as is" without any warranty, express or implied.
 - Refer to the original Juniper Networks (or other relevant vendor) license agreement for the governing terms of use regarding the firmware or software.
 - The hash list and any associated tools created by the repository owner are made available under the [CC0 1.0 Universal Public Domain Dedication](LICENSE).
