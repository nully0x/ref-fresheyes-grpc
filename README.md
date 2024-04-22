# FRESHEYES

## Overview

This tool is designed to streamline the code review process by integrating with GitHub's API. It checks out a pull request (PR) branch, generates patches, and inserts GNU patch(1)-style diff comments, indicating where previous reviewers have left comments. This allows a user to conveniently review a pull request without distractions of the review comments, enhancing the efficiency of the review process.

It is targeted to noobs to a project who wants to understand the project code base better by reviewing past and present pul request without comment distractions.

The project consists of a Rust-based CLI tool and a library that can also be compiled to WebAssembly (WASM), allowing for flexible use in various environments.

### This a RPC backend test setup for the FRESHEYES project