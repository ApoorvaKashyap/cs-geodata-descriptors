# Pipeline Descriptors

This directory contains TOML descriptor files used to configure and drive the geodata processing pipeline.

A descriptor defines:
- The target geographical entity (e.g., `mws`, `district`, `tehsil`).
- The base geometry layer.
- The attribute layers (from GeoServer WFS or static files) to download and join.
- Column mapping, renaming, dropping, and scaling rules.

## Available Descriptors

- `mws.toml`: Micro-watershed (MWS) level descriptor.
- `district.toml`: District level descriptor.
- `tehsil.toml`: Tehsil level descriptor.
- `waterbodies.toml`: Waterbodies descriptor.

## Documentation

For a comprehensive guide on the descriptor format, supported fields, and how they configure the pipeline's output, please refer to the Descriptor TOML Reference page in [cs-geodata documentation](https://apoorvakashyap.github.io/cs-geodata). 

For a step-by-step trace of how a descriptor drives a full pipeline run, see the Data Flow Documentation page in [cs-geodata documentation](https://apoorvakashyap.github.io/cs-geodata).
