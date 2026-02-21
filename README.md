# 🚀 A0 Token Optimizer v1.0  
---
**(Anarcho-Skills im Wandel zu Total Liberation)**

**Extreme Prompt-Kompression & Kontext-Optimierung, speziell entwickelt für Agent Zero.**

Der **A0 Token Optimizer** ist ein hochleistungsfähiger Skill für Agent Zero, der darauf ausgelegt ist, API-Kosten drastisch zu senken und das Kontextfenster (Context Window) maximal effizient zu nutzen. Inspiriert von der **LLMLingua2**-Technologie, extrahiert dieses Tool die absolute Essenz aus Texten, Dokumenten, Prompts und Bildern.

## 🏆 Die wichtigsten Errungenschaften

Dieses Projekt nutzt eine "Pure Aggressive" Architektur, um das absolute Maximum an Effizienz herauszuholen:

*   🔥 **Extreme Kompressionsrate (90%):** Der Optimizer reduziert Eingabetexte und Prompts auf nur **10% ihrer ursprünglichen Größe**. Das bedeutet 90% weniger In-Tokens und massiv reduzierte API-Kosten bei großen Kontexten.
*   🧠 **Hohe Semantische Qualität (~88-92%):** Das Tool ist darauf trainiert, für *Künstliche Intelligenz* zu schreiben, nicht für Menschen. Während der komprimierte Text für das menschliche Auge oft wie eine unleserliche "Keyword-Suppe" aussieht, behält er für LLMs nahezu seine vollständige semantische Bedeutung und Instruktionskraft.

## 🤖 Optimiert für Agent Zero

Dieser Skill wurde von Grund auf für die nahtlose Integration in **Agent Zero** entwickelt und löst typische Probleme von Standard-Kompressoren:

*   **Docker-Native & Systemd-Free:** Perfekt für die Container-Umgebung von Agent Zero. Der Daemon läuft stabil dauerhaft im Vordergrund (`--foreground`), ohne auf veraltete `systemd`-Abhängigkeiten angewiesen zu sein. Sogar Reboots überlebt er.
*   **HTTP-Daemon (Port 9199):** Anstatt bei jedem Aufruf gigantische Modelle neu in den Speicher zu laden, läuft das Modell als ressourcenschonender Hintergrund-Service. CLI-Tools und Agent Zero kommunizieren blitzschnell über eine lokale REST-API.
*   **CPU-Optimiertes PyTorch-Bundle:** Nutzt eine maßgeschneiderte, CPU-only PyTorch-Umgebung (`transformers v4.46.3`), um Kompatibilitätsprobleme in VPS Umgebung zu vermeiden.

## 📄 Erweiterte Datei- und Bildbearbeitung

Der Optimizer beschränkt sich nicht nur auf reinen Text, sondern bietet eine umfassende Pipeline für verschiedene Medien:

*   **Intelligente Dokumenten-Kompression:** Große Textdateien, Code-Dateien oder PDFs (nach Textextraktion) werden durch den integrierten `Document Optimizer` und `Chunker` in semantisch sinnvolle Blöcke unterteilt, einzeln komprimiert und wieder nahtlos zusammengefügt. So können selbst riesige Dokumente das Token-Limit nicht sprengen.
*   **Bild-Optimierung (Vision Tokens sparen):** Der integrierte `Image Optimizer` verkleinert Bilder intelligent, reduziert die Auflösung auf das für Vision-Modelle nötige Minimum und konvertiert sie in token-sparende Formate, bevor sie an multimodale LLMs gesendet werden.
*   **Automatischer File Watcher:** Ein Hintergrundprozess überwacht definierte Input-Ordner und komprimiert neu abgelegte Dokumente und Bilder vollautomatisch.

## ⚙️ Wie es funktioniert (Die "Pure Aggressive" Engine)

Anstatt auf fehleranfällige hybride Ansätze oder weiche Fallbacks zu setzen, nutzt Version 1.0 die **Pure Aggressive Engine**. 
Basierend auf dem leistungsstarken `microsoft/llmlingua-2-xlm-roberta-large-meetingbank` Modell, zwingt die Engine das System auf eine strikte Beibehaltungsrate (Retention Rate) von 10%. Unwichtige Füllwörter, Formatierungen und redundante Satzbausteine werden gnadenlos entfernt, während die Kernfakten und Handlungsanweisungen für das Ziel-LLM erhalten bleiben.

Ich freue mich sehr auf Forks mit guten Verbesserungen, lass uns AI kosteneffizienter machen um Diskriminierungsfreier zu werden. 


---
*Entwickelt als Custom Skill für Agent Zero. Inspiriert von LLMLingua2.*

---
---
OnMyWayToTotalLiberAtion
Freiheit für alle Lebewesen
TotalLiberationNOW!
