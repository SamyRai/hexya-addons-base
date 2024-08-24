# Hexya Base Module

[![Build Status](https://travis-ci.com/hexya-addons/base.svg?branch=master)](https://travis-ci.com/hexya-addons/base)  
[![Go Report Card](https://goreportcard.com/badge/hexya-addons/base)](https://goreportcard.com/report/hexya-addons/base)  
[![codecov](https://codecov.io/gh/hexya-addons/base/branch/master/graph/badge.svg)](https://codecov.io/gh/hexya-addons/base)  
[![License: LGPL v3](https://img.shields.io/badge/License-LGPL%20v3-blue.svg)](https://www.gnu.org/licenses/lgpl-3.0)

## Overview

The Hexya Base module is the core component of the Hexya ERP framework, providing essential functionality that other modules build upon. It includes key models like companies, users, attachments, and more, forming the backbone of any Hexya-based ERP application.

## Features

- **Core Models**: Defines models for companies, users, currencies, and other essential entities.
- **Mixins**: Reusable components that extend the functionality of models.
- **Data Management**: Predefined data and configurations for initial setups, including country codes, currencies, and more.
- **Internationalization**: Comprehensive support for multiple languages through `.po` files.

## Installation

To use this module:

1. Add it to your Hexya project’s `go.mod`:
   ```go
   require github.com/hexya-addons/base v0.1.6
   ```
2. Import it in your main setup:
   ```go
   import _ "github.com/hexya-addons/base"
   ```

## Directory Structure

- **Go Source Files**: Core logic for models, mixins, and functionalities.
- **Tests**: Unit tests for validating module functionality.
- **Data**: Predefined CSV files for initial data.
- **Resources**: XML files defining views and model configurations.
- **Localization**: `.po` files for language support.
- **Static Assets**: Images and other static resources.

## Running Tests

Use the provided `run_tests.sh` script to run the tests:

```bash
./run_tests.sh
```

Ensure your environment is properly set up, including the database.

## Contributing

Contributions are welcome! Please follow the [contribution guidelines](https://github.com/hexya-erp/hexya/blob/master/doc/contribution.adoc).

## License

This module is licensed under the LGPL v3.0. See the [LICENSE](https://www.gnu.org/licenses/lgpl-3.0) file for details.