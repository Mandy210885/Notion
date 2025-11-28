4. App Review Submission Text

App Review – Explanation of Integration

Our web application “LUMI AGENT” automates the management and publication of music and social media videos.
The integration with TikTok uses the TikTok Content Posting API exclusively.

Flow of the integration:

The user logs in via Login with TikTok (OAuth).

After granting permission, our system receives an upload token.

The user uploads a video, or the app automatically creates a Short clip.

The video is sent to TikTok via the /post/publish/video endpoint.

The system automatically attaches title, tags, and description.

The user may optionally schedule a future post.

Scopes Used:

video.upload

video.publish

user.info.basic (optional, used only to display username/avatar)

What our app does NOT use:

No reading of inbox / messages

No access to follower lists

No automatic social graph collection

No data sharing with third parties

Storage & Privacy
Only upload tokens and the user's own uploaded videos are stored.
No user data is sold, shared, or analyzed beyond posting functionality.

This version contains initial TikTok API integration and basic upload automation.Terms of Service — LUMI AGENT

Welcome to LUMI AGENT.
By using this website and its automation features, you agree to the following terms:

Purpose
LUMI AGENT provides tools for managing, preparing and uploading media content to social platforms such as TikTok, YouTube, Instagram and Facebook.

User Responsibility
You remain fully responsible for all content you upload.
You must hold all rights to the videos, audio and images you process.

Data Access
Our system only accesses the TikTok API to publish videos on your behalf after you authorize it via the TikTok OAuth login.

Limitations
We do not guarantee uptime or availability of any third-party platforms (TikTok, Meta, Google, etc.).

Liability
We are not liable for damages caused by API limitations, misuse, or platform restrictions.

If you do not agree with these terms, please discontinue using the service.

Privacy Policy — LUMI AGENT

LUMI AGENT collects and uses personal data only for the purpose of managing and uploading video content to social platforms.

Data We Access

TikTok OAuth profile information (only what TikTok provides).

TikTok upload permission token.

Uploaded video files that you provide.

How We Use the Data

To authenticate your TikTok account.

To publish videos you selected.

To generate content metadata (titles, descriptions, thumbnails).

How We Store the Data

Tokens are stored securely on your device/server.

No data is sold or shared with third parties.

Removal of Data

You can revoke TikTok access anytime via your TikTok account settings.

You can delete stored data on your server at any time.

Legal Basis

Consent (you provide it via OAuth).

If you have questions, contact us via our website.
