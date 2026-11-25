# Topic Codebook: News Coverage of Zohran Mamdani

**COMP 370 - Politician in the Media**  
**Unit of annotation:** One article (headline and opening text)

## Purpose and coding rules

This codebook groups news coverage of Zohran Mamdani by its **main subject**, rather than whether the coverage is positive or negative. The six provisional categories were drafted with the collected article themes in mind and should be revised based on the group's manual open coding.

1. Read the article's **title and opening text**. Do not rely on the full article when assigning a topic.
2. Assign **exactly one** of the six topics below to each article. Choose the subject that receives the most emphasis in the title and opening.
3. When several subjects appear, prioritize the **main event or question being reported**, not a passing reference. Use the edge-case rules to resolve overlaps.
4. Do not label criticism automatically as *Political Disputes*: policy criticism remains in the relevant policy topic, and criticism of foreign-policy positions remains in *International Issues*.
5. Record unclear cases in the annotation notes so the group can refine category boundaries. **Topic and sentiment are separate annotations.**

The examples below are **illustrative situations**, not pre-labeled articles from the dataset.

## 1. Elections

**Definition:** Coverage primarily about the New York City mayoral election as a contest: polling, candidates' standing, voters, ballots, or voting outcomes.

**Include:** Opinion polls; primary or general-election results; ranked-choice voting; turnout; candidate rankings; election rules; debate performance when the central question is its effect on the race.

**Examples:** A report comparing mayoral candidates' polling numbers; a story explaining how ranked-choice voting may affect the primary.

**Edge cases:** An endorsement is *Campaign Activities* unless the focus is a measurable change in election standing. A story centered on the details or costs of a housing proposal is *Local Policies*, even if published during the election.

## 2. Campaign Activities

**Definition:** Coverage primarily about efforts to win political support or organize a campaign.

**Include:** Endorsements; fundraising; donations; advertisements; campaign events; rallies; canvassing; volunteer organizing; campaign strategies and coalitions.

**Examples:** A political figure endorses Mamdani; a campaign launches an advertisement or organizes a rally.

**Edge cases:** A poll following an endorsement is *Elections* if polling is the main subject. Accusations of unethical campaign conduct are *Political Disputes* if the alleged conduct, not the campaign tactic itself, is the focus.

## 3. Local Policies

**Definition:** Coverage primarily about proposals, decisions, or debates concerning New York City policy and residents' daily lives.

**Include:** Rent and housing; transportation and free buses; city-run grocery stores; local taxation and budgets; public services; schools; public safety; policing; and the feasibility or effects of municipal proposals.

**Examples:** A discussion of a rent-freeze proposal; an article assessing the cost of a city-run grocery-store plan.

**Edge cases:** Criticism that a proposal is too expensive still belongs here when the **proposal** is central. Coverage mainly about voter reactions or polling belongs to *Elections*. Foreign-policy positions belong to *International Issues*.

## 4. International Issues

**Definition:** Coverage primarily about Mamdani's positions, statements, or controversies related to foreign countries, international conflicts, or foreign-policy matters.

**Include:** Israel–Palestine and Gaza; BDS and international boycotts; comments about foreign leaders or governments; international military conflicts; reactions to his views on these subjects.

**Examples:** An article examining his position on BDS; coverage of disagreement over his remarks about Gaza.

**Edge cases:** Criticism of a foreign-policy view stays here even when politically contentious. A story primarily about discrimination, religious identity, or threats directed at a community belongs to *Identity and Representation*. A rally where international issues are only briefly mentioned may instead be *Campaign Activities*.

## 5. Identity and Representation

**Definition:** Coverage primarily about Mamdani's identity or the representation, experiences, and treatment of social, ethnic, religious, or immigrant communities.

**Include:** Muslim, South Asian, or immigrant identity; representation in public office; identity-based community responses; Islamophobia; antisemitism; discriminatory rhetoric or threats when identity-based treatment is the central subject.

**Examples:** An article about the significance of a Muslim candidate's representation; a report focusing on identity-based harassment directed at the candidate.

**Edge cases:** An article about Israel or Gaza is *International Issues* when the policy position is central. A demographic breakdown of votes is *Elections* when the focus is how groups voted, rather than their representation or experiences.

## 6. Political Disputes

**Definition:** Coverage primarily about allegations, candidate conduct, qualifications, past record, personal controversies, or conflicts among political figures that do not chiefly concern a specific policy position.

**Include:** Disputes about experience or qualifications; allegations concerning conduct; personal criticism or rivalries; scrutiny of past actions or statements; disputes over campaign behavior.

**Examples:** A story questioning a candidate's qualifications; coverage of an allegation about a candidate's past conduct.

**Edge cases:** Criticism of housing or transit proposals is *Local Policies*. Disputes centered on Israel–Palestine positions are *International Issues*. Routine endorsements, fundraising, and rallies are *Campaign Activities*. Threats motivated by religious or ethnic identity are *Identity and Representation* when that treatment is the focus.

## Cross-category decision guide

| If the article mainly discusses... | Use |
| --- | --- |
| Polls, voting rules, results, or who's ahead | Elections |
| Endorsements, fundraising, campaign outreach, or rallies | Campaign Activities |
| The substance, cost, or consequences of an NYC policy | Local Policies |
| A stance on an international issue, including backlash about that stance | International Issues |
| Personal identity, representation, or identity-based treatment | Identity and Representation |
| Qualifications, conduct, allegations, or personal political conflicts | Political Disputes |

**If no category seems to fit:** Do not force a final judgment silently. Record the article ID and issue in the notes, then raise it during group codebook review. The group must still choose one category for every article in the finalized dataset.
