# 2024-TP3 - Link and Text-Based Sources

This repository is work in progress, it is expected to be finalised by the end of business on Tuesday September 9th.

This repository contains materials that will be used during the TP3 workshop at Dyalog'24.

- `stats.dws` is a small workspace that we will convert to use text source files
- `182U64.dcfg` and `190U64.dcfg` are example configuration files that can be used as
inspiration when configuring Dyalog APL as described under [Preparation](#preparation).
- `ReadMail` is a small Cider project that can be used in one of the exercises, if
you do not have ideas of your own.

In addition to verifying the pre-requisites listed below, workshop participants can download a ZIP file containing the above as the latest [release](https://github.com/dyalog-training/2024-TP3/releases) (when it becomes available). These materials will also be circulated on a USB drive at the start of the workshop.

More time will be available for experimentation and teaching during the workshop if you have performed the steps described under [Preparation](#preparation) below.

## Pre-requisites

Required:

- Dyalog v19.0 – Unicode/Classic, 32/64-bit, any supported operating system.
  
- Link v4.0.17 – included with Dyalog v19.0

- Cider and Tatin activated (if you want to do the exercises which use Tatin packages)

- Many of the exercises will also work with Link 3.0 and Dyalog 18.0 / 18.2, but the content has only been tested with v19.0.  

  
Recommended:

- Your own small Workspace to convert to text files

- .NET 8.0 (only required for the final exercise using NuGet packages).

- Link v4.0.20 (a few fixes for bugs that will probably be encountered doing the exercises)

- Internet access (the venue has WiFi)

## Preparation

1. Install .NET 8.0 or later, if you would like to do the final exercise using NuGet packages. If you need to use .NET 6 or 7, contact the Dyalog help desk for instructions
on configuring Dyalog APL to use it.

2. Download [Link version 4.0.20](https://github.com/Dyalog/link/releases/latest) and follow the [installation instructions](https://dyalog.github.io/link/4.0/Usage/Installation/).

3. Check your APL Configuration and verify that it is enabling both the correct .NET version and the downloaded version of Link.

If you need inspiration, inspect the relevant configuration file for your APL version, one of [182U64.dcfg](https://github.com/dyalog-training/2024-TP3/blob/main/182U64.dcfg) or [190U64.dcfg](https://github.com/dyalog-training/2024-TP3/blob/main/190U64.dcfg). These two files are also included in the download zip file.

4. Activate Cider and Tatin using `]tools.activate all`. You will need to restart APL and possibly also run `]ureset` after the restart. Verify that they are active using `]cider.version` and `]tatin.version`.
