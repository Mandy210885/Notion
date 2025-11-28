# Notion
Web-Tool zum Verwalten und automatischen Hochladen unserer Musik- und Social-Media-Videos auf TikTok
App Review – Beschreibung der Integration

Unsere Web-Anwendung „LUMI AGENT“ dient zur automatischen Verwaltung und Veröffentlichung von Musik- und Social-Media-Videos.
Die Integration mit TikTok erfolgt ausschließlich über den TikTok Content Posting API Workflow.
Der Nutzer meldet sich über TikTok OAuth Login an und erteilt die Berechtigung, Videos auf seinem TikTok-Profil zu veröffentlichen.

Wie wir die API verwenden:

Nutzer loggt sich über „Login with TikTok“ ein → wir erhalten ein OAuth-Token.

Nutzer lädt ein Video hoch oder unsere Software erzeugt automatisch einen Short-Clip.

Das Video wird über den TikTok Posting API Endpoint an TikTok gesendet.

Titel, Beschreibung und Hashtags werden automatisch generiert und mitgesendet.

Optional kann der Nutzer direkt im Interface eine Veröffentlichung planen.

Wir nutzen keine weiteren TikTok Scopes außer:

video.upload

video.publish

user.info.basic (optional, für Username/Avatar)

Unsere App speichert ausschließlich Upload-Tokens und hochgeladene Videodateien.
Keine Daten werden an Dritte weitergegeben.
