# Civil Society Wetlands Coalition — Website v1

Static, mobile-responsive website with News & Voices, Our Network, Resources, Media Centre, map preview and member submission draft workflow.

## Preview
Open `index.html` in a browser. For a local development server, run `python -m http.server 8000` in this folder and open http://localhost:8000.

## Deploy
Upload all files in this folder to a GitHub repository and deploy as a static site on Vercel (framework preset: Other, output directory: root). No build command required. Register and connect a domain when ready.

## Important before launch
1. Connect the member form to an approved Google Form or other secure form backend. The current form **only downloads a text draft** and does not submit data.
2. Replace the Google Maps **Zimbabwe geographic placeholder** with the coalition's own published Google My Maps embed link. No wetland pins or threat locations are currently asserted.
3. Upload and link publication PDFs once publication permission and image rights are confirmed. Covers are supplied source materials; the site does not link to local PDFs.
4. Confirm all coalition member organisations, names, contact addresses and permission to list.
5. Replace the hero stock landscape photo with licensed Zimbabwe wetland imagery. The current remote photo requires internet connectivity and should not be interpreted as depicting a particular site.
6. Add a designated coalition media contact and privacy notice before accepting live submissions.
7. News cards are editorial summaries of the two provided 2026 newsletters, not full republications or independent verification.

## Source material
- Wetland Voices, August 2026, Issue 1
- Civil Wetlands Newsletter, June/July 2026, Issue 1

## Wetland action decision tree
`action-guide.html` and `action-guide.js` provide a branching public action guide and downloadable case-report form. The form is NOT connected to a recipient. Before publication configure a coalition intake channel, consent/privacy terms, safeguarding and triage protocol.


## v3 — Google Form integration

The action guide and homepage now link directly to the coalition’s supplied public Google Form for wetland case reports. The former local case-report download form was removed from the action guide. The separate editorial/story submission draft on the homepage is unchanged and still does not send online. Test the Google Form response collection, notifications and permissions before launch.
