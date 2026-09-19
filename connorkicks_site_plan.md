# connorkicks.com — Site Plan

Compiled Sept 19, 2026 from the Sept 15 site spec and the Sept 19 ideas file. This file replaces both. Everything below is an idea, not a commitment, unless it is marked live, built or decided.

Live site: https://www.connorkicks.com
Stats page: https://www.connorkicks.com/stats.html
Repo: bvonstein11/connor_kicks, branch main. Upload at github.com/bvonstein11/connor_kicks/upload/main

---

## 1. What the site is for

Until about sophomore year the site is a digital record: a dated scrapbook of film, numbers and milestones. From sophomore year on it becomes a recruiting site.

Hudl and YouTube are warehouses; this site is a timeline. A coach who lands here in 2028 should be able to scroll back to eighth grade and see the whole arc: growth from 5'0" and 98 lb to today, camp scores climbing with dates and official charts, two-team live reps starting in seventh grade, the next evaluation date, curated film that explains each clip before he presses play, and academics and character once they are ready. The pitch is that he has been building toward this since he was eleven.

## 2. Standing rules

| Rule | What it means |
|---|---|
| Every number shows its source and scale | Camp average or best-2, TDY or GST, and altitude. |
| No live schedule | City, event name and date are fine, since Kohl's publishes them. Never a venue, hotel, check-in time, practice, or "we are here now." |
| No location data in media | Strip metadata from every photo and video. |
| Family approval first | Quotes and academics go live only after the family signs off. |
| No misses in film | Film and recaps show no misses at this age: ceiling and trajectory, not the floor. The field goal page is the one place misses appear, as make rates by spot. Unedited game film matters later, when he is being evaluated for starting jobs. |
| YouTube is the warehouse | The channel holds every good rep in order. The site curates and explains, and never copies the archive. |
| Email, not a form | Coaches live in their inbox. A form lands in a generic bucket and stores messages on someone else's server. |
| Claims stay with the data | The About line says first in class 2031 "in kickoff," not kickoff and punt, because Jacob W. punted 75.87 to Connor's 70.40 at Denver in May. |
| Build from live | Every edit starts from the live repo file. |

## 3. Recruiting reality

Verified Sept 19, 2026.

Email is the first contact. D1 football coaches can start recruiting contact (calls, texts, emails and recruiting materials) on June 15 after sophomore year, which for Connor is June 15, 2029. The NCAA moved that date up from Sept 1 of junior year in April 2023. In-person, off-campus contact opens Jan 1 of junior year, which for Connor is Jan 1, 2030. Before June 15, 2029, coaches can send only camp brochures, questionnaires and other non-recruiting material. Connor can email coaches at any time, and unofficial visits can happen at any age. Sources: CBS Sports, Apr 14, 2023, reporting the Division I Council vote; SportsRecruits, Aug 2026. Re-verify in spring 2029.

The pipeline as planned: eighth grade now, Valor Christian in ninth (possibly JV reps), varsity as the sophomore-year goal if size and strength are there, then the June 15, 2029 contact date. Until then the site's job is to be the place Connor points coaches to (film, numbers, story, next event) rather than an inbox.

## 4. Status at a glance

Already live: dated measurables for each year; the two-team story (CHC Lions and Parker Hawks); camp-over-camp trajectory numbers; 12 game recaps in a popup; the 7th-grade highlight reel; hero game film of a Valor Stadium touchback; stats.html with Kohl's camp averages, official result links, archived chart images and altitude and ball footnotes; the growth popup; Email, X, Instagram and YouTube in the contact row; Kohl's and CSK profile links in the header.

