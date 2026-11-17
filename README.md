# ATW Source v106 — Refined

## Open or publish

Open ATW_Source_v106_ATLAS_FIX.html for the standalone application. For GitHub Pages, extract ATW_Source_v106_GitHub_Package.zip and publish its contents, keeping index.html, assets/, vendor/ and .nojekyll together. The archive root is the site root. This release has not been pushed or published automatically.

## Registration

The registration form includes the two original supplied Word templates: Declaration Form - Template - Final_Rev Internal.docx and Surat Pernyataan Terkait Pajak - ATW Group.docx. Their bytes are unchanged, embedded for standalone downloads, and also available under assets/vendor-registration/. Completed forms can be uploaded as PDFs in their matching signed-document fields.

Bank Account Confirmation is required. NPWP document, Relevant Certifications, Product Catalogues, ISO Certificates and Other Supporting Documents are optional. Signed Declaration Form and Signed Tax Statement are optional. Legal identity fields and other applicable legal documents still follow the selected country, company form and business role. A submitted account remains provisional (-P); ATW approval is needed for Active status.

## Integrated workspaces

Procurement Budget Assistant is the single budget module for Internal CAPEX, Internal OPEX and project budgets (COGS). Project scope retains engineering work, goods/services, direct/indirect costs, lead times, strategic procurement flags and commercial ranges. Missing rates prevent a complete cost/profit claim. Internal budgets do not display project profit or margin.

Personal Procurement accounts see request settings. Submission through procurement@atwsolar.com requires the verified division access flow and a registered member PIC. Employee request forms remain available according to their division access. Procurement configuration and creation forms start collapsed behind explicit controls. Mailing center consolidates drafts, reminders and workflow correspondence, with the current registered member signature. A draft, queue entry or unverified legacy Sent status is not treated as confirmed delivery.

Vendor RFQ forms compare the new price against that vendor's own previous eligible submission. Comparison uses exact item, entity, currency, UOM and discount. Incompatible or equivalent items do not receive a misleading percentage. Rejected submissions do not create a new price-history entry.

ATLAS offers A for the suggested action, B for alternatives and C for a visible free-question conversation. The character has 29 recorded prompts and topic summaries in each of English, Indonesian and Mandarin. Dynamic answer speech uses a device-local voice for the selected language; if none is available, the written answer remains available without an unrelated audio fallback. Audio follows the selected language after interaction, with mute/replay and mouth animation synchronized to playback. Specific findings and amounts can be spoken only by the matching device-local voice; the bundled recordings do not synthesize arbitrary private answers. Both the standalone HTML and the hosted package contain the audio. Binary data is loaded per language on first use. No runtime outside speech provider is enabled. After 45 seconds of inactivity, ATLAS enters quiet standby and wakes on interaction. See RELEASE_NOTES.md for audio provenance and limits.

Outstanding lists are scoped to actionable follow-ups. PR tracking remains available before a PO exists. PO approval takes place in ATW Source; a NetSuite migration queue is separate from approval and completion.

## Operational boundary and validation

This is a static frontend package. Browser storage, account checks and recorded workflow approvals do not constitute shared production authentication, a company database or server-side authorization. A company server, server-side access checks, shared persistence, document storage, notifications and integration adapters must be connected and verified before official multi-user operation. No API key, external AI account or live backend was created.

VALIDATION.json records 335 behavior/integrity checks and 84 menu openings, with zero detected errors in those scenarios. Tests cover the application code in a DOM harness, the actual recorded media files and isolated workflow fixtures. They are evidence for the tested paths, not a guarantee that every device/input is error-free. Browser reproduction was blocked by the file-URL policy and a localhost-preview connection timeout; native interaction, a physical phone and native file-mode OCR were not verified. Playback and voice-state tests use simulated browser audio events.

The original private quotation and its extracted content are excluded. Only the two registration templates supplied for applicants are included. ASSET_MANIFEST.json records file hashes; the adjacent SHA256 file covers the HTML and ZIP.
