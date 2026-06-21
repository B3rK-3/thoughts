# How Google Drive Works

Google Drive is a cloud storage and synchronization service by Google. Files are stored on Google's servers and synced across devices via the user's Google account.

## Core Mechanics

- **Storage**: Files live in Google's data centers, replicated across multiple locations for durability. Each account gets 15 GB free (shared with Gmail and Google Photos).
- **Sync**: The Drive desktop app watches a local folder for changes and syncs them to the cloud. Conflicts are resolved by keeping both versions with "conflicted copy" suffixes.
- **Sharing**: Files can be shared via link with view/comment/edit permissions. Owners can revoke access anytime.
- **Collaboration**: Google Docs, Sheets, and Slides are real-time collaborative — multiple users edit simultaneously, with cursor presence and version history.
- **Versioning**: Drive keeps revision history for 30 days (or longer for Google Workspace accounts), so you can restore previous versions.
- **Search**: Google's OCR indexes text in images and PDFs. Search queries scan filenames, content, and metadata.

Drive uses OAuth 2.0 for authentication and exposes a REST API for programmatic access.