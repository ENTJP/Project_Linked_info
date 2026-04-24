# Synapse — Privacy Policy

**Effective date:** April 24, 2026
**Contact:** myjoon94@gmail.com

Synapse is a personal knowledge graph application that runs entirely on your
Mac. This policy describes what data the app handles, where it is stored,
and what is (and is not) transmitted off your device.

---

## 1. Data We Collect

**None.**

Synapse does not collect, transmit, or store any personal information on
remote servers. We do not operate any backend service that receives your
data. We do not use analytics, crash reporting, advertising SDKs, or any
third-party tracking.

---

## 2. Data Stored On Your Device

All content you create in Synapse is stored **locally on your Mac**:

- **Knowledge graph data** (nodes, text, rich content, images, workspaces,
  semantic relationships, and computed embedding vectors) is stored in the
  app's local IndexedDB database inside the macOS application container.
- **User preferences** (color theme, hierarchy source, etc.) are stored in
  the same local database.
- **Exported `.linked` files** are written only to locations you explicitly
  choose via the system Save dialog.

This data never leaves your device unless you deliberately export it.

---

## 3. Network Access

Synapse makes network requests in **only one** circumstance:

### First-launch AI model download

On first launch, Synapse downloads an on-device machine-learning model
(`Xenova/paraphrase-multilingual-MiniLM-L12-v2`, approximately 120 MB) from
the Hugging Face Hub CDN (`https://huggingface.co`). The model is cached
locally and reused on subsequent launches; no further network requests are
made.

The model is used **entirely on your device** to compute semantic embedding
vectors for the text you write. No text, embeddings, or any other user data
is ever sent to Hugging Face or any other server.

Hugging Face's own privacy practices for the CDN request (which sees only a
model file download) are described at
<https://huggingface.co/privacy>.

### No other network calls

Synapse does not contact any other server. There is no account system, no
cloud sync, no telemetry, no update server, and no advertising network.

---

## 4. Children's Privacy

Synapse is not directed to children under 13. Because the app collects no
personal information at all, it does not knowingly collect data from anyone,
including children.

---

## 5. Your Rights

Because Synapse stores data only on your device:

- **Access / export:** Use "Save As" to export your entire graph to a
  `.linked` file at any time.
- **Delete:** Use "Restart Synapse" inside the app to clear all local data,
  or uninstall the app (macOS will remove the local container).

No server-side request or data request form is necessary — there is no
server-side data.

---

## 6. Changes to This Policy

If this policy changes in the future, the updated version will be published
at the URL you received with this app and the effective date above will be
updated.

---

## 7. Contact

Questions about this policy: **myjoon94@gmail.com**
