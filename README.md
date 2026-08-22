# Meercata Documentation

Public operator documentation for the Meercata project.

## Available manuals

- [English - Meercata v1.00 Windows Operations Manual (PDF)](manuals/windows/Meercata_Windows_Operations_Manual_v1.00_English.pdf)
- [Bahasa Melayu - Manual Operasi Meercata v1.00 untuk Windows (PDF)](manuals/windows/Meercata_Windows_Operations_Manual_v1.00.pdf)

The Windows v1.00 source repository is maintained separately and is not included here. The public manual contains operating instructions, troubleshooting guidance, command references, maintenance procedures, and an operator cheat sheet.

## Windows v1.00 prerequisites

Install the components in this order before starting Meercata:

1. Python 3.10 or newer, available in `PATH`.
2. Npcap with its driver running.
3. Suricata for Windows with `suricata.exe`, a readable `suricata.yaml`, valid rules, and EVE JSON output enabled.
4. Meercata v1.00, followed by **Check requirements** from an elevated launch.

Passive IDS requires Suricata and Npcap. Windows inline IPS additionally requires a Suricata build with WinDivert support. Meercata does not install these dependencies automatically.

## Public-release sanitization

The published PDF uses RFC 5737 documentation addresses from `203.0.113.0/24` in examples. Local usernames, credentials, tokens, raw logs, alert evidence, and private configuration files are not included.

## Platforms

- Meercata v1.00: Windows-based OS
- Meercata Bash: Linux-based OS, published in its own repository

## License

No licence file is included yet. Public visibility does not by itself grant reuse, modification, or redistribution rights.
