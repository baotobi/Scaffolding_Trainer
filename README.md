# Scaffolding in the ESL Classroom — Trainer V6

## Deploy on GitHub Pages
Extract the ZIP and upload every file to the repository root. Keep `index.html` and all JS, CSS and image assets together. Enable GitHub Pages from the selected branch/root. Trainer materials contain answers and should not be distributed to trainees.

## V6 changes
- Symbolic Home background: scaffold-supported stairs toward independent learning.
- Vertical question numbering and aligned horizontal MCQ option columns.
- A− / percentage reset / A+ control (80–160%), stored on this browser. Slides no longer shrink automatically. Larger text or smaller displays can scroll; use the fixed footer to navigate.
- Bubble matching supports pointer dragging, click-to-connect, separating pairs, and dragging joined pairs to reorder them. Trainer Key and Reset work with the existing answer fields.
- Trainer only: Example fills the current group Design Canvas step; asks before replacing nonblank fields.
- Homework is a separate six-step group canvas. Group name and lesson title are needed to generate PNG. File name: `Group Name _ Scaffolding Mind Map _ Lesson Title.png`. Homework does not overwrite group work.
- Export PDF generates and downloads A4 PDF directly, without printing. It includes slides, entered answers, visible trainer notes, coursebook pages, group canvas and homework. The PDF is rendered from canvas images (text not searchable); browser font availability affects the result. Very long mind maps are represented by the full entered text as well as the scaled map image.

## Configure links
Open `config.js` and fill in `zaloUrl`, `zaloQrImage`, `blooketCode`, and `homeworkDriveUrl` as needed. The Google Drive button opens the configured folder; the group manually uploads the downloaded PNG and teaching demo MP4. Give participants appropriate upload permission. The Homework folder URL is preconfigured in V6; verify upload permissions.

## Browser and privacy
Be Vietnam Pro is loaded from Google Fonts (Internet required); Arial is the fallback. Data stays in the browser's local storage, with V3 group data preserved where origin and browser are unchanged. Export before switching devices. Direct PDF export uses packaged local image assets and does not send entered answers to a server. Test using Chrome/Edge and the actual projector; touch interactions and live Google Drive permissions have not been verified. Coursebook pages are included as supplied; check distribution rights before publicly publishing them.

## V6 adjustments
- Approved cover artwork with fading learning supports; removed the Macmillan × LOOK 3 cover tagline.
- Left-aligned bubble text and consistent label spacing.
- Configured Homework Google Drive submission link.

## V6 updates
- Responsive mobile menu and layouts; click options without radio circles.
- Global Reset All clears workshop responses but keeps homework, configuration and font preference.
- Coursebook follows Agenda; ZPD choices reflect zone colors; new pill and speech bubbles.
- Homework groups submit a PNG mind map and a 10–15-minute teaching demo video. Include group members. Video name: `Group Name _ Teaching Demo _ Lesson Title.mp4`.

## V7
- White technique pills; colourful example speech bubbles.
- Reference tab replaces Resources.
- Trainee Check: marks submitted answers correct or incorrect without filling answers. Available for ZPD, definition, hard/soft, matching, ordering and decisions. Open-ended timing/justification is not graded. Checking data is client-side and inspectable in source.
