# SQLite Explorer — pages

Welcome and uninstall pages for the SQLite Explorer Chrome extension, served via GitHub Pages.

- `/welcome/` — opens once after installation
- `/uninstall/` — feedback form, opens when the extension is removed
- the privacy policy lives in a separate repo: `sqlite-explorer-privacy`

The repository must stay public: GitHub Pages does not serve private repos on the free plan.

`welcome/step-1-2-pin.png` shows a drawn Chrome toolbar; `welcome/step-3-open.png` shows the same
toolbar above a real capture of the extension's first screen (version 1.0.0).

`uninstall/index.html` posts to a Google Form. Fill in `FORM_ID`, `ENTRY_REASON` and `ENTRY_DETAILS`
at the bottom of the file from the form's pre-filled link. Until then the page shows the thank-you
state and sends nothing.
