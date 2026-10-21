# Litter Log – Launch Plan (draft, nothing posted)

## 1. Where breeders gather (URLs checked 2026-10-20)
| Community | URL | Status |
|---|---|---|
| r/DogBreeding | https://www.reddit.com/r/DogBreeding/ | Reddit returned 403 to my fetches, so **I could not read the rules or member count**. Read the sidebar rules manually before posting. |
| Golden Retriever Dog Forums | https://www.goldenretrieverforum.com/ | Active breeding/litter threads, e.g. https://www.goldenretrieverforum.com/threads/breeding-goldens.426161/ (via search). Rules not yet read. |
| BreedingBusiness.com | https://www.breedingbusiness.com/ | Loads (200). It's a content site for kennels, not a forum, so it's an outreach/guest-post option only. |

Not verified, so skipped: other breed forums returned bot challenges (HTTP 202).

## 2. Rules first (before any post)
1. Open each community's rules/sidebar by hand. Check self-promotion limits, link rules, and flair. Reddit rules for r/DogBreeding are **unverified**. I couldn't fetch them.
2. If self-promo is banned, message the mods to ask if a feedback post is OK, or skip that community.
3. Post from Jordan's existing account only. No new accounts, no cross-posting the same text everywhere.

## 3. Value-first draft post (asking for feedback)
**Title:** Built a free, offline litter log for puppy weights. Looking for breeder feedback

> I kept seeing breeders here track daily puppy weights in spreadsheets with a tab per puppy, so I built a simple alternative and would love honest feedback before I go further.
>
> What it does: one-tap daily weights per puppy (by collar color), a growth chart with the whole litter on one graph, notes per puppy, dam heat/mating dates, and a printable puppy record you can hand to buyers.
>
> It installs from the browser, works offline in the whelping room, and keeps all data on your own phone. No account, no uploads. It's record-keeping only, not vet advice.
>
> Link: [hosted URL]
>
> Questions I'd love answers to: What do you track that's missing? Would you use the buyer printout? What does your current system look like?
>
> Free to use while I collect feedback.

## 4. Free hosting (static PWA, no paid account)
- Cloudflare Pages: https://pages.cloudflare.com/
- GitHub Pages: https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages
- Netlify (free plan): https://www.netlify.com/pricing/

Any of these serve the static files over HTTPS, which service workers need. Pick one, deploy the folder, then test install and offline on a real phone.

## 5. Pricing idea (benchmark: Breedera, $16.99/mo or $99.99/yr per its App Store listing: https://apps.apple.com/au/app/breedera-dog-breeder-app/id1430975439)
- Free: 1 active litter, full weights, notes, and chart.
- Pro: unlimited litters, buyer-record PDFs, export/backup. Test **$4.99/mo or $39/yr** to undercut Breedera and match a smaller feature set. These are hypotheses to test, not validated prices.
- Payments come later (e.g. a license key). Don't charge until about 10 breeders use it for a full litter.

## 6. Feedback collection
- Add a "Send feedback" link (mailto or free form) on the About page.
- Reply to every comment. Log the requests in a simple table (request, how many asked).
- After 2–3 weeks, ask: "Would you pay $X/yr for unlimited litters plus buyer PDFs?"
