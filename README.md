# Personal Health Monitor

个人健康监测助手 / Personal health monitoring assistant

This is a personal project for reviewing sleep, recovery, activity and subjective energy in Chinese-language conversations. It is independently developed and is not affiliated with or endorsed by Oura or OpenAI.

## Current status

- The conversational component is being prepared as a private skills plugin for ChatGPT.
- Live wearable data access is **not connected**. No current ring scores or measurements are available to this project.
- Automated reports and proactive monitoring are **not enabled**.
- The project is investigating Oura's official MCP access route. A locally developed API prototype is not being deployed as a ChatGPT data source.

The conversation workflow can help organize the owner's stated wellness goals and subjective check-ins. It must explicitly distinguish those statements from connected device measurements and must not invent readings.

## Planned reporting

When an official data connection is verified, reports will identify the latest data date, missing measurements and relevant units, compare recent trends with the owner's personal baseline where enough data is available, and offer up to three general lifestyle suggestions. Synchronization delays and unsupported metrics will be stated clearly.

## Documentation

- [Privacy notice](privacy.md)
- [Terms of use](terms.md)

This public repository contains project documentation only. Health records, API credentials, access tokens and personal health reports must not be posted here or in public issues.

Contact the project owner through the GitHub account that owns this repository. Do not include private health information in public communications.