| Item | Status | Next step |
|---|---|---|
| LAST / NEXT line | Live | LAST gets a hand edit after each game or camp. NEXT reads Kohl's Fall Assessment, Denver, Oct 18. |
| Location | Live | "Kicker / Punter · Highlands Ranch, CO" in the hero. |
| About line fix ("in kickoff") | Live | None. |
| Game recaps | Live (12) | CHC Games 1–3 (2026); Hawks Games 1–8 and the Super Bowl (2025). |
| stats.html "#" header links | Resolved | None remain. On the homepage, the height and weight lines open the growth popup. |
| Valor line in hero | Live | "VALOR CHRISTIAN HS · FALL 2027" (§5). |
| Why Valor sentence | Live | In About (§5). |
| Email subject | Live | Opens pre-filled with "Connor von Stein · K/P 2031 · Colorado." |
| Growth-pace fix | Live | "Between mid-February and his fourteenth birthday, a pace of about 4.8 inches a year." |
| Rolling NEXT | Now | §6.1 |
| PR dates on stat cards | Now | §6.2 |
| Kickoff volume card | Live | 7th grade: 63 kickoffs, Hawks 45 and Lions 18, 6 onside with 2 recovered. Touchback rate held until the 8th-grade number exists (§6.9). |
| Field goal page | Now | Publish after three dated sessions, around Dec 2026 (§6.3). |
| Origin story | Now, ready | §6.4 |
| His own words | Now | First capture Oct 18 (§6.5). |
| Side-by-side form | Now | Footage in hand (§6.6). |
| Film index | Now, blocked | Needs 8–12 YouTube links, each with a one-line label (§6.7). |
| Training log | Collect now, publish 2027 | §6.8 |
| Film tab, punt section, progress timeline, camp cards | 2027 | §7 |
| Class comparison, coach one-pager | Recruiting phase | §8 |
| Visitor analytics | Any time | Matters most from junior year (§8). |
| Beyond the Field, character quote, seasonal hero | Optional or waiting | §10 |
| Academics, coaching roster, strength and speed | Held, decided | §9 |

## 5. Uploaded Sept 19 — done

Done. The merged index.html went up on Sept 19 and is the working copy. It carried all four built changes above and replaced the two earlier builds (the growth-pace file and the first Valor-and-email file). Both were made from the same live file, so whichever went up second would have erased the other. Upload only the merged file. It was checked at 360, 390 and 1440 px wide with no sideways scroll and no script errors. The live file was re-checked at 4:47 pm MT on Sept 19 and was unchanged; if anything else goes up first, rebuild before uploading.

Why Valor, as written (confirm before upload): "He plans to attend Valor Christian for high school because every level of the program practices together, so a freshman specialist trains alongside the varsity from his first day." The Sept 15 spec also named the kicking coach and the college pipeline as reasons; either can be added.

The hero line says "HS" because "HIGH SCHOOL" wraps onto two lines on 360 px phones.

## 6. Now — fall 2026

### 6.1 Rolling NEXT

The LAST / NEXT line sits under the name: the last game or camp, and the next public camp or showcase, as city, event name and date only. In the off-season, LAST becomes the last camp or a training note.

The upgrade is a dated list of camps and showcases, so NEXT rolls forward by itself when an event passes. LAST stays a hand edit. NEXT never shows practices. The 8th-grade NEXT EVENT stat card shows the same event, so the list should drive both.

Phoenix (Dec 20) goes on the list only once he is registered, since it is a go/no-go call around Dec 10. The About popup already says a Kohl's Winter Showcase this December will be his first national ranking event; a no-go means editing that sentence too.

### 6.2 PR dates on the stat cards

The 8th-grade cards show best kickoff 87.0 (single game kick, 55 yd, 3.2 hang), longest field goal 50 (practice only) and best punt 80.5 (single game punt, 28 yd, 3.50 hang). The one addition is the date each was set.

### 6.3 Field goal page

The honest number: make rate by spot, misses included. Showing misses is what makes every other number on the site believable.

Charting is one session a month on the 9th–10th grade NSC chart: 30, 35, 35, 40, 40, 45, 45, 50, 50, 52. That is ten kicks for 11 points, with the 52 worth two. Three monthly sessions roll into a quarterly score out of 33, the same shape as the NSC chart itself. He moves to the 36-point chart ahead of NSC July 2029, his first in the 11th–12th grade group; those distances are still to be confirmed with Groner.

The page is a field map with a dot per spot showing its make rate. The default view is the last three months, and history runs back two years. Tapping a dot shows that spot's makes and misses. Each miss logs two things separately: direction (left, center or right) and distance (short, or had the distance). "Left, had the distance" is a path fault and "short" is a leg fault, and they have different fixes. Every session records its ball, block and altitude (GST from Oct 21, 1-inch block).

A mock exists (fg_chart_MOCK.html). **The charting workbook does not exist yet and is the blocker: it has to be built before the first October session, or that session gets reconstructed from memory afterwards.** Publish once three dated sessions exist, around Dec 2026; stats.html already promises a make-rate table at that point. Game recaps still leave misses out.

### 6.4 Origin story

The facts: Connor played soccer from age 3 to 11. Through soccer he met Jon Baker, a coach who turned out to be a nine-year pro kicker, and asked him for a lesson. At 11 he left soccer to kick and punt full time, while most kickers his age still split practice time with soccer.

Where it goes: two or three sentences under the "First practice, September 2024" video at the bottom of the 6th-grade section. He made 3 of 10 field goals from 15–35 yards that day; by 8th grade his longest practice make is 50.

Jon Baker, verified against Wikipedia, ProStar Sports Agency and the NFLPA:

| Item | Detail |
|---|---|
| Background | Born 1972, Bakersfield, CA. Lettered in soccer as well as football in high school. |
| College | Arizona State; second-team All-Pac-10, 1994. |
| NFL | Undrafted, 1995. Kickoff specialist for the Dallas Cowboys (1995) and Kansas City Chiefs (1999); 5 games. Camps with the 49ers and Dolphins. |
| Elsewhere | NFL Europe (Scottish Claymores, 1998). CFL: Edmonton (led the league in kickoff average, 1999) and BC Lions. af2 record 54-yard field goal, 2003. |
| Career | Nine pro seasons, 1995–2003. |
| Now | Vice President, ProStar Sports Agency; NFLPA-certified agent since 2016. |

Wording for the site: "a nine-year pro kicker who played for the Dallas Cowboys and Kansas City Chiefs" — without the name. He is an NFLPA-certified agent today, and naming a current agent alongside a 14-year-old prospect invites a question the story does not need. The detail that matters is the pedigree, not the person. His NFL work was kickoffs with no field-goal attempts, so avoid anything that implies NFL field goals. Leave out the Super Bowl XXX championship; the Cowboys released him in September of that season. His name stays in this file for accuracy; it does not go on the site.

The thread worth pulling: Baker's pro specialty was the kickoff, and kickoff is where Connor finished first in class 2031 at Auburn and Denver.

### 6.5 His own words

One or two lines after each camp, written down verbatim and shown small and italic under that camp's numbers, with the date. Ask questions that can't be answered with "fine": What did the coach tell you to change? What was the hardest kick of the day? What can you do now that you couldn't in May? First capture: Oct 18. Over four years it becomes a record of how he thinks about the craft, and probably the part most worth rereading. Its long-term home is the progress timeline (§7).

### 6.6 Side-by-side form

The same kick at two points in time, synced on the contact frame and playing together. The first pair can come from existing footage: a 7th-grade reel rep against this season's game film. The angles won't match, but the approach and follow-through will read. From here on, film a fixed-angle form clip every quarter from the same tripod spot, side-on and from behind with yard lines in frame, at the quarter's last field goal session. By junior year that is a sequence rather than two points.

### 6.7 Film index

A short curated index, not a dump: 8–12 clips, one per milestone, such as first camp, first game, best kickoff and first punt on the big ball. Each item embeds the YouTube video and adds what the channel can't: date, ball, altitude and what it meant. Filters are Kickoff, Punt, PAT and Field goal, with season or grade as a second filter rather than a matrix. Practice field goals are included and labeled, for example "Practice · 38 yards · Sept 2026"; at this age any FG film is rare, and the label does the honesty. It is blocked on the YouTube links and a one-line label for each. How it relates to the 2027 Film tab is an open decision (§10).

### 6.8 Training log: collect now

The off-season is when the work nobody sees happens. Keep dated entries, not a diary, posted only after the fact. Track camp attendance, practice distance and accuracy, off-season showcases, and non-football work that signals character, such as a job, volunteering, flight hours or scuba. Entry format example: "June: added 8 yards to KO average in six weeks." Weight-room numbers were on the Sept 15 list but come off under the Sept 19 strength-and-speed decision (§9). The page itself waits for 2027.

### 6.9 Touchback rate

The kickoff card shows volume. Rate is the number a coach reads first, and it needs a denominator of deep kicks only, since pooches, squibs and onsides are called plays rather than attempts at distance. Oct 11 makes the point: 1 touchback in 5 kickoffs reads 20%, but 1 in 2 deep kicks is 50%.

Seventh grade stands at 3 confirmed touchbacks (Aug 30, Oct 1, Oct 11) against roughly 49 deep attempts, about 6%. That is unremarkable alone and becomes worth showing beside the 8th-grade figure, which already has a 55-yard touchback in Game 2. Publish as a pair, not alone. Notaro went 24% to 45% to 74% across three years, and the climb is the story.

Still needed: per-game touchback counts for both teams, and the deep-versus-called split for Hawks Games 2 to 6.

## 7. 2027

**Film tab.** A filterable wall of every clip: tap Kickoffs, Field Goals & PATs, or Punts, then narrow by season. The working name is "Film," which is what coaches call it (not "Library"). It supersedes the commented-out "8th Grade Clips" placeholder already in the page. Individual reps can be cut from the recap builds. GitHub Pages caps a published site at 1 GB, so at volume the clips live on the YouTube channel and embed.

**Punt section.** Punting gets its own space, history and film, instead of a single chart. The lane is wide open: CSK lists zero class-2031 punters, and Kohl's class-2030 punter board ran only 24 deep. Claims stay with the data, which is why the About line says "in kickoff."

**Progress timeline.** Every camp score, growth measurement and milestone on one scrolling line, so the arc shows at a glance instead of across several charts. It is the natural home for his own words, one line under each camp.

**Shareable camp cards.** One clean card per camp, showing the number, its format (camp average or best-2), ball, altitude and date, sized for a phone screenshot so the source travels with the number when someone passes it along.

**Training log, published.** Show the work, not just results: what he is charting and what got fixed. It reads as relentless rather than just talented. Posted after the fact only, never as a live schedule.

## 8. Recruiting phase (sophomore year on)

**Class comparison.** His number beside the class benchmark at the same age, in the same scoring format only. Built so it is easy to pull if it stops flattering him. Not published until the first real class-2031 board exists.

**Coach one-pager.** A single printable page: measurables, best numbers with their formats, film link and contact. It could be a print layout of stats.html.

**Visitor analytics** (replaces the email-capture idea). Coaches rarely leave an email on a prospect's site. Free, cookie-free analytics (GoatCounter, for example) would show roughly where visits come from and what sent them, without asking anyone for anything. It can go in any time; it matters most from junior year.

**Contact extras.** A phone number for later-stage calls, and a Hudl link beside the email once a profile exists (YouTube is already there). Both are open (§10).

## 9. Held — decided

| Section | Decision | Revisit |
|---|---|---|
| Academics | Middle-school GPA stays off; start clean with the Valor record. When it goes up: a clean GPA line, test scores once they exist, and a short note on rigor. The bar for a specialist: 3.7 is the floor, not the ceiling, and rigor beats the decimal. A 3.8 in honors and AP reads stronger than a 3.95 on a soft schedule. | First Valor grades, around Dec 2027 |
| Coaching | No named roster yet. There are too many coaches in the mix, and naming some over others risks friction; wait to see who actually puts in the work (Rafter's return is open). A generic line such as "trains with an NFL veteran kicker" is possible but not decided. | When the coaching stack settles |
| Strength and speed | Not for the site: specialists are recruited on the leg, not a forty or a squat. Private tracking (vertical, squat) is optional as a check on the Pivotal work; Florendo's call. | None |

## 10. Optional, waiting and undecided

**Beyond the Field.** Most of this is already in the About popup as prose: active in church since 2020 and in a youth group this year; more than 80 community-service hours since 2022, including top fundraiser for Wreaths Across America and a team that packed and shipped over four thousand meals for Lifeline Christian Missions; track, fly fishing, scuba certification, seventeen hours of flight instruction, and a German shepherd (Cody, unnamed on the site). A separate section is optional. If it is built: a tight list, not labeled a résumé, two or three lines per item, numbers doing the talking, a one-line "why it matters" only when the fact is unusual (flight hours at 14 is the example), and never "because I love it." Use the current flight-hour count when it is published.

**Character.** Two or three lines from a coach or teacher who isn't Dad; "shows up early, stays late, never complains" is the shape. One quote beats another stat block. It waits until someone writes it, and goes live only with family approval. A quote from one private coach would name him over the others, the same friction as the coaching hold, so a teacher or a school coach is the cleaner source.

**Seasonal hero.** The hero stays video. The clip could change with the season (summer camp, fall game) so the page feels watched; not needed while the Valor Stadium touchback is the strongest first impression.

| Open decision | Options |
|---|---|
| Film | The Sept 15 plan is a curated 8–12 milestone index now; the Sept 19 idea is a filterable wall of every clip in 2027, with three filters instead of four. They can stage: the milestone index first, growing into the Film tab. Also open: its own /film page or a homepage section. |
| About | Keep the modal, or add a shareable /about URL. |
| Phone number | On the site, or email only until junior year. |
| Hudl | Add the link once a profile exists. |
| Section label | "Beyond the Field" or "Outside Football." |
| Coaching line | The generic line, or nothing until the stack settles. |
| Phoenix | The go/no-go around Dec 10 decides the NEXT line and the About sentence about December. |

## 11. Don't break

**Homepage.** The year cards date the measurables: 8th grade 5'7", 115 lb, Sept 2026; 7th grade 5'3", 105 lb, Oct 2025; 6th grade 5'0", 98 lb, fall 2024. The header shows current height and weight. The recap buttons stay wired. About stays a modal unless §10 decides otherwise.

**stats.html.** It is the official-chart archive: camp averages only, not best-2 and not Scholarship Camp session averages. Three scales never share a column. The field goal table waits for three dated sessions.

## 12. Housekeeping

**Upload index.html** — carries the Game 3 poster frame.

**Repo cleanup** (optional, easiest on a computer). IMG_5700–5703.jpeg (uncropped chart screenshots; two show the phone's status bar, none carry location data) and recap_2025_hawks_g7-4.mp4 (byte-identical to Game 7) are unreferenced but public. Press "." on the repo page to open the web editor, delete all five and commit once.

**Corrections to carry into the project brief:**

| Brief section | Fix |
|---|---|
| ATHLETE | "No soccer background" is wrong: soccer from 3 to 11, full-time K/P since 11, first kicking lesson from Jon Baker (the "First practice, September 2024" video). |
| WEBSITE, pending edit | Done. The About line reads "first among class of 2031 athletes in kickoff at Auburn in April and Denver in May." |
| WEEKLY GAME RECAPS, done list | Add Game 3 vs Cherry Creek Black, W 28–6, Sept 15. |
