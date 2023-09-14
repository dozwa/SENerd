# README: SE-Nerd QA App
Nerdy chatbot for Systems Engineering Questions

## Beschreibung

Die "SE-Nerd QA App" ist eine Webanwendung, die auf der Grundlage des LangChain-Frameworks entwickelt wurde, um Fragen in Bezug auf bereitgestellte Dokumente zu beantworten. Benutzer können eine Frage in das bereitgestellte Textfeld eingeben und aus verschiedenen Kettenoptionen wählen, um relevante Textabschnitte aus den Dokumenten zu extrahieren, die die Frage beantworten.

## Installation und Einrichtung

1. Klone das Repository:

   ```bash
   git clone [Link-zum-Repository]
   cd [Repo-Name]
   ```

2. Installiere die erforderlichen Pakete:

   ```bash
   pip install langchain openai chromadb tiktoken pypdf panel
   ```

3. Setze deinen OpenAI API-Schlüssel als Umgebungsvariable:

   ```bash
   export OPENAI_API_KEY="dein-api-schlüssel"
   ```

## Verwendung

Starte die App:

```bash
python app_name.py
```

Folge den Anweisungen in der App:

1. Stelle deine Frage.
2. Wähle die gewünschten Parameter.
3. Klicke auf "Run!".

Die Antwort wird im Ausgabefeld angezeigt.

## Änderungen gegenüber dem Original

Die "SE-Nerd QA App" wurde auf der Grundlage des [Original-Notebooks](https://github.com/sophiamyang/tutorials-LangChain/blob/main/LangChain_QA_Panel_App.ipynb) von Sophia Yang erstellt. Während die Hauptfunktionalität beibehalten wurde, wurden die folgenden Erweiterungen und Modifikationen vorgenommen:

- Entfernung der Notwendigkeit, eine PDF-Datei und den OpenAI-API-Schlüssel hochzuladen. Stattdessen wird der API-Schlüssel als Umgebungsvariable verwendet.
- Anbindung an eine lokale, bereits mit Daten befüllte Datenbank (ChromaDB)
- Anpassungen am Design und Layout, um die Benutzerfreundlichkeit zu erhöhen.
- Einige erweiterte Einstellungen wurden hinzugefügt, um dem Benutzer mehr Kontrolle über die Funktionsweise der App zu geben.

## Credits

Ein besonderer Dank geht an [Sophia Yang](https://github.com/sophiamyang/tutorials-LangChain/commits?author=sophiamyang) für die Erstellung des ursprünglichen Notebooks, auf dem diese App basiert. Ihr Beitrag zur Gemeinschaft ist unschätzbar und hat die Entwicklung dieser App erheblich erleichtert.

## Lizenz

Bitte beachten Sie die beigefügte Lizenzdatei für Informationen über die Verwendung und Verteilung dieses Codes.

---

Es ist immer wichtig, sicherzustellen, dass alle notwendigen Abhängigkeiten und Anweisungen korrekt und vollständig sind, bevor Sie sie an andere weitergeben. Ich empfehle, die Anweisungen selbst zu überprüfen und gegebenenfalls anzupassen.
