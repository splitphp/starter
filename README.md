![splitphp-logo.png](https://splitphp-media-archive.s3.us-east-1.amazonaws.com/SPLIT_PHP-logo-full.png)

[![Core version](https://img.shields.io/packagist/v/splitphp/core.svg)](https://packagist.org/packages/splitphp/core)

Boilerplate project to scaffold a new SplitPHP application.

## Installation

You can get started in two ways:

### 1. Via Composer

```bash
composer create-project splitphp/starter myapp
cd myapp
```

This will install the `splitphp/core` engine and set up the basic directory structure.

### 2. Download ZIP (For non-composer users)

1. Go to the [Releases page](https://github.com/splitphp/starter/releases).
2. Download the **`splitphp-distribution-<version>.zip`** asset.
3. Extract it:

   ```bash
   unzip splitphp-distribution-<version>.zip -d myapp
   cd myapp
   ```

## Directory Structure

```
myapp/
├── core/       # SplitPHP core framework
├── application/  # Application-specific code (user-defined code)
├── modules/      # Reusable scalable modules (user-defined code)
├── public/       # Web entry-point (e.g. index.php)
├── config.ini    # Configurations file
└── README.md     # This file
└── LICENSE       # MIT License file
└── console       # CLI entry-point
```

## Getting Started

1. Setup your application:

  ```bash
  php console setup
  ```
  This will create your application hash keys and config.ini file from example.config.ini, so you don't have to rename it manually.

2. Run your application's dev server:

  ```bash
  php console server:start
  ```
  This will create your application hash keys and config.ini file from example.config.ini, so you don't have to rename it manually.
  
3. Access http://localhost:8000 in the browser and you shall see the **SPLIT PHP** Welcome Page.

## Documentation

For a more complete documentation, usage examples, and advanced topics, see the [SplitPHP Core repository](https://github.com/splitphp/core) README.

---

© Gabriel Valentoni Guelfi | MIT License
