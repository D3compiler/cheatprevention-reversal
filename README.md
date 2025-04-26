# Reversal

This repository contains dumped encrypted requests from cheatprevention.com.

This project is a reversal of the API and does not introduce novel techniques or findings. The analysis reveals that many of the detection methods appear to be derived from echo.ac.

Some detections are noted as potentially ineffective or improperly implemented, with specific examples like the exora.cc ones being highlighted as non-functional.

A webhook used for sending screenshots to a Discord server was identified and subsequently disabled via a DELETE request (to protect users privacy), as permitted by Discord's API.

In addition to collecting system information, the API also downloads software from their CDN, including tools such as `drvscan` ([https://github.com/ekknod/drvscan](https://github.com/ekknod/drvscan)) and `ExtractUsnJrnl` ([https://github.com/jschicht/ExtractUsnJrnl](https://github.com/jschicht/ExtractUsnJrnl)) and few others (nothing useful).

While system information is collected by the API, the types of data gathered are largely consistent with what is collected by echo.ac and do not present significant differences in terms of invasiveness. The overall assessment is that their APIs demonstrate similar limitations and issues as echo.ac.

# Advisory

Based on the current reversal and analysis, the effectiveness of this tool appears to be significantly limited. Many of the detection methods seem to be inherited from or similar to those used by echo.ac, which are known to have shortcomings.

At present, the tool is considered to be largely ineffective due to the issues identified in its detection mechanisms, including some that are non-functional.

It is anticipated that the tool may undergo improvements in the future. However, based on its current state, purchasing this tool is not recommended due to its demonstrable limitations and poor performance.

# Sources

*   https://cdn.cheatprevention.com/v1/assets/files/rtcore.sys
*   https://cdn.cheatprevention.com/v1/assets/files/Prevention4.exe
*   https://cdn.cheatprevention.com/v1/assets/files/ExtractUsnJrnl64.exe
*   https://cdn.cheatprevention.com/v1/assets/files/xxstrings64.exe

and some others...
