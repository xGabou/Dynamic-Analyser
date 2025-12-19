# Dynamic Analyser

## Description

Dynamic Analyser is an internal debugging tool used to inspect runtime behavior in environments where traditional IDE debugging is unavailable. It helps observe data flow, state changes, and execution paths during execution.

The tool is experimental and partially implemented.

## Purpose

The goal of Dynamic Analyser is to centralize diagnostic information that would otherwise be scattered across `Logger.log` and `console.log` calls. It provides a structured way to reason about complex runtime behavior.

## Current State

The architecture is in place, but several features are incomplete or unstable. The tool should be considered a development aid only and not relied on for production debugging.

## Usage

Dynamic Analyser is optional and must be enabled manually. It does not affect application behavior unless explicitly invoked.

## Notes

This tool is intended for exploration and understanding, not guaranteed correctness.  
If something looks wrong, it probably is.
