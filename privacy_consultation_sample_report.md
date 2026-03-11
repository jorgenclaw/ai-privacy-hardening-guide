# AI-Assisted Privacy Consultation

*Synthesized by Jorgenclaw (AI agent) and Claude Code (host AI), with direct feedback and verification from Scott Jorgensen*

## Sample Report: Session 1

**Client:** Sarah Martinez (Fictional Composite - Not a Real Person)
**Date:** March 15, 2026
**Session Duration:** 90 minutes
**Consultant:** Privacy Auditor + AI Assistant
**Report Generated:** March 15, 2026

**DISCLAIMER:** This is a sample report for educational purposes. "Sarah Martinez" is a fictional composite, not a real client. This report is not legal advice. Consult a qualified attorney for legal questions about privacy or surveillance laws.

---

## What We Found — The Big Picture

This report covers everything we discovered during Sarah's first privacy consultation session. We walked through threat modeling (figuring out what you're protecting and from whom), a comprehensive OSINT audit (searching publicly available information to see what anyone could find about you), a vulnerability assessment, and a step-by-step action plan.

**Key Findings:**
- **Privacy Grade:** C+ (Fair — there's meaningful exposure out there, but it's very fixable)
- **Critical Vulnerabilities:** 2 (Home address publicly indexed, children's info on social media)
- **High Priority Issues:** 5 (Data broker exposure, weak passwords, no 2FA on critical accounts)
- **Medium Priority Issues:** 8 (Social media settings, email aliases needed, device hardening)

**How Long Will This Take to Fix?** About 20–25 hours spread over 3–4 weeks. That's a realistic estimate that includes the inevitable frustrations and learning curves.

**Next Session:** March 29, 2026 (we'll check in on how the first round of fixes went)

---

## Part 1: Getting to Know Sarah's Situation

### Who We're Working With

**About Sarah:**
- Age: 34
- Location: San Diego, California
- Occupation: Marketing Manager at a mid-sized tech company
- Family: Married, two children (ages 7 and 4)
- Online Activity: Moderate social media use, professional LinkedIn presence

**What Her Digital Footprint Looked Like Before We Started:**
- Active Facebook (public profile)
- Instagram (public account, frequent posts)
- LinkedIn (professional, public)
- Twitter (abandoned around 2020, never deleted)
- Gmail (one primary email used for everything)

### Understanding What Matters Most to Sarah

We started the session by working through a threat model — basically, a structured way to figure out what Sarah actually needs to protect and who she's protecting it from. This helps us focus energy on what matters most instead of trying to do everything at once.

**What are you protecting, Sarah?**

Sarah told us her priorities are:
- Children's safety (photos, school information, location details)
- Home security (address, travel patterns)
- Financial information
- Professional reputation (nothing controversial, but she wants control over what's out there)

**Who are you worried about?**

Sarah ranked her concerns:
1. **Strangers and predators** — She's worried about her children's photos being accessible to anyone online
2. **Identity thieves** — Recent news about data breaches has her concerned
3. **Future employers** — She's planning a career move in about 2 years and wants a clean online presence
4. **Data brokers** (companies that buy and sell personal information) — She's uncomfortable with her info being sold
5. **An ex-partner** — She had a difficult breakup before her marriage and is concerned about being too easy to find

**How much risk is Sarah actually facing?**

**Our Assessment:** Medium Risk
- She's not a public figure or high-value target
- Her concerns are standard family privacy concerns — very common and very valid
- Her professional life requires some online presence (she can't disappear entirely)
- The previous relationship concern adds a moderate layer of risk

**What Sarah Wants to Accomplish:**
1. Remove her children's identifiable information from public view
2. Get her home address out of search results
3. Secure financial accounts with strong passwords and 2FA (two-factor authentication — an extra login step using your phone)
4. Clean up her social media history
5. Understand what ongoing maintenance looks like so things don't slip back

---

## Part 2: What We Found When We Searched

### How We Searched

We used an AI assistant to systematically search for Sarah's information across the internet, the same way a stranger, stalker, or identity thief could. Here's what we used:

**Tools:**
- AI assistant for systematic, thorough searching
- Google (standard + advanced search operators)
- Other search engines (Bing, DuckDuckGo) to catch things Google might not show
- Data broker sites (Spokeo, Whitepages, BeenVerified, Radaris, and others)
- Social media platforms
- Public records databases
- Reverse image search
- HaveIBeenPwned (a free service that checks if your email appeared in known data breaches)

**What We Searched For:**
```
"Sarah Martinez" + "San Diego"
"Sarah Martinez" + "[Company Name]"
"Sarah Martinez" + "Marketing"
sarah.martinez@gmail.com
[Phone Number]
[Home Address]
```

### Here's What We Found

#### CRITICAL — Fix These Right Away

**1. Sarah, Your Home Address Is Publicly Listed Online**

**Where we found it:**
- Whitepages: Full address, phone number, and age — all listed
- Spokeo: 14 matches came up (one confirmed as Sarah, with the address visible just in the preview)
- TruePeopleSearch: Address plus a list of associated people (family members named)
- Zillow: Property value estimate pulled from public records

**Why this matters:** Anyone who searches Sarah's name can find exactly where she lives. Combined with the geo-tagged photos on Instagram (more on that below), this creates a real physical security concern.

**What to do about it:**
- Submit opt-out requests to every data broker listing the address (we'll walk through this)
- Remove or make private any social media posts with location tags
- Going forward, consider using a PO Box or work address for anything public-facing

---

**2. Sarah's Children Are Identifiable on Social Media**

**Where we found it:**
- Facebook: 47 photos of her children with their names in the captions
- Instagram: 32 posts featuring the children, several showing school uniforms
- Instagram: 3 posts geo-tagged at the children's school
- Instagram: Birthday posts that reveal the children's exact birthdates
- Facebook: Comments on posts where other people mention the school by name

**Why this matters:** Right now, anyone online can see Sarah's children's faces, learn their names, figure out which school they go to, and know their birthdates. That's a lot of information in the wrong hands — whether for identity theft down the road or more immediate safety concerns.

**What to do about it:**
- Make Facebook and Instagram private immediately (this is a quick first step while we do the rest)
- Go back and remove or edit captions that reveal the children's names
- Delete the posts geo-tagged at the school
- Remove birthday and birthdate information from posts
- Check tagged photos — other people may have posted pictures of Sarah's kids too
- Long-term: Adopt a clear family social media policy going forward

---

#### HIGH PRIORITY — Tackle These Within a Week

**3. Password Security Needs Attention**

**How we assessed this:** We talked through Sarah's password habits and checked her email address on HaveIBeenPwned.

**What we found:**
- Sarah isn't using a password manager
- She admits to reusing variations of the same password across different sites
- Her email address showed up in 3 known data breaches:
  - LinkedIn breach (2021) — Email + hashed password exposed
  - Canva breach (2019) — Email + name exposed
  - Adobe breach (2013) — Email + encrypted password exposed

**Why this matters:** When passwords from one breach get reused on other sites, attackers can try them everywhere — a technique called "credential stuffing." Sarah's email account is especially vulnerable, and if someone gets into her email, they can reset passwords on everything else.

**What to do about it:**
- Install a password manager right away (we recommend Bitwarden — it's free and easy to use)
- Generate new, unique passwords for every account, starting with email, then banking, then social media
- Turn on 2FA (two-factor authentication) on all critical accounts — this means even if someone gets your password, they still can't log in without your phone
- Change the email password first — it's the single most important one

---

**4. Social Media Privacy Settings Are Wide Open**

**Facebook:**
- Profile: Public (anyone can see it)
- Friends list: Public (all 234 friends visible to anyone)
- Posts: Public (all 847 posts visible to anyone)
- Photos: Public (23 albums visible)
- Tagged photos: Visible to the public (128 photos other people tagged Sarah in)

**Instagram:**
- Account: Public (1,247 followers)
- Posts: All public (412 posts)
- Story highlights: Public (including family vacation highlights)
- Bio: Includes the children's names

**Twitter:**
- Account: Public (last post was in 2020, but the account is still live)
- 347 tweets (many from college years, some with strong political opinions)
- Old photos still visible

**LinkedIn:**
- Profile: Public (appropriate for professional networking)
- Connections: Hidden (good!)
- Activity: Public posts visible (mostly professional content — this looks fine)

**Why this matters:** Facebook and Instagram are HIGH risk right now because all family photos and information are accessible to anyone on the internet. The old Twitter account is a MEDIUM risk — those college-era tweets could become a liability during a job search. LinkedIn looks good as-is.

**What to do about it:**
- Facebook: Set everything to "Friends Only" — profile, posts, photos, and friends list
- Instagram: Switch to a Private Account
- Twitter: Review old tweets, delete anything controversial or inappropriate, or consider deleting the account entirely
- LinkedIn: No action needed — it's already in good shape 👍

---

**5. One Email Address for Everything Is Risky**

**What we found:**
- Sarah uses a single Gmail address for everything — shopping, banking, social media, and professional contacts
- That email address is visible on some social media profiles
- It appeared on 8 different data broker sites
- It's been in multiple breach databases (see the password section above)

**Why this matters:** Using one email for everything creates a single point of failure. If that email gets compromised, an attacker has the keys to the kingdom. It also means Sarah can't easily "abandon" a compromised shopping email without disrupting her banking or professional life.

**What to do about it — set up an email tier system:**
- **Tier 1 (Personal Identity):** Create a new ProtonMail account for banking, government, and medical accounts — the sensitive stuff
- **Tier 2 (Professional):** Keep the current Gmail for work-related things
- **Tier 3 (Shopping):** Use SimpleLogin aliases (disposable email addresses that forward to your real one) for retail and newsletters
- **Tier 4 (Throwaway):** Use burner email addresses for one-off signups you don't trust
- Migrate critical accounts to the Tier 1 email over time
- Set up forwarding so nothing gets missed during the transition

---

#### MEDIUM PRIORITY — Fix These Within a Month

**6. Data Brokers Have Sarah's Information Everywhere**

**Every data broker site where we found Sarah listed:**
1. Spokeo (14 matches, one confirmed)
2. Whitepages (address + phone)
3. TruePeopleSearch (address + relatives)
4. BeenVerified (detailed report available for purchase)
5. PeopleFinder (basic info visible)
6. Radaris (address history)
7. Intelius (age + location)
8. MyLife (public reputation score)
9. PeekYou (social media connections)
10. USSearch (address + phone)
11. 411.com (phone lookup)
12. TruthFinder (background check available)

**Why this matters:** Sarah's personal information is being bought and sold as a product. Some of these listings are free to view, others are behind a paywall, but all of them make it easy for someone to piece together a detailed profile. Even worse, these sites tend to re-add people after removal, so this requires ongoing attention.

**What to do about it:**
- Work through a systematic opt-out campaign for all 12 confirmed sites (plus any others we find)
- Use a tracking spreadsheet to keep track of which ones you've submitted and when
- Set a quarterly calendar reminder to re-check (they do re-add people)
- If this sounds exhausting — it is. Consider a paid removal service like DeleteMe (~$129/year) that automates the process

---

**7. Device Security Could Be Stronger**

**Sarah's Devices:**
- iPhone 13 (used for both work and personal)
- MacBook Pro (personal)
- Shared iPad (the kids use this)

**What we found:**
- iPhone: Face ID is enabled (great!), but iCloud is syncing everything (that means Apple has access to a lot of data)
- MacBook: FileVault (full-disk encryption) is not turned on — if this laptop were stolen, all the data on it would be accessible
- iPad: No Screen Time restrictions set up — the kids can access anything on it
- All devices: Automatic app updates are enabled (good)
- All devices: Location services are turned on for many apps (worth reviewing)

**Why this matters:** An unencrypted laptop is a big risk if it's ever lost or stolen — all of Sarah's data would be right there. The kids' iPad without restrictions means they could accidentally share family information or access things they shouldn't.

**What to do about it:**
- MacBook: Turn on FileVault (full-disk encryption — this protects everything if the laptop is stolen)
- iPhone: Review iCloud settings and turn off syncing for sensitive data
- iPad: Set up Screen Time with content restrictions appropriate for the kids' ages
- All devices: Go through app permissions and turn off Location, Camera, and Microphone access for apps that don't need them
- Consider installing a VPN (like Mullvad or ProtonVPN) for when you're using public WiFi

---

**8. Public Records Are Out There Too**

**What we found:**
- Property ownership: Public record in the San Diego County Assessor database
- Voter registration: Visible in the California voter file (name, address, party affiliation)
- Professional license: Listed in a California marketing association directory (name, company)
- Marriage record: Available in county clerk records (name, spouse, date)

**Why this matters:** Most of this is legally public information, so it can't be fully removed. But we can limit how easy it is for someone to find and connect all these dots.

**What to do about it:**
- Voter registration: Request confidential status (California offers this for people concerned about harassment or stalking)
- Professional directories: Request removal if your listing is optional
- Property records: These can't be removed, but opting out of data brokers that republish this information helps a lot
- Marriage records: This is public information — no action needed

---

**9–13. A Few More Things on the List**

*(These would be covered in detail in a full report:)*
- Old accounts that may still be out there (MySpace, forgotten forum registrations)
- Email forwarding rules — make sure no one has set up unauthorized forwards
- Browser privacy settings (tracking, cookies, autocomplete data)
- Cloud storage audit — what's sitting in Google Drive? Dropbox?
- Connected apps review — which apps still have access to your social media accounts?

---

## Part 3: Your Step-by-Step Action Plan

We've broken everything into three phases so it doesn't feel overwhelming. Start with the most important stuff and work your way through.

### Phase 1: The Most Important Fixes (This Week)

**Day 1 (Today) — Lock Down the Essentials (about 2 hours)**

**Set Up a Password Manager**
- [ ] Install Bitwarden (the free account is all you need)
- [ ] Create a strong master password (write it down on paper and store it somewhere safe)
- [ ] Install the browser extension so it works while you browse
- [ ] Generate a new, unique password for Gmail
- [ ] Turn on 2FA for Gmail (use an authenticator app, not SMS — it's more secure)

**Make Social Media Private Right Now**
- [ ] Facebook: Change all content to "Friends Only"
- [ ] Instagram: Switch to Private Account
- [ ] Remove the children's names from your Instagram bio
- [ ] Delete those 3 geo-tagged posts at the children's school

**Day 2–3 — Start Removing Your Info from Data Brokers (about 2 hours)**
- [ ] Submit Spokeo opt-out
- [ ] Submit Whitepages opt-out
- [ ] Submit TruePeopleSearch opt-out
- [ ] Submit BeenVerified opt-out
- [ ] Write down the submission dates in your tracking spreadsheet (you'll need to follow up)

**Day 4–5 — Fix Your Passwords (about 3 hours)**
- [ ] Generate new, unique passwords for:
  - Banking (highest priority)
  - Credit cards
  - Social media (Facebook, Instagram, LinkedIn)
  - Amazon and other shopping sites
  - Work email
- [ ] Turn on 2FA for all of the above

**Day 6–7 — Clean Up Social Media History (about 2 hours)**
- [ ] Facebook: Scroll through the last 3 years of posts, delete or make private anything you wouldn't want a stranger to see
- [ ] Instagram: Remove or edit captions that include the children's names
- [ ] Twitter: Review all tweets — delete controversial content, or just delete the whole account if it's not worth keeping
- [ ] LinkedIn: Double-check that privacy settings still look good

**Phase 1 Total Time: about 9 hours**

---

### Phase 2: Important But Less Urgent (Weeks 2–3)

**Set Up Email Compartmentalization (about 2 hours)**
- [ ] Create a ProtonMail account (free)
- [ ] Set up SimpleLogin (free tier gives you 10 aliases)
- [ ] Move banking accounts to the new ProtonMail address
- [ ] Move medical accounts to ProtonMail
- [ ] Create a shopping alias for future online purchases

**Finish the Data Broker Opt-Outs (about 3 hours)**
- [ ] Opt out of the 8 remaining confirmed brokers
- [ ] Search for any additional brokers we haven't found yet
- [ ] Set a quarterly calendar reminder to re-check (they re-add people over time)

**Tighten Up Your Devices (about 2 hours)**
- [ ] Turn on FileVault on the MacBook
- [ ] Review iPhone iCloud settings and turn off unnecessary syncing
- [ ] Set up Screen Time on the kids' iPad
- [ ] Go through app permissions on all devices
- [ ] Install a VPN (Mullvad or ProtonVPN are good options)

**Phase 2 Total Time: about 7 hours**

---

### Phase 3: The Rest of the Cleanup (Week 4 and Beyond)

**Track Down Old Accounts (about 3 hours)**
- [ ] Search for old accounts you may have forgotten about (MySpace, LiveJournal, old forums)
- [ ] Delete them or lock them down
- [ ] Check your email forwarding rules for anything unexpected
- [ ] Audit what's stored in cloud services like Google Drive or Dropbox

**Set Up Ongoing Monitoring (about 1 hour)**
- [ ] Create Google Alerts for your name (you'll get notified when new results appear)
- [ ] Register on HaveIBeenPwned for breach monitoring
- [ ] Freeze your credit with all three bureaus (Equifax, Experian, TransUnion) — this prevents anyone from opening accounts in your name
- [ ] Set calendar reminders for quarterly privacy check-ups

**Phase 3 Total Time: about 4 hours**

---

**Grand Total: 25–30 hours spread over 4–6 weeks**

**A word of encouragement, Sarah:** Most people underestimate how long the data broker opt-outs take, and almost everyone finds them more tedious than they expected. If this takes longer than planned, that's completely normal. The important thing is to start with Phase 1 — those first fixes make the biggest difference. You don't have to be perfect; you just have to be better than you were yesterday.

---

## Part 4: What This Will Cost

### The Essentials
- **Password Manager:** $10/year (Bitwarden Premium, which includes built-in 2FA support)
- **Email Aliases:** $30/year (SimpleLogin, after the free tier)
- **VPN:** $60/year (Mullvad or ProtonVPN)
- **Total for Year 1:** about $100

### Nice-to-Have Upgrades
- **ProtonMail Plus:** $48/year (adds a custom domain and more storage)
- **Data Removal Service:** $129/year (DeleteMe — automates the data broker opt-outs for you, and we honestly recommend it)
- **Credit Monitoring:** $0–20/month (you may already get this free through your credit card)

### The Honest Trade-Off Between Time and Money

**The DIY Approach:** ~$100/year, 25–30 hours of your time
- This works if you're patient, detail-oriented, and don't mind tedious tasks
- Worth noting: 25 hours at the median US wage (~$27/hr) means you're spending about $675 worth of your time
- Best for people who want to learn the process and have full control

**The Hybrid Approach:** ~$250/year, 10–12 hours of your time
- Use DeleteMe to handle the data broker opt-outs (the most mind-numbing part)
- You handle passwords, social media, and device settings yourself
- This is the best balance for most people

**The Full-Service Approach:** $500–1,000/year, 3–5 hours of your time
- A reputation management firm handles most of the work; you just approve and implement their recommendations
- Best for people with high incomes and very limited free time

**Our Recommendation for Sarah:** The Hybrid Approach is probably your best bet. Sarah, you're clearly capable of doing this work, but you told us you tend to be "lazy with tech" — and that's okay! At your income level, $250/year is very reasonable, and DeleteMe handles the most tedious part automatically (including when brokers re-add your info later, which they will). The learning experience is valuable, but the reality is that tedium causes most people to abandon the process halfway through.

**A question worth thinking about:** "Would you rather spend 25 hours doing tedious opt-outs, or pay $129/year to automate that part and spend your time on the fixes that actually need a human touch?"

---

## Part 5: What Sarah Learned This Session

### Key Concepts We Covered

**Threat Modeling**
Sarah now has a clear picture of her specific risks — not generic internet fears, but a personalized understanding of what she's protecting and from whom. This means she can make smart decisions about where to spend her energy instead of guessing.

**OSINT Awareness (How Much Strangers Can Find)**
Sarah was genuinely surprised by how much information was publicly accessible. That reaction is totally normal — and it's actually a great motivator. Now she knows what's out there, and she knows exactly how to reduce it.

**Password Security**
Sarah understands why reusing passwords is dangerous and how a single breach on one site can put all her other accounts at risk. She's committed to using a password manager going forward.

**How Data Brokers Work**
Sarah now knows that her personal information is being collected, packaged, and sold as a product by companies she's never heard of. She also understands that opting out isn't a one-time fix — it requires periodic check-ups because these companies re-add people.

### Resources We Gave Sarah

**Guides:**
- Comprehensive Privacy Hardening Guide (50 pages)
- Executive Summary (5 pages)
- This consultation report with the action plan

**Tools:**
- Bitwarden password manager
- SimpleLogin email alias service
- Data broker opt-out tracking spreadsheet
- HaveIBeenPwned breach monitoring

**Templates:**
- CCPA opt-out email template (California's privacy law gives you the right to demand companies delete your data)
- Social media privacy checklist
- Quarterly audit checklist

---

## Part 6: What Happens Next

### Session 2 (March 29, 2026)

**What we'll cover:**
1. Check that Phase 1 is done — Is the password manager set up? Are critical accounts secured?
2. Verify social media changes — Are the profiles actually private now?
3. Review data broker opt-out submissions — Have any confirmations come back yet?
4. Talk through any roadblocks Sarah hit along the way
5. Start planning Phase 2

**Sarah's homework before Session 2:**
- Complete all Phase 1 action items (don't worry if a few are still in progress — just make real progress)
- Write down any problems or questions that came up
- Bring a list of any old accounts you discovered

### Session 3 (April 12, 2026)

**What we'll cover:**
1. Verify Phase 2 completion — Is email compartmentalization set up? Are the remaining data brokers handled?
2. Check device hardening — Is FileVault on? Are the kids' iPad restrictions working?
3. Walk through the quarterly audit process so Sarah can do it on her own
4. Discuss a family privacy policy (including how to talk to the kids about this)
5. Set up a long-term maintenance plan

### Support Between Sessions

**You're not on your own, Sarah:**
- Email your consultant anytime with questions
- The AI assistant is available for specific tasks
- We'll share a tracking spreadsheet so everyone can see progress

**Long-Term Support:**
- Quarterly check-ins (30 minutes each, $50)
- Annual comprehensive re-audit (2 hours, $200)
- Emergency support if a breach or doxxing incident occurs

---

## Part 7: What Sarah Had to Say

### Post-Session Feedback

**How do you feel about your privacy now?**
> "Honestly, I'm horrified by how much information is out there about me and my kids. But I also feel empowered because I now know exactly what to do about it. I didn't realize my home address was on so many sites — that's terrifying."

**Was the AI-assisted audit helpful?**
> "Absolutely. There's no way I could have found all of this myself. Having the AI systematically search for everything saved hours, maybe days. And the consultant helped me interpret what it meant."

**How confident are you about completing the action plan?**
> "Pretty confident. The Phase 1 stuff seems doable this week. The data broker opt-outs are tedious but straightforward. I'm most worried about maintaining this long-term — I tend to let things slide."

**What surprised you the most?**
> "Two things: 1) How many data brokers exist — I'd never heard of most of them. 2) How much of my kids' information I put out there without thinking. I feel guilty about that."

**Would you recommend this to other people?**
> "Definitely. Especially parents. I wish I'd done this years ago before posting so much about my kids."

---

## Part 8: Notes for the Consultant

### What's Working in Sarah's Favor
- She's motivated and was engaged the entire session
- She picks up technical concepts quickly
- She took detailed notes throughout (always a great sign)
- She's realistic about how much time this will take

### Where She Might Need Extra Support
- She describes herself as "lazy with tech" in the past — follow-through could be a challenge
- She felt a bit overwhelmed by the amount of work ahead
- Long-term maintenance is her biggest concern
- Her husband wasn't at the session — it may be worth bringing him into Session 2 or 3 to get buy-in on a family privacy policy

### Realistic Predictions
- **Phase 1:** 90% likely to complete on time (the children's safety concern is a powerful motivator)
- **Phase 2:** 70% likely to complete (enthusiasm tends to dip once the most urgent threats are handled)
- **Phase 3:** 50% likely to complete (lower-urgency items often get pushed to "someday")
- **Long-term maintenance:** 40% likely without ongoing support (she told us herself that she tends to let things slide)

### Consultant To-Do's
- Send a mid-week check-in email to see how Phase 1 is going
- Offer extra help with the data broker opt-outs — they're the most tedious part and the most likely to cause someone to give up
- Keep reinforcing the importance of quarterly audits (this is Sarah's weak spot)
- Consider inviting her spouse to Session 2 or 3 — family-wide buy-in makes everything stick better

---

## Appendix A: Complete Findings List

*(A full report would include an exhaustive list of every URL, data broker listing, social media post, and more. Here's an abbreviated version.)*

**Data Brokers (12 confirmed, 5 suspected):**
1. Spokeo - spokeo.com/Sarah-Martinez/CA/San-Diego/[ID] - Address visible
2. Whitepages - whitepages.com/name/Sarah-Martinez/San-Diego-CA/[ID] - Address + Phone
3. TruePeopleSearch - truepeoplesearch.com/results?name=Sarah%20Martinez&citystatezip=San%20Diego%2C%20CA - Address + Relatives
... (full list)

**Social Media Posts Flagged for Review or Deletion:**
- Facebook Post (2024-08-15): Photo of son in school uniform with caption "First day at [School Name]!"
- Instagram Post (2023-12-25): Christmas photo geo-tagged at home
- Instagram Story Highlight (2023-07): "Emma's 4th Birthday" with birthdate visible
... (full list)

**Breached Databases:**
- LinkedIn (2021): Email + hashed password
- Canva (2019): Email + name
- Adobe (2013): Email + encrypted password

---

## Appendix B: Action Tracking Spreadsheet

*(Provided separately — the spreadsheet includes columns for:)*
- Task Description
- Priority (Critical / High / Medium / Low)
- Status (Not Started / In Progress / Completed)
- Date Assigned
- Target Completion Date
- Actual Completion Date
- Notes

---

## Wrapping Up

Sarah came into this consultation with a general sense of unease about her family's privacy and left with a clear understanding of exactly what's exposed and a concrete plan to fix it. The AI-assisted OSINT audit turned up more than she expected — particularly around her children's information and her home address being publicly listed across a dozen data broker sites.

**Why we think this will work for Sarah:**
1. The threat modeling session connected every action item to something Sarah actually cares about — especially her kids' safety
2. The AI-powered audit was thorough and fast (doing this manually would have taken days)
3. Breaking everything into phases prevents that "where do I even start?" feeling
4. The education component means Sarah won't just fix things once — she'll understand how to keep them fixed

**What to expect in the coming months:**
- Within 1 week: The critical vulnerabilities should be addressed — children's info made private, home address opt-outs submitted
- Within 1 month: High priority issues resolved — passwords secured, social media locked down
- Within 3 months: Medium priority items completed, ongoing maintenance habits established
- Privacy grade improvement: C+ to B+ (projected)

**Next Session:** March 29, 2026 — We'll verify Phase 1 is done and start planning Phase 2.

---

*Report prepared by [Consultant Name] with AI assistance*
*Confidential — For Client Use Only*
*Version 1.0 — March 15, 2026*
