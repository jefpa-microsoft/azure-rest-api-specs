# HealthcareApis

> see https://aka.ms/autorest

This is the AutoRest configuration file for HealthcareApis.

---

## Getting Started

To build the SDK for HealthcareApis, simply [Install AutoRest](https://aka.ms/autorest/install) and in this folder, run:

> `autorest`

To see additional help and options, run:

> `autorest --help`

---

## Configuration

### Basic Information

These are the global settings for HealthcareApis service.

``` yaml
title: HealthcareApisManagementClient
description: Azure Healthcare APIs Client
openapi-type: arm
tag: package-preview-2025-04-01
azure-arm: true
```


### Tag: package-preview-2025-04-01

These settings apply only when `--tag=package-preview-2025-04-01` is specified on the command line.

```yaml $(tag) == 'package-preview-2025-04-01'
input-file:
  - Microsoft.HealthcareApis/preview/2025-04-01-preview/healthcare-apis.json
```

### Tag: package-preview-2025-03-01

These settings apply only when `--tag=package-preview-2025-03-01` is specified on the command line.

```yaml $(tag) == 'package-preview-2025-03-01'
input-file:
  - Microsoft.HealthcareApis/preview/2025-03-01-preview/healthcare-apis.json
```

### Tag: package-2024-03-31

These settings apply only when `--tag=package-2024-03-31` is specified on the command line.

``` yaml $(tag) == 'package-2024-03-31'
input-file:
  - Microsoft.HealthcareApis/stable/2024-03-31/healthcare-apis.json
```

### Tag: package-2024-03

These settings apply only when `--tag=package-2024-03` is specified on the command line.

```yaml $(tag) == 'package-2024-03'
input-file:
  - Microsoft.HealthcareApis/stable/2024-03-01/healthcare-apis.json
```
### Tag: package-2023-12

These settings apply only when `--tag=package-2023-12` is specified on the command line.

``` yaml $(tag) == 'package-2023-12'
input-file:
  - Microsoft.HealthcareApis/stable/2023-12-01/healthcare-apis.json
```

### Tag: package-2023-11

These settings apply only when `--tag=package-2023-11` is specified on the command line.

``` yaml $(tag) == 'package-2023-11'
input-file:
  - Microsoft.HealthcareApis/stable/2023-11-01/healthcare-apis.json
```

### Tag: package-2023-09

These settings apply only when `--tag=package-2023-09` is specified on the command line.

``` yaml $(tag) == 'package-2023-09'
input-file:
  - Microsoft.HealthcareApis/stable/2023-09-06/healthcare-apis.json
```

### Tag: package-2023-02

These settings apply only when `--tag=package-2023-02` is specified on the command line.

``` yaml $(tag) == 'package-2023-02'
input-file:
  - Microsoft.HealthcareApis/stable/2023-02-28/healthcare-apis.json
```

### Tag: package-2022-12

These settings apply only when `--tag=package-2022-12` is specified on the command line.

``` yaml $(tag) == 'package-2022-12'
input-file:
  - Microsoft.HealthcareApis/stable/2022-12-01/healthcare-apis.json
```

### Tag: package-preview-2022-10

These settings apply only when `--tag=package-preview-2022-10` is specified on the command line.

``` yaml $(tag) == 'package-preview-2022-10'
input-file:
  - Microsoft.HealthcareApis/preview/2022-10-01-preview/healthcare-apis.json
```

### Tag: package-2022-06

These settings apply only when `--tag=package-2022-06` is specified on the command line.

``` yaml $(tag) == 'package-2022-06'
input-file:
  - Microsoft.HealthcareApis/stable/2022-06-01/healthcare-apis.json
```

### Tag: package-2022-05

These settings apply only when `--tag=package-2022-05` is specified on the command line.

``` yaml $(tag) == 'package-2022-05'
input-file:
  - Microsoft.HealthcareApis/stable/2022-05-15/healthcare-apis.json
```

### Tag: package-preview-2022-01

These settings apply only when `--tag=package-preview-2022-01` is specified on the command line.

``` yaml $(tag) == 'package-preview-2022-01'
input-file:
  - Microsoft.HealthcareApis/preview/2022-01-31-preview/healthcare-apis.json
```

### Tag: package-2021-11

These settings apply only when `--tag=package-2021-11` is specified on the command line.

``` yaml $(tag) == 'package-2021-11'
input-file:
  - Microsoft.HealthcareApis/stable/2021-11-01/healthcare-apis.json
```

### Tag: package-preview-2021-06

These settings apply only when `--tag=package-preview-2021-06` is specified on the command line.

``` yaml $(tag) == 'package-preview-2021-06'
input-file:
  - Microsoft.HealthcareApis/preview/2021-06-01-preview/healthcare-apis.json
```

### Tag: package-2021-01

These settings apply only when `--tag=package-2021-01` is specified on the command line.

``` yaml $(tag) == 'package-2021-01'
input-file:
  - Microsoft.HealthcareApis/stable/2021-01-11/healthcare-apis.json
```

### Tag: package-2020-03-30

These settings apply only when `--tag=package-2020-03-30` is specified on the command line.

``` yaml $(tag) == 'package-2020-03-30'
input-file:
  - Microsoft.HealthcareApis/stable/2020-03-30/healthcare-apis.json
```

### Tag: package-2020-03

These settings apply only when `--tag=package-2020-03` is specified on the command line.

``` yaml $(tag) == 'package-2020-03'
input-file:
  - Microsoft.HealthcareApis/stable/2020-03-15/healthcare-apis.json
```

### Tag: package-2019-09

These settings apply only when `--tag=package-2019-09` is specified on the command line.

``` yaml $(tag) == 'package-2019-09'
input-file:
- Microsoft.HealthcareApis/stable/2019-09-16/healthcare-apis.json
```

### Tag: package-2018-08-preview

These settings apply only when `--tag=package-2018-08-preview` is specified on the command line.

``` yaml $(tag) == 'package-2018-08-preview'
input-file:
- Microsoft.HealthcareApis/preview/2018-08-20-preview/healthcare-apis.json
```

# Code Generation

## Swagger to SDK

This section describes what SDK should be generated by the automatic system.
This is not used by Autorest itself.

``` yaml $(swagger-to-sdk)
swagger-to-sdk:
  - repo: azure-sdk-for-net
  - repo: azure-sdk-for-python
  - repo: azure-sdk-for-java
  - repo: azure-sdk-for-go
  - repo: azure-sdk-for-js
  - repo: azure-resource-manager-schemas
  - repo: azure-powershell
```

## Python

See configuration in [readme.python.md](./readme.python.md)

## CLI

See configuration in [readme.cli.md](./readme.cli.md)

## Go

See configuration in [readme.go.md](./readme.go.md)

## Java

See configuration in [readme.java.md](./readme.java.md)
