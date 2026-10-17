# St. Gabriel Technical School
## Project handover for the school owner

**Date:** 17 October 2026  
**Prepared for:** The owner of St. Gabriel Technical and Vocational Training Institute, Enugu  
**What this is:** A plain-language map of everything digital we built for the school, who can touch it, and how you take ownership.

Keep the last page (passwords) off email if you can. Fill it in by hand when you sit down together, then store it somewhere safe.

---

## 1. What you now own

You are being given control of the school’s online presence. In everyday terms, that is:

| What | In plain English | Where it lives |
| --- | --- | --- |
| The public website | The school’s shop window on the internet | [www.stgabrieltech.com](https://www.stgabrieltech.com) |
| The learning platform (LMS) | An online classroom we started building. It is a working preview, not a full student system yet | [st-gabriels-technical-schools-lms.vercel.app](https://st-gabriels-technical-schools-lms.vercel.app) |
| The domain name | The web address `stgabrieltech.com` | Pointed at Vercel (the company that publishes the website) |
| School email | Inboxes such as `info@stgabrieltech.com` | Hostinger |
| The code cupboard | The saved, official copy of both projects | GitHub organisation **St Gabriel Technical School** |
| The school GitHub login | The account that owns that cupboard | Username **SG-Tech25**, opened with the school email we are handing you |

You also keep two people who already work on the projects:

- **Lead developer** — GitHub username `ZZYXX-CC`. This person reviews and publishes changes.
- **Junior developer** — Stanley, GitHub username `StanleyDcoder`. This person can propose changes. They cannot publish to the live site on their own.

---

## 2. Your first 30 minutes (do this in order)

Sit at a computer with the school email open.

1. **Open the school email we are giving you.** This inbox is the key. It is also how GitHub will send you “is this you?” emails.
2. **Go to** [github.com/login](https://github.com/login).
3. **Sign in** with the school GitHub username **SG-Tech25** and the password we give you on the last page.
4. **Change that password immediately.** Click your profile picture (top right) → **Settings** → **Password and authentication**.
5. **Turn on two-step verification** on the same page (GitHub will ask for a code from your phone). Do this so a stolen password is not enough to take the school’s sites.
6. **Open the school’s GitHub home:**  
   [https://github.com/St-Gabriel-Technical-School](https://github.com/St-Gabriel-Technical-School)  
   You should see **two projects** listed.
7. **Open the live website** in another tab: [https://www.stgabrieltech.com](https://www.stgabrieltech.com)  
   Confirm it loads and shows the school name.
8. **Bookmark both links** (GitHub home and the live website) on this computer.

If step 3 fails, do not keep guessing the password. Use **Forgot password** on GitHub — the reset link will arrive in the school email.

---

## 3. The two projects, simply explained

Think of GitHub as a locked filing cabinet. Each **project** (GitHub calls this a *repository*) is one folder in that cabinet.

### Project A — School website

- **What the public sees:** [https://www.stgabrieltech.com](https://www.stgabrieltech.com)
- **Spare copy of the same site:** [https://st-gabriel-technical-college-websit.vercel.app](https://st-gabriel-technical-college-websit.vercel.app)
- **Code cupboard:** [https://github.com/St-Gabriel-Technical-School/st-gabriel-technical-college-website](https://github.com/St-Gabriel-Technical-School/st-gabriel-technical-college-website)
- **What it is:** The public college website. Home, programmes, admissions, news, contact, and a waitlist while admissions are closed.
- **What already works for visitors:**
  - The pages themselves (the site is live).
  - A waitlist form designed to email **info@stgabrieltech.com** and **waitlist@stgabrieltech.com**.
- **What still needs your attention:**
  - Some contact details on the site still look like placeholders (for example dummy phone numbers on the contact page). Get a developer to replace those with the school’s real numbers.
  - The admissions application form is **not fully wired** to the school inbox yet. In the code it still points at `admissions@stgabriel.edu`, which is not your domain. Until that is fixed, do not rely on that form.
  - The waitlist emails only send if the publishing account (Vercel) still has the email-sending key set up. After handover, the lead developer should confirm a test waitlist entry arrives in the school inbox.

### Project B — Learning platform (LMS) and mobile draft

- **What the public can open today:** [https://st-gabriels-technical-schools-lms.vercel.app](https://st-gabriels-technical-schools-lms.vercel.app)
- **Code cupboard:** [https://github.com/St-Gabriel-Technical-School/St-Gabriels-Technical-Schools-LMS](https://github.com/St-Gabriel-Technical-School/St-Gabriels-Technical-Schools-LMS)
- **What it is:** “SGT Learn” — an online place for courses, lessons, and (later) student logins.
- **Honest status:** This is a **working preview with sample / demo content**. It is not yet a live school with real student accounts, real payments, or real course videos. The plan on file is to use:
  - student login (planned with a service called Supabase),
  - videos hosted on YouTube,
  - payments later (Paystack / Flutterwave were named in the plan).
- **Also inside this same cupboard:** a mobile-app draft named **SGT Learn** (folder `main/EducatePro`). It is a starting design for phones. It is **not** listed on the Apple App Store or Google Play as part of this handover.

If someone asks “can students log in and take paid courses today?”, the accurate answer is **not yet**. The public website is live. The learning platform is a preview.

---

## 4. Your accounts — the keys to the kingdom

These are the doors. Whoever has the email and passwords can change or take down the school’s sites. Change every password on handover day.

### A. School email (you are receiving this inbox)

| | |
| --- | --- |
| What it is | The school’s official inbox |
| Address on the website | **info@stgabrieltech.com** |
| Where the mail is hosted | **Hostinger** (this is confirmed by the internet records for the domain) |
| Other school addresses already used in the project | `waitlist@stgabrieltech.com`, `no-reply@stgabrieltech.com`, plus contact-page addresses `admissions@`, `hello@`, and `careers@` @stgabrieltech.com |
| Log in | Hostinger / hPanel — ask the person handing over to log in with you once and write the Hostinger username on the last page |

GitHub’s organisation billing email is **info@stgabrieltech.com**. The school GitHub account **SG-Tech25** is the account that owns the organisation. The email we are handing you is the one that can recover that GitHub account if you forget the password.

### B. GitHub (the code cupboard)

| | |
| --- | --- |
| Website | [https://github.com](https://github.com) |
| School login | **SG-Tech25** |
| Organisation (the school’s cabinet) | [https://github.com/St-Gabriel-Technical-School](https://github.com/St-Gabriel-Technical-School) |
| Your role there | **Owner** — you can add/remove people and see everything |
| Cost today | GitHub Free (no paid GitHub plan is required for what is set up) |

### C. Vercel (puts the website on the internet)

The live site and the learning preview are published by **Vercel**. The domain’s name servers are:

- `ns1.vercel-dns.com`
- `ns2.vercel-dns.com`

That means: **whoever is logged into the Vercel account can change or unpublish the live website.**

We could not see that Vercel login from here. **Do not leave today without:**

- the Vercel login email,
- the Vercel password (or a transfer of the projects into a Vercel account that uses the school email),
- a quick look in Vercel that both projects are listed.

Log in at [https://vercel.com/login](https://vercel.com/login).

### D. Email-sending for the waitlist (Resend)

The website waitlist is built to send mail through a service called **Resend**, from `no-reply@stgabrieltech.com` to `info@` and `waitlist@`.

The secret key for Resend lives in Vercel, not in GitHub (that is correct). You need the Resend login as well, or a developer must show you that the key is in Vercel under the website project.

### E. What is not a separate “school account” yet

- **Supabase** (student logins) — planned, not in active use on the live LMS.
- **Apple / Google developer accounts** — not part of a published app handover.
- **Paystack / Flutterwave** — planned for later, not a live payment setup in this handover.

---

## 5. GitHub in plain English

You do not need to write code. You only need to recognise the rooms.

1. Open [https://github.com/St-Gabriel-Technical-School](https://github.com/St-Gabriel-Technical-School).
2. You will see two folders (projects):
   - `st-gabriel-technical-college-website`
   - `St-Gabriels-Technical-Schools-LMS`
3. Click a folder to see the files. You do not need to edit them.
4. If a developer wants to change the live site, they open a **pull request** (a “please approve this change” request). You will see those under the **Pull requests** tab.
5. Only the **Maintainers** group can publish those changes onto `main` (the official version). That is deliberate.

### Who is allowed to do what

| Person | GitHub username | School cabinet role | Can suggest changes | Can publish to the live official copy |
| --- | --- | --- | --- | --- |
| You (school) | `SG-Tech25` | Owner | Yes | Yes |
| Lead developer | `ZZYXX-CC` | Owner, Maintainers team | Yes | Yes |
| Junior developer | `StanleyDcoder` | Member, Developers team | Yes | **No** |

How we locked that:

- Both projects require a **review** before the official copy (`main`) can change.
- The Maintainers team is listed as the code owners. Their approval is required.
- Only Maintainers can complete the publish step, and only through a pull request. Nobody should be pushing straight onto the live official copy.

You should **not** make Stanley an Owner. Owner can bypass the safety rules.

### Teams (the two groups)

- **Maintainers** — people allowed to publish. Today: `SG-Tech25` and `ZZYXX-CC`.
- **Developers** — people allowed to work and send requests. Today: `StanleyDcoder` (and `SG-Tech25` is also listed here; you can ask the lead developer to remove the school account from Developers so that group is only for staff who write code).

---

## 6. How a change should happen from now on

Give this to any developer, including Stanley:

1. They copy the project and work on a **side version** (a branch), never on `main`.
2. They send a **pull request** into `main`.
3. The lead developer (or you) reads it and approves.
4. The lead developer clicks **Merge**. Vercel then updates the live website automatically.

If someone asks you to “just send me the password so I can upload,” say no. They can have a GitHub invitation as a Developer. They cannot have the school email password or the Vercel password.

---

## 7. School email and the waitlist

**Incoming school mail** (people writing to you) is handled by **Hostinger**.

**Outgoing waitlist notices** (the website writing to you when someone joins the waitlist) are handled by **Resend**.

Addresses to keep working:

| Address | Used for |
| --- | --- |
| info@stgabrieltech.com | Main school contact, GitHub billing email, waitlist copy |
| waitlist@stgabrieltech.com | Waitlist copy |
| no-reply@stgabrieltech.com | The “from” address on waitlist emails |
| admissions@ / hello@ / careers@stgabrieltech.com | Shown on the contact page — create these inboxes on Hostinger if they do not exist yet |

Create missing inboxes on Hostinger **before** you advertise those addresses, or people will write into a black hole.

---

## 8. What is live, what is unfinished

Be honest with staff and vendors. Over-selling the LMS will cause complaints.

**Live today**

- Public website on `stgabrieltech.com`
- Domain connected through Vercel
- School mail routing through Hostinger
- GitHub organisation with both projects, teams, and publish rules
- LMS preview on Vercel (demo content)

**Not finished / not to be treated as production**

- Real student accounts and course progress
- Real payments
- Real lesson videos tied to school courses
- Mobile apps on the App Store / Play Store
- Admissions application emails (still pointing at the wrong address in code)
- Some contact-page phone numbers still look like examples
- Two-step verification is **not** yet forced on the whole GitHub organisation — turn it on for the school login today

---

## 9. People and how to reach the work

| Role | Who | GitHub | What they do after handover |
| --- | --- | --- | --- |
| Owner | You | `SG-Tech25` | Holds the school email, GitHub, and (once transferred) Vercel |
| Lead developer | Current developer | `ZZYXX-CC` | Reviews and publishes changes |
| Junior developer | Stanley | `StanleyDcoder` | Builds features, sends pull requests |

Stanley has already joined the organisation. He does not need the school password.

If the lead developer ever leaves, **do not delete the GitHub organisation**. Remove them from Maintainers and Owner after a new trusted person is added. Always keep **two** Owners so one lost password cannot lock the school out. Right now the two Owners are `SG-Tech25` and `ZZYXX-CC`. When you are comfortable, add a second school person as Owner and then you can remove the outside developer.

---

## 10. If something breaks

| Problem | What to try |
| --- | --- |
| Website is down | Open the spare link: [st-gabriel-technical-college-websit.vercel.app](https://st-gabriel-technical-college-websit.vercel.app). If that works but `stgabrieltech.com` does not, the domain / Vercel connection is the issue. Log into Vercel. |
| You cannot log into GitHub | Use Forgot password. The reset goes to the school email. |
| You cannot open the school email | Log into Hostinger. If that fails, Hostinger support with the domain name `stgabrieltech.com`. |
| A developer says they cannot upload | They should send a pull request, not ask for the school password. |
| Waitlist form says it failed | The Resend key in Vercel is missing or expired. A developer must check Vercel → the website project → Environment Variables for `RESEND_API_KEY`. |
| Someone left the team | GitHub organisation → **People** → remove them. Also change the school email, GitHub, Vercel, Hostinger, and Resend passwords. |

GitHub support: [https://support.github.com](https://support.github.com)  
Vercel dashboard: [https://vercel.com/dashboard](https://vercel.com/dashboard)  
Hostinger: [https://www.hostinger.com](https://www.hostinger.com)

---

## 11. Direct links (bookmark these)

**For you (non-technical)**

- Live website: https://www.stgabrieltech.com
- Learning preview: https://st-gabriels-technical-schools-lms.vercel.app
- GitHub school home: https://github.com/St-Gabriel-Technical-School
- School website code: https://github.com/St-Gabriel-Technical-School/st-gabriel-technical-college-website
- LMS code: https://github.com/St-Gabriel-Technical-School/St-Gabriels-Technical-Schools-LMS
- School GitHub profile: https://github.com/SG-Tech25

**For a developer**

- Organisation: `St-Gabriel-Technical-School`
- Official branch on both projects: `main`
- Teams: `maintainers` (publish) and `developers` (propose)
- Website waitlist env var: `RESEND_API_KEY`
- Website application form env vars (if you finish that form): `SMTP_HOST`, `SMTP_PORT`, `SMTP_USER`, `SMTP_PASS`, `SMTP_FROM`

---

## 12. Handover checklist

Tick together on the day. If a box is empty, that item is **not** handed over yet.

### You received

- [ ] School email inbox open on this computer
- [ ] GitHub login `SG-Tech25` works
- [ ] GitHub password changed
- [ ] Two-step verification turned on for `SG-Tech25`
- [ ] You can see both projects in the organisation
- [ ] Live website opens
- [ ] Learning preview opens
- [ ] Hostinger (email) login works
- [ ] Vercel login works, **or** both projects have been moved into a Vercel account under the school email
- [ ] Resend login works, **or** the lead developer showed you the waitlist key inside Vercel
- [ ] A test waitlist submission arrived in `info@` or `waitlist@`
- [ ] You know who Stanley is, and that he cannot publish alone
- [ ] You know the lead developer’s GitHub name (`ZZYXX-CC`)

### You were told, honestly

- [ ] The public website is live
- [ ] The learning platform is a preview, not a full student system
- [ ] There is no App Store / Play Store app to take over
- [ ] Some contact details and the admissions form still need cleanup

### Sign-off

| | Name | Signature | Date |
| --- | --- | --- | --- |
| Handed over by | | | |
| Received by (school owner) | | | |

---

## 13. Private credentials sheet

**Print this page. Do not put these passwords in WhatsApp, GitHub, or email.**

Fill this in by hand on handover day. After passwords are changed, destroy the old copy.

| Account | Web address | Username / email | New password (write after you change it) | Recovery |
| --- | --- | --- | --- | --- |
| School email | Hostinger / webmail | info@stgabrieltech.com | | Phone / backup email: ________ |
| GitHub (school) | github.com | SG-Tech25 | | Same school email |
| Vercel | vercel.com | ________ | | ________ |
| Hostinger control panel | hpanel.hostinger.com | ________ | | ________ |
| Resend | resend.com | ________ | | ________ |
| Domain (if different from Vercel) | ________ | ________ | | ________ |

Spare recovery codes (GitHub two-step verification) — store offline:

```
________________________________________________
________________________________________________
```

---

## 14. One-page summary you can read aloud

“The school website is live at stgabrieltech.com. The files live in a GitHub organisation called St Gabriel Technical School. You are getting the school email and the GitHub login SG-Tech25, which owns that organisation. Two developers can work on it: the lead developer publishes, Stanley only proposes. The learning app is a preview, not a finished classroom. Email is at Hostinger. The website is published by Vercel. Change every password today and turn on two-step verification.”
