KarNet Solutions — COMPLETE GITHUB PACKAGE

Upload the CONTENTS of this package to the root of your GitHub repository.

Included:
- index.html — public customer website
- admin/index.html — owner login/admin dashboard
- assets/ — website images
- karnet-broadband-logo.jpg — logo
- thanks.html — submission success page
- FIRESTORE-RULES.txt — Firestore rules reference

Contact synchronization fix:
- Owner Contact Information writes to karnetSite/publicContact
- Compatibility copies are also written to karnetSite/contact and settings.contact
- Public website listens to publicContact and refreshes from Firestore

IMPORTANT:
Do not upload the outer KarNet-GITHUB-COMPLETE folder as a nested folder if you want the website at the repository root. Upload its contents directly.

PLANS MANAGEMENT UPDATE
- Owner dashboard now includes Content Management > Plans.
- Owner can add, edit, publish/unpublish, or delete broadband plans.
- Plans are stored in Firestore at karnetSite/plans and update the public website live.
- Public plan buttons open the Enquiry form with the selected plan pre-filled.
- Submitted plan enquiries are stored in karnet_enquiries and appear under Admin > Enquiries.
