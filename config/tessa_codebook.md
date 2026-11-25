# Topic Codebook: News Coverage of Zohran Mamdani as Mayor

**COMP 370 - Politician in the Media**
**Annotator:** Tessa
**Sample:** `data/annotated/tessa_open_coding_50.csv` (articles published 2025-12-18 to 2026-06-01)
**Unit of annotation:** One article (headline and opening text)

## Purpose and coding rules

This codebook groups coverage of Zohran Mamdani by its **main subject**, not by whether the coverage is positive or negative. The categories came from open coding of my 50-article sample. My period starts just before Mamdani took office on January 1, 2026, so most coverage is about him **governing** rather than campaigning.

1. Read only the article's **title and opening text**. Hide the `source` and `url` columns while coding so the outlet does not influence the label.
2. Assign **exactly one** category per article: the subject that gets the most emphasis in the title and opening.
3. **Topic and tone are separate.** Criticism of the mayor goes in the category of whatever is being criticized. For example, an attack on his tax plan is *Fiscal Policy*, not a separate "controversy" category.
4. Category names are deliberately **neutral**. Do not use a headline's framing (e.g. "socialist", "anti-Israel") as a label.
5. If the opening is not real article text (site slogans, boilerplate, or a newsletter teaser about a different story), code from the **title alone** and say so in `notes`.
6. Record any article where you hesitated between two categories in `notes`, naming the other category.

## 1. Elections and Campaigns

**Definition:** Coverage primarily about elections and efforts to win them, primarily by Mamdani's own endorsements as he is already in office and his endorsements carry weight.

**Include:** Mamdani's endorsements of other candidates; primary challenges; his own re-election plans; whether other Democrats seek or avoid his support.

**Examples:** The mayor endorsing a City Council or congressional challenger; candidates who avoided him during the campaign now welcoming his backing.

**Edge cases:** Breaking a campaign promise is not this category. It is coded by the promise's subject (e.g. free buses → *Economic Policy*).

## 2. Transition into Office

**Definition:** Coverage primarily about Mamdani becoming mayor, or broad assessments of his first weeks or months in office.

**Include:** The inauguration and swearing-in; moving into the mayoral mansion; what he promises to do as new mayor; commentary judging his early performance overall.

**Examples:** Coverage of the swearing-in ceremony; an opinion piece arguing his first month shows a pragmatic side.

**Edge cases:** A specific act he takes on day one (for example, revoking executive orders) goes to that act's topic. Protests at the inauguration go to the subject of the protest.

## 3. City Administration

**Definition:** Coverage primarily about how the mayor runs city government day to day, including dealings with other levels of government.

**Include:** Appointments and staffing (e.g. the NYPD commissioner); executive orders about how city government is organized; operational decisions (snow days, street design); ceremonial duties as mayor; meetings and relations with the President and federal government.

**Examples:** Clarifying who the police commissioner reports to; announcing a snow day for public schools; a scheduled White House meeting.

**Edge cases:** If a federal official's comments are mainly about a specific policy, code the policy (e.g. criticism of a tax increase → *Fiscal Policy*).

## 4. Fiscal Policy

**Definition:** Coverage primarily about the city's taxes and budget.

**Include:** His own tax plan; property taxes; the city budget; reactions to his own tax plan.

**Examples:** The mayor announcing the city budget and warning that property taxes may rise.

**Edge cases:** Spending on a specific program is coded by the program (e.g. grocery stores → *Economic Policy*, housing construction → *Housing*).

## 5. Economic Policy

**Definition:** Coverage primarily about city programs aimed at prices, services, or local businesses, other than housing and taxes.

**Include:** City-owned grocery stores; free or reduced bus fares; small-business policy; other public services meant to lower everyday costs.

**Examples:** Opening the first city-owned grocery store; delaying the free-bus promise.

**Edge cases:** Rent and landlords are *Housing*. Taxes and the overall budget are *Fiscal Policy*.

## 6. Housing

**Definition:** Coverage primarily about housing, rent, landlords, and tenants.

**Include:** Rent policy; landlord oversight and hearings; housing construction; housing affordability.

**Examples:** Hearings on landlord practices; a plan to build housing across the city.

**Edge cases:** Gracie Mansion as the mayor's residence is *Transition into Office*, not housing policy.

## 7. Immigration Policy

**Definition:** Coverage primarily about immigration and immigration enforcement.

**Include:** Sanctuary-city status; calls to abolish or limit ICE; immigrants' access to city services; reactions to federal enforcement.

**Examples:** The mayor saying he favors abolishing ICE; defending sanctuary-city status.

**Edge cases:** An article that uses religious language to argue an immigration position is still *Immigration Policy* when immigration is the subject.

## 8. Foreign Policy

**Definition:** Coverage primarily about Mamdani's positions or actions on foreign countries and international conflicts.

**Include:** Israel and Palestine, including city actions concerning Israel; Iran; reactions from foreign governments; protests directed at his foreign-policy views.

**Examples:** Revoking the previous mayor's pro-Israel executive orders; condemning a strike on Iran; Israel's government criticizing him.

**Edge cases:** If the focus is his relationship with a religious community in New York rather than the foreign issue itself, use *Religious Community Relations*.

## 9. Religious Community Relations

**Definition:** Coverage primarily about Mamdani's relationship with religious communities in New York: Jewish, Muslim, Catholic, or others.

**Include:** Attendance or lack thereof of religious holidays and ceremonies; meetings with community leaders; community reactions to him; antisemitism or Islamophobia as local issues; religion in city government.

**Examples:** Celebrating Hanukkah with a Jewish actor; skipping a Catholic archbishop's installation; skipping a local parade that is a major Jewish community event.

**Edge cases:** An Israel policy decision is *Foreign Policy* even if Jewish groups react to it. What he wears or does at a religious event, when that is the story, is *Personal Life and Public Image*.

## 10. Personal Life and Public Image

**Definition:** Coverage primarily about Mamdani as a person and how he presents himself, rather than a policy or official decision.

**Include:** His background and personal interests; his style of communicating; appearances, clothing, humor, sports, and social media; profiles.

**Examples:** Joking online about a basketball rivalry; visiting his old high school; launching a livestream series.

**Edge cases:** Moving into Gracie Mansion is *Transition into Office*. Ceremonial duties as mayor are *City Administration*.

## Cross-category decision guide

| If the article mainly discusses... | Use |
| --- | --- |
| Endorsements, other races, re-election | Elections and Campaigns |
| Inauguration, moving in, overall early assessments | Transition into Office |
| Running the government: staff, operations, the federal government | City Administration |
| Taxes or the budget | Fiscal Policy |
| Groceries, buses, small businesses, public services | Economic Policy |
| Rent, landlords, housing construction | Housing |
| ICE, sanctuary city, immigrants | Immigration Policy |
| Israel–Palestine, Iran, other countries | Foreign Policy |
| Relations with Jewish, Muslim, Catholic or other communities | Religious Community Relations |
| Who he is and how he presents himself | Personal Life and Public Image |

Points for group review: whether to merge *Fiscal Policy* and *Economic Policy*; whether *Political Disputes* is needed once criticism is coded by topic; and whether *Transition into Office* should be one category for the final dataset, since only the later samples contain it.
