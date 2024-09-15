# Custom Version of Firebase Admin Node SDK

## Overview

This repository contains a **custom version** of the [Firebase Admin Node SDK](https://github.com/firebase/firebase-admin-node), which has been modified to suit specific platform requirements. **I do not own the original code**; these modifications are built upon the open-source code provided by the Firebase team.

## License

The original code is licensed under the [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0). You can find a copy of the license in this repository.

## Changes Made

The following modifications have been made to the original code:
- Adding the sendEach method from version 12.4 that invokes operations on the new API version
- Method sendMultiCast now invokes that sendEach instead of sendAll 
- Adding required classes and data objects 

These changes are intended for specific use cases and are **not officially supported** by Firebase or Google.

## Disclaimer

- **I do not own the original source code** of the Firebase Admin Node SDK. This is a derivative work made in accordance with the Apache License 2.0, which allows for modification and redistribution as long as the terms of the license are followed.
- This version of the SDK is provided "as is," without any warranties or official support from Firebase or Google.

## Acknowledgements

The original Firebase Admin Node SDK is an open-source project created and maintained by the [Firebase team](https://github.com/firebase/firebase-admin-node).

