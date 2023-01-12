My more interesting Huginn scenarios.

# Scenarios

# release-notifications.json

Create an email digest with daily updates on software releases.

### Credentials
Requires the following credentials:

* mail_bot_username - The username for the ImapFolderAgent "Mail Bot Firehose"
* mail_bot_password - The password for the ImapFolderAgent "Mail Bot Firehose"

## security-issues.json
Detects security issues with the given software and emails a report every 2 hours if any are detected.

### Searches
- Email
- ExploitDB (via RSS)
- Github commits (via RSS)
- Github notifications
- RSS feeds (TincVPN)
- Webpages (NGINX security advisories)

### Credentials
Requires the following credentials:

* mail_bot_username - The username for the ImapFolderAgent "Mail Bot Firehose"
* mail_bot_password - The password for the ImapFolderAgent "Mail Bot Firehose"
* github_access_token - A Github access token for the GithubNotificationsAgent "Github Notifications"
