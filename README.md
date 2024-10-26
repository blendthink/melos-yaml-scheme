# Melos YAML Schema

This project provides a JSON schema for the `melos.yaml` file used in Melos. Its primary purpose is to serve as a temporary reference for creating pull requests to the Melos project.

## Purpose

1. Accurately document the structure of the `melos.yaml` file used in Melos
2. Facilitate understanding of the `melos.yaml` specification for Melos contributors
3. Serve as a reference when creating pull requests for the Melos project

## Issue Addressed

This schema addresses a specific issue in the official Melos schema configuration:

- The official schema was missing the schema definition for the `steps` field in `melos.yaml`.
- This omission caused errors when using the `steps` field in `melos.yaml`.

The schema in this project includes the correct configuration for the `steps` field, resolving this issue.
