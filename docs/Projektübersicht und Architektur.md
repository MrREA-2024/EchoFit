# **Adaptive Coach \- KI-gestütztes Conversational Coaching**

## **1\. Projektübersicht**

Dieses Projekt ist die Umsetzung des Konzepts für ein KI-gestütztes, adaptives Coaching-System. Das Hauptziel ist es, die Interaktion mit dem Benutzer so natürlich und menschlich wie möglich zu gestalten, wobei die Konversation im Vordergrund steht (Chat/Sprache, nicht Formulare).

Die adaptive Logik basiert auf dem Feedback des Benutzers (im Chat erfasst) und seinen Echtzeit-Gesundheitsdaten (simuliert oder integriert).

## **2\. Technischer Stack**

* **Frontend:** React (TypeScript/JSX)  
* **Styling:** Tailwind CSS (für schnelle, responsive UI)  
* **Persistenz/Authentifizierung:** Firebase (Firestore, Auth)  
* **KI-Logik:** Google Gemini API (Natural Language Processing, Contextual Memory, TTS/STT)

## **3\. Aktueller Sprint-Fokus (Prio 1\)**

Der Fokus liegt auf der Implementierung der Kernfunktionalität **I.1. Echte Sprachinteraktion**.

* Einrichtung des Haupt-UI-Gerüsts (App-Komponente).  
* Implementierung der Logik, um Benutzer-Eingaben per Text aufzunehmen und die **Gemini API** (gemini-2.5-flash-preview-tts) für die Ausgabe in **Audio (TTS)** zu nutzen.  
* Die UI muss ein klares Mikrofon-Icon enthalten, das die Sprachinteraktion signalisiert.  
* Die App muss eine Initialisierung von Firebase (Auth und Firestore) enthalten, um Daten (Ziele, Pläne) persistent speichern zu können.