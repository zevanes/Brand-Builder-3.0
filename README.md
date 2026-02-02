Brand Builder OS 3.0 🚀

Brand Builder OS ist ein professionelles, browserbasiertes Werkzeug für Markenstrategen, Agenturen und Gründer. Es ermöglicht die Entwicklung, Visualisierung und Verwaltung von Markenidentitäten in einer einzigen, intuitiven Oberfläche.

Die Anwendung ist als Single-File-Application konzipiert – kein Build-Prozess, kein Server, einfach reines HTML, CSS und JavaScript (React).

(Hier können Sie später einen echten Screenshot Ihrer App einfügen)

✨ Hauptfunktionen

🗂️ Multi-Projekt-Management

Verwalten Sie mehrere Kunden oder Marken gleichzeitig.

Alle Daten werden lokal im Browser (localStorage) gespeichert – nichts verlässt Ihren Rechner (außer AI-Anfragen).

Onboarding-Flow für neue Projekte mit Metadaten (Branche, Lead, Datum).

🧠 KI-Integration (Google Gemini)

Das OS nutzt die Google Gemini API für strategische Unterstützung in Echtzeit:

DNA Generator: Vorschläge für Markenwerte und Kernelemente.

Strategie-Analyse: Interpretiert visuelle Bewegungen in der Positionierungs-Matrix.

Persona Generator: Erstellt detaillierte Zielgruppenprofile.

Naming & Messaging: Kreiert Namen und Elevator Pitches basierend auf der Markenidentität.

🛠️ Die Module

Business Modell: Lean Canvas Ansatz zur Definition von Problem, Lösung, USP und Revenue.

Brand DNA: Interaktives Zwiebelschalen-Modell (Kern, Werte, Beweise) mit Drag & Drop.

Positionierung: Matrix-Tool mit frei beweglichen Logos und Strategie-Pfeilen zur Visualisierung von Marktbewegungen.

Markenarchitektur: Baumstruktur-Visualisierung für Masterbrands, Subbrands und Produkte.

Zielgruppen: KI-gestützte Erstellung von Buyer Personas.

Naming: Kreativ-Tool für Namensfindung mit verschiedenen Routen.

Markenbotschaft: Tonalitäts-Regler und Pitch-Generator.

Brand Book: Automatische Zusammenfassung aller Ergebnisse als One-Pager.

🖨️ Export & Präsentation

PDF-Export: Saubere Druckfunktion für das Brand Book und einzelne Module.

Fullscreen-Modus: Für ablenkungsfreie Präsentationen direkt im Browser.

🚀 Installation & Nutzung

Da es sich um eine Single-File-App handelt, ist keine Installation von Node.js oder npm notwendig.

Laden Sie die Datei game.html (oder index.html) herunter.

Öffnen Sie die Datei in einem modernen Browser (Chrome, Firefox, Edge, Safari).

Fertig!

Konfiguration (API Key)

Damit die KI-Funktionen (Gemini) funktionieren, müssen Sie Ihren Google API Key im Code hinterlegen:

Öffnen Sie die HTML-Datei in einem Texteditor (VS Code, Notepad++, etc.).

Suchen Sie nach der Zeile:

const apiKey = "";


Fügen Sie Ihren API Key zwischen den Anführungszeichen ein:

const apiKey = "IHR_GOOGLE_GEMINI_API_KEY";


Speichern Sie die Datei.

Hinweis: Geben Sie diese Datei mit Ihrem API-Key nicht öffentlich weiter, wenn Sie GitHub nutzen. Verwenden Sie für öffentliche Repositories Umgebungsvariablen oder fordern Sie den Nutzer auf, seinen eigenen Key einzutragen.

💻 Tech Stack

Core: HTML5, React 18 (via CDN), Babel (Standalone)

Styling: Tailwind CSS (via CDN)

Icons: SVG (Inline, Zero-Dependency)

Markdown: Marked.js

AI: Google Gemini API (gemini-2.5-flash-preview)

Persistence: LocalStorage API

🤝 Lizenz

Dieses Projekt ist unter der MIT Lizenz veröffentlicht. Fühlen Sie sich frei, es zu nutzen, zu verändern und zu erweitern.

Entwickelt mit Leidenschaft für Markenstrategie.
