
# Privacy Policy

**Effective date:** October 31, 2026

This Privacy Policy explains how the speak Discord application ("the Application") processes information when you use its slash commands.

## 1. Information Processed

When you use `/say`, the Application processes:

- The text you submit through the command.
- Discord interaction data required to validate and respond to your command.
- The interaction context, such as whether the command was used in a server or direct message.

## 2. How Information Is Used

The submitted text is returned as a public interaction response in the Discord channel or conversation where the command was invoked.

The Application also processes Discord's request signature to verify that incoming requests are authentic.

## 3. Storage and Retention

The current implementation does not maintain a database or intentionally store submitted message contents.

The application may write limited operational information, such as interaction context, to its runtime logs. Standard server access logs may also record request paths, timestamps and response statuses.

Discord and infrastructure providers may independently process or retain information under their own policies.

## 4. Third-Party Services

The Application relies on:

- **Discord:** Delivers interactions and displays responses. Discord's Privacy Policy applies to its processing of your data.
- **ngrok:** Provides the secure network tunnel used to connect Discord to the Application during self-hosted operation. Its own privacy policy applies to its processing.

The Application does not sell your personal information or use third-party advertising trackers.

## 5. Public Messages

Messages submitted using `/say` may be visible to other members of the Discord channel or conversation. Do not submit confidential or sensitive information.

## 6. Data Deletion

The current Application does not retain a separate database of submitted messages. Messages displayed through Discord can be managed or deleted using Discord's available features.

Operational logs, if retained by the operator or infrastructure providers, may require separate deletion requests.

## 7. Security

The Application verifies Discord interaction signatures and is designed to prevent user-submitted text from triggering automatic `@everyone` or `@here` mentions.

No internet-based service can guarantee absolute security.

## 8. Changes

This policy may be updated when the Application's functionality, infrastructure or data practices change.

## 9. Contact

For privacy questions or deletion requests concerning information retained by the Application, contact the maintainer through the repository's GitHub Issues page. Do not post sensitive personal information in a public issue.

---

This is an independently maintained application and is not affiliated with or endorsed by Discord.
