# CVE-2024-26229 Beacon Object Files

Beacon Object File (BOF) implementations from [NVISO](https://www.nviso.eu) of CVE-2024-26229 for Cobalt Strike and BruteRatel.

Compile with: 

```bash
gcc -c CVE-2024-26229-bof.c -o CVE-2024-26229-bof.o
```

![Cobalt Strike](CobaltStrike.png)

![BruteRatel](BruteRatel.png)

This vulnerability was patched on April 9th, 2024. See [https://msrc.microsoft.com/update-guide/vulnerability/CVE-2024-26229](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2024-26229) for details.

The software is provided as-is. Do not expect any future updates.

## Acknowledgements

All credits for the exploit code go to the original author [varwara](https://github.com/varwara/CVE-2024-26229/).

## Authors

- **Sander Forrer** (@Cerbersec)
