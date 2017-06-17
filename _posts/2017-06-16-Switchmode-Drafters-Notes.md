---
title: Switchmode Drafter's Notes
description: first draft of the form, line by line
layout: post
tags:
- Contracts
- Open Source
---

> # Switchmode Developer Agreement
>
> **Company** and **Developer** agree to these terms, the First Draft of the First Edition Switchmode Developer Agreement:

Under the terms of the current Law form License, others are free to make changes to the form, as long as they make clear that their form isn't standard Switchmode.  That could easily happen here, by adding "based on" ahead of "the First Draft...".  That sends two important messages:

1.  The form you're looking at isn't the standard form.

2.  But a comparison to the standard form is probably a good way to start understanding what you're being offered.

> ## Purpose<a id="Purpose"></a>
>
> Open software developers and companies approach intellectual property, confidentiality, and other legal matters differently. The expectations of their user and customer communities differ, too. The purpose of this agreement is to enable _Developer_ to bridge the gap and do paid work for _Company_ without creating issues either for _Company_ or for _Open Software_ efforts that _Developer_ has participated in, or may participate in later. This agreement achieves that purpose with intellectual property, confidentiality, and other terms that vary, depending on whether open or proprietary expectations apply to specific work.

Switchmode isn't just a plain-language restatement of standard contract form substance.  Setting out its purpose gives an immediate sense of why the substance differs, and what aims those changes were meant to achieve.

Stating an overall purpose in one place also allows us to refer to it later, in the [severability clause](#Unenforceable_Terms).

> ## Representative<a id="Representative"></a>
>
> _Company_ agrees to appoint a **Technical Representative** by giving _Notice_ of their name, title, and email address before work starts. _Company_ agrees to appoint a replacement _Technical Representative_ if the current one leaves or becomes unavailable. If _Company_ or any _Affiliate_ has technical staff, the _Technical Representative_ must be a member of the technical staff.

This is one of a few places where Switchmode tries to spell out good common practice.  It's been my experience that most open-source development contracts only come together because an engineering employee of the company understands what open-source software is, and how it will be valuable to the company.

This provision gives that person a name in the contract---Technical Representative.  Other parts of the terms give the Technical Representative limited authority to make decisions for the company, on technical and working-relationship questions.

> ## Projects<a id="Projects"></a>
>
> The terms of this agreement apply to each **Project** that _Company_ and _Developer_ write up and cosign in a **Project Summary**. Each _Project Summary_ must refer to this agreement, say that it's a _Project Summary_, and set out what _Developer_ agrees to do for _Company_ and what _Company_ agrees to pay _Developer_ for the work.

Switchmode is a master agreement, meaning it sets out terms that fill in the details of shorter documents describing actual work to do later.  The most common term for those kinds of mini-agreements under master terms is probably "statement of work".  Switchmode uses plainer terms.

> ## Open and Closed<a id="Open_and_Closed"></a>
>
> Some terms of this agreement apply to a _Project_ depending on whether the _Project Summary_ calls it a **Open Project** or a **Closed Project**. If a _Project Summary_ does not say, the _Project_ is an _Open Project_.

The fundamental thesis of Switchmode is that open-source-style developers and their would-be corporate clients want to do a mix of projects.  Some of those look like paid open-source development, the kind of thing The Linux Foundation or The Apache Foundation might pay for.  On the other hand, there will be proprietary projects, producing IP that belongs to the company-client, with more concern for secrecy.

Rather than expect developers and clients to decide and write out all those variations in statements of work, Switchmode gives them a choice of two sets of terms---Open and Closed---for each project.  The default is Open, but even Closed anticipates use and possible release of open-source software.

> ## Default Project Terms<a id="Default_Project_Terms"></a>
>
> All of these terms apply to each _Project_, unless its _Project Summary_ says otherwise:

All the same, Switchmode doesn't try to _stop_ developers and clients from writing custom terms, even specific legal terms, into their project summaries.  In essence, project summaries can overload most of the major categories of terms, including all operational and IP terms.  The most important exceptions---terms project statements _can't_ override---are confidentiality and contractor-not-employee terms.  That makes it more important to get those particular terms right.  That being the case, clients can worry less about each project statement.

> ### Fees<a id="Fees"></a>
>
> _Company_ agrees to pay _Developer_ fees for _Project_ work on an hourly basis, in fairly rounded, quarter-hour increments.

Quarter-hour billing default.  Since these terms can be overridden, it's perfectly possible to sign project statements for flat-rate, monthly, or other fee calculations.

> If the _Project Summary_ doesn't state a rate per hour, _Company_ will pay the first of these hourly rates that can be determined:
>
> 1.  the rate in the last _Project Summary_ _Company_ and _Developer_ signed that stated a rate
>
> 2.  _Developer_'s published standard rate
>
> 3.  _Developer_ and the _Technical Representative_'s joint estimate of the going rate for a developer of similar skill and experience

Project summaries for hourly billing should state an hourly rate.  On the off chance they do not, these terms try to provide a reasonable fallback.  The fallback isn't particularly great: "published standard rate" is unavoidably vague, and a joint estimate may not be possible.

> ### Expenses<a id="Expenses"></a>
>
> _Company_ agrees to reimburse _Developer_ for _Project_ expenses listed in the _Project Summary_, expenses that the _Technical Representative_ preapproves in writing, and travel and accommodation expenses for trips that _Company_ requests and _Developer_ agrees to make. _Company_ agrees to advance _Developer_ expenses likely to exceed _Project_ fees for the month incurred, on written request.

Arguments about expense-reimbursement policies sour good working relationships fast.  These terms give total freedom as to _what kind_ of expenses the company-client will reimburse, focusing instead on how they're approved.  Ideally, a project statement would set out every relevant expense, by description and amount for it.

Here we see the first of the Technical Representative's company-representative functions, approving expenses.  Collusion is possible, but clients will usually have leverage to refuse suspicious line-items to individual contractors, and also to discipline Technical Reps who approve expenses too easily.  When expenses come from the Technical Rep's budget, there's arguably nobody more interested in keeping spend down.

> ### Billing<a id="Billing"></a>
>
> For fees calculated on an hourly basis, _Developer_ agrees to send _Company_ a bill at the end of each calendar month. For fees calculated on any other basis, _Developer_ agrees to send _Company_ a bill on the schedule in the _Project Summary_, or if there isn't any, when the _Project_ is done.

Again, a series of fallbacks, to provide some kind of clarity on billing procedure.  I'd be very interested in others' views of whether this would be a better to set monthly billing as the default for non-hourly projects, as well, rather than falling back immediately to bill-on-completion.

> Developer_ agrees to submit bills via any processing system that _Company_ specifies by advance _Notice_. _Company_ waives any additional legal terms that its choice of processing system tries to impose, and agrees to reimburse _Developer_ any costs of using its system.

Large companies frequently outsource or automate payment.  Contractors rarely have the leverage to resist using those systems, even though they're often cumbersome.  But it's unreasonable to hide terms changes in terms for a mandatory payment portal, or to choose a service that shifts fees for the company's convenience onto the ones being paid.

> ### Payment<a id="Payment"></a>
>
> _Company_ agrees to pay _Developer_ all correctly billed amounts within thirty calendar days of receiving each bill. _Company_ agrees to give _Notice_ of any suspected error on a bill within fourteen calendar days of receiving the bill.

Thirty days to pay.

I will seriously consider moving the deadline to report billing errors to match the payment deadline.  A tighter deadline is good for the contractor, but a bit unfair to the client.  Everyone looks at bills when they get around to paying them.

> ### Late Payment<a id="Late_Payment"></a>
>
> _Company_ agrees to pay _Developer_ 1.5% interest on late bill payments, compounded monthly. If the law sets a lower maximum rate of late-payment interest, _Company_ agrees to pay that rate of interest instead.

A standard late-payment-interest provision, in plainer terms.  There's no legal-drafting reason ideas like this can't be expressed in multiple sentences.

> If _Company_ fails to pay any bill on time, _Developer_ may give _Notice_ and stop any or all work under this agreement until all bills due are paid and all suspected errors are addressed. Stopping work in this way automatically postpones all deadlines under every _Project_ for as long as work stops. Retainer and other recurring fees continue to add up.

No work, no pay.  No pay, no work.

> ### Delivery<a id="Delivery"></a>
>
> _Developer_ will deliver work on the _Project_ to _Company_ by giving the _Technical Representative_ an Internet address from which to download a copy.

Delivery is to the Technical Representative.  No need to write out and ponder over how that will happen.

> ### Intellectual Property<a id="Intellectual_Property"></a>

The major area where Switchmode's terms "switch" between "modes", based on whether a project is Open or Closed.

> #### Open Project IP Terms<a id="Open_Project_IP_Terms"></a>
>
> For an _Open Project_:
>
> ##### Developer Retains IP<a id="Developer_Retains_IP"></a>
>
> _Developer_ retains all _Intellectual Property Rights_ in _Developed Intellectual Property_.
>
> ##### License to Company<a id="License_to_Company"></a>
>
> Upon _Company_'s full payment of each _Developer_ bill for the _Project_, _Developer_ licenses _Developed Intellectual Property_ covered by that bill to _Company_. For _Intellectual Property Rights_ in any _Derivative_ of _Open Software_, the terms of that license are the same terms on which the _Open Software_ is licensed to the public. For other _Intellectual Property Rights_, the terms are those of a _Separate MIT License_.

Developer retains IP in their work, but gives Company the broad permissions of a standard open-source license.

For work building on preexisting open-source work, or work by other open-source developers, Switchmode implements the "inbound=outbound" norms of contributors licensing their contributions on the same terms provided for earlier work on the project.  For other work, it's the highly permissive MIT License.  With very rare exceptions, companies already using open-source software will already be using MIT-licensed software, without the benefit of terms like Switchmode's additional [provenance guarantees](#Developer_Guarantees).

For license wonks, the definition of [Separate MIT License](#Separate_MIT_License) has a few interesting wrinkles.

> ##### Public License<a id="Public_License"></a>
>
> _Developer_ agrees that if _Developer_ makes _Developed Intellectual Property_ available to the public, _Developer_ will do so under the terms of a _Separate MIT License_.

This needs to be corrected.  The terms should be the same as those described in [License to Company](#License_to_Company), which could be either a Standard MIT License or the current public license terms, for Derivates of Open Software.

This provision tries to head off ambiguity and perceived unfairness if the Developer tries to apply a different open-source license to their code for the public, especially if they use a permissive license in one situation, and a copyleft license in another.

> #### Closed Project IP Terms<a id="Closed_Project_IP_Terms"></a>
>
> For a _Closed Project_:
>
> ##### Developer Assigns IP<a id="Developer_Assigns_IP"></a>
>
> _Company_ and _Developer_ agree that _Developed Intellectual Property_ will be "work made for hire" under copyright law, to the extent legally possible. Upon _Company_'s full payment of each _Developer_ bill for the _Project_, _Developer_ assigns _Developed Intellectual Property_ covered by that bill that cannot be "work made for hire" to the _Company_.

The company-client owns rights in Closed Project work.

> Among the rights assigned are:
>
> 1.  ownership of the _Developed Intellectual Property_
>
> 2.  all rights to take _Legal Action_ for _Infringement_ of the _Developed Intellectual Property_
>
> 3.  all rights to seek legal remedies for _Infringement_ of the _Developed Intellectual Property_, such as money damages, injunctions, and other "equitable remedies", as well as any other compensation, benefits, or procedural privileges a court might award
>
> 4.  all other rights _Developer_ has in the _Developed Intellectual Property_

I'm not sure these clarifications are necessary.  I may remove this language, if and when I find the time to pin down authorities that spell out that "assignment" is sufficient.  At the same time, this kind of thing is a staple of orthodox contracting agreements, and I suspect company counsel will welcome the reassurance.

> ##### Further Steps<a id="Further_Steps"></a>
>
> _Developer_ agrees to do everything necessary to paper assignments in [Developer Assigns IP](#Developer_Assigns_IP), make them legally effective, and help _Company_ enforce the rights assigned. _Company_ agrees to give _Notice_ of any further steps required, to provide all necessary documentation, and to reimburse _Developer_ for reasonable out-of-pocket expenses.

A typical further-assurances clause, as short and plain as I could make it.

> ##### Company Can Act on Developer's Behalf<a id="Company_Can_Act_on_Developer's_Behalf"></a>
>
> ###### What Company May Do<a id="What_Company_May_Do"></a>
>
> _Company_ may take action under [Further Steps](#Further_Steps) on _Developer_'s behalf if _Company_ can't find _Developer_, if _Developer_ isn't capable of doing so, or if _Developer_ refuses to do so.
>
> ###### Legal Intent<a id="Legal_Intent"></a>
>
> In legal terms of art, _Company_ and _Developer_ intend [What Company May Do](#What_Company_May_Do) to appoint _Company_ as _Developer_'s "attorney in fact with full right of substitution" to act on _Developer_'s behalf under [Further Steps](#Further_Steps).

The last, legal clarification shows a drafting principle that I hope to apply throughout the agreement: When a legal term of art can get real work done, use it, but make clear to a casual reader that magic words are being spoken.

> ##### Open Releases<a id="Open_Releases"></a>

Another instance of trying to write out common practice, this time for releasing open-source software out of work that starts life as company-owned contract work.

> ###### Requesting Open Releases<a id="Requesting_Open_Releases"></a>
>
> No more than once per calendar quarter for a recurring _Project_, or once within thirty calendar days after the _Project_ ends for any other _Project_, _Developer_ may send a written **Open Release Request** to the _Technical Representative_. Each _Open Release Request_ must identify at least one **Proposed Release**, a discreet, reusable _Software_ component of _Developed Intellectual Property_ that _Developer_ proposes to publish as _Open Software_. The _Open Release Request_ must note when a _Proposed Release_ is a _Generic Improvement to Open Source_.

The Technical Representative is the primary point of contact and decision maker for open-source releases.  It's arguably their most important function under Switchmode's terms, but their discretion isn't total.

It is very hard to pick terms for what's eligible to release.  I've used three terms---"discreet", "reusable", "component"---that I think meet the most essential criteria:

1.  They're commonly used in software-architecture conversations, among technical folk.
2.  They have substantially the same meaning in general parlance, among educated English speakers.
3.  With the possible exception of "component", in very specific language and framework contexts, they aren't used with too much more precision in technical lingo than the general parlance.

It's very hard to strike a balance between picking and choosing specific words to get a specific meaning, and just using more plain words.  I think this particular language works, but I'm very open to improving it.  I speak both kinds of relevant gobbledygook---software and law---but that might make me the _worst_ objective judge of this language, rather than the best.

Generic Improvement to Open Source is a special category of candidates that takes less to get approved for release.  If defining what qualifies for release _in general_ is hard, an abstraction on top of that is necessarily fuzzier.

> ###### Responding to Open Release Requests<a id="Responding_to_Open_Release_Requests"></a>
>
> _Company_ agrees to task the _Technical Representative_ to respond to each _Open Release Request_:
>
> 1.  The _Technical Representative_ must discuss each _Proposed Release_ with _Developer_, as needed, and decide whether each _Proposed Release_ is an **Approved Release**.
>
> 2.  The _Technical Representative_ must send a decision for each _Proposed Release_, in writing, to _Developer_ within fourteen calendar days.
>
> ###### Approving Open Release Request<a id="Approving_Open_Release_Request"></a>
>
> If the _Technical Representative_ fails to send a decision in time for a _Proposed Release_ that is a _Generic Improvement to Open Source_, and was noted as a _Generic Improvement to Open Source_ in the _Open Release Request_, that _Proposed Release_ automatically becomes an _Approved Release_. Otherwise, a _Proposed Release_ becomes an _Approved Release_ only if the _Technical Representative_ confirms that decision in writing.

Here is the functional difference between Generic Improvements to Open Source and other release candidates.  If the Developer is absolutely confident that a particular piece of work meets the Generic Improvement definition, they can release it even if the Technical Representative stonewalls them.  Otherwise, they need approve to release.

> ###### License to Release<a id="License_to_Release"></a>
>
> _Company_ licenses _Developed Intellectual Property_ in each _Approved Release_ to _Developer_. The license permits _Developer_ to sublicense the _Approved Release_ to the public. For an _Approved Release_ that is a _Copyright Derivative_ of _Open Software_, the terms of the public license must be the same terms on which the _Open Software_ is currently licensed to the public. For other _Developed Intellectual Property_, the terms of the public license must be a _Separate MIT License_. In either case, unless an executive officer gives _Notice_ of permission to attribute the _Approved Release_ to the _Company_ by name, _Developer_ must substitute a statement that _Developer_ sublicenses under the First Draft of the First Edition Switchmode Developer Agreement in place of any usual copyright notice.

Since the company-client, not developer, owns IP in Closed Project work, the developer needs permission to release under an open-source license.  That permission takes the legal form of a license, with rights to sublicense in a very specific way.  Again, Switchmode honors the "inbound=outbound" licensing terms norm for derivatives of open-source software born outside the contract, and uses an MIT License for all that's new.

By default, however, the developer does not get to mention in `LICENSE` or header comments that the company owns the code.  Rather, they list their own name as licensor, with a note that they got their licensing power under a Switchmode agreement.

In cases where the company wants to keep its involvement in the work confidential, perhaps because it might tacitly disclose tactical information about the technology it is using, or the kinds of work it is trying to do, this approach protects confidentiality.  Switchmode gives the company the option to choose regular attribution by name, but that requires Notice, which has to come from corporate, and not just from the Technical Representative.

As far as I'm aware, this use---or abuse---of The MIT License template's flexibility is unprecedented.  As a possible consumer of software licensed in this way, I think the situation is more complicated, but not altogether more risky.  In terms of providing evidence of good provenance, a reference to a publicly available form contract for the private terms that governed IP ownership at creation is a far richer data point than a hacker's name, and perhaps a year.  There's nothing to stop publishers from using a Switchmode-style attribution when they didn't actually sign a Switchmode agreement, or follow its release terms---other than, perhaps, legal claims based on misrepresentation---but there's nothing to stop them putting whatever they like in `LICENSE`, anyway.

> #### Developer Guarantees<a id="Developer_Guarantees"></a>
>
> _Developer_ guarantees that to the best of _Developer_'s knowledge, all of these statements will be true of _Developed Intellectual Property_ when delivered to _Company_:
>
> 1.  _Developer_ has all legal rights needed to license the _Developed Intellectual Property_, if the _Project_ is an _Open Project_, or to assign the _Developed Intellectual Property_, if the _Project_ is a _Closed Project_.
>
> 2.  None of the _Developed Intellectual Property_ has been involved in any _Legal Action_.
>
> 3.  No one else has claimed any rights in any _Developed Intellectual Property_.
>
> 4.  None of the _Developed Intellectual Property_ has been assigned or exclusively licensed to anyone else under a different agreement.
>
> 5.  No one else has any lien on or other right to any of the _Developed Intellectual Property_ that will interfere with or limit the rights _Company_ receives.
>
> 6.  No employer, client, educational institution, or other organization _Developer_ has been affiliated with has any right to claim ownership of any of the _Developed Intellectual Property_.
>
> 7.  If the _Developed Intellectual Property_ _Utilizes_ others' _Software_, data, or other kinds of work, either the _Project Summary_ or the _Technical Representative_ specifically approved that work, or it is _Open Software_.

Almost no open-source licenses have warranties about provenance---that the one giving the license actually has the IP rights to do so.  The only exceptions I'm aware of are Larry Rosen's AFL and OSL license forms.  On the other hand, almost all paid contract-development forms have warranties like these.  There are very good arguments for including them in either situation.

I'll remove the knowledge qualifier in a later draft.  These are points where the developer is very likely to be aware of any issue, and should bear the risk.

I'd also like to make this shorter, though I think a little language here sends the right language.  Developers should take these guarantees seriously.

> #### Open Source Guidelines<a id="Open_Source_Guidelines"></a>
>
> If _Company_ gives _Notice_ of specific _Open Software_ or kinds of _Open License_ that _Company_ permits or prohibits, _Developer_ agrees to follow those guidelines in selecting _Open Software_ that _Developed Intellectual Property_ for any later _Project_ _Utilizes_.

Companies taking open-source software seriously put their policies in writing, so coders can follow them.  Developers under Switchmode should abide by those guidelines as well, but they shouldn't be stuck complying with guidelines they weren't aware of when drawing up and agreeing to Project Statements.

> _Company_ agrees that _Developer_ can rely on LICENSE, COPYING, and similar files, as well as copyright notices, header comments, and package metadata, to determine what license terms apply.

Developers can't be expected to make legal conclusions, or to take the place of dedicated code-audit or compliance consultants while churning out code.  They can and should be expected to understand and take basic steps to maintain license hygiene.

> ### Work on Open Software<a id="Work_on_Open_Software"></a>
>
> Unless _Company_ and _Developer_ agree to a _Project_ covering the work:
>
> 1.  _Company_ does not agree to pay _Developer_ for any additional work to prepare any _Approved Release_, or any _Developed Intellectual Property_ created during work on any _Open Project_, for publication as _Open Software_.
>
> 2.  _Developer_ does not agree to maintain, provide support for, ensure the availability of, or provide any other kind of service for any _Developed Intellectual Property_ published as _Open Software_.

The developer decides when to request open release of Closed Project components, and shoulders the burden of preparing for release when approved.  The other side of the same coin is ongoing maintenance.  Open source release does not obligate anyone to satisfy all comers with maintenance, support, or other services.  The company-client doesn't indenture the developer to provide that kind of work by approving release.

> ### Disclaimers<a id="Disclaimers"></a>
>
> *Developer makes only the guarantees in [Developer Guarantees](#Developer_Guarantees) about Developed Intellectual Property. Otherwise, Developer provides the Developed Intellectual Property without any warranty of merchantability, of fitness for a particular purpose, or of any other kind. If Company takes Legal Action against Developer related to the Developed Intellectual Property, under contract law, tort law, or any other kind of law, the Company's damages from Developer will be capped at the amount of fees Company actually paid Developer under this agreement during the twelve prior calendar months.*

A typical software disclaimer of implied warranties.  I'm not yet sure how necessary this is.  The open-source licenses covering Open Project work almost universally disclaim all warranties and limit damages to zero.  This limitation of liability---to fees paid---is potentially in tension.

Closed Project work assignment is completely governed by these terms.  The developer has a clear contract obligation to deliver what's specified on project statements.

> ### Changes<a id="Changes"></a>
>
> _Company_ and _Developer_ can change any of the terms of a _Project Summary_ by writing out and cosigning an amendment to the _Project Summary_. _Developer_ and the _Technical Representative_ can change _Project Summary_ terms about the work that _Developer_ will do by agreeing to changes in writing.

Contract changes happen all the time, and they take time.  Often, necessary changes to project scope or technical requirements go undocumented, since neither the developer nor their primary contact want to wait on lawyers or procurement personnel.  Again, the Technical Rep gets a bit of discretion, but not to change fundamental legal or risk-shifting terms.

> ### Project Term<a id="Project_Term"></a>
>
> If the _Project Summary_ describes recurring work, the _Project_ continues until either _Developer_ or _Company_ gives _Notice_ that it will stop at the end of the next calendar month. Otherwise, the _Project_ ends when _Developer_ finishes work. _Company_ and _Developer_ can agree to end a _Project_ early at any time.

Switchmode aims to support both recurring, on-call service projects, like providing support, as well as one-off, build-out projects.  The termination mechanisms need to allow room for termination by the company when need for a project ends, while protecting developer from foregoing other opportunities, only to find a project cancelled.

> ## Confidentiality<a id="Confidentiality"></a>

Standard contractor forms are a poor fit for open-source or even open-source-compatible engineering work on many points, but the most glaring issues tend to be in the "confidentiality and invention assignment agreements".  To make the developer-company crossover work, Switchmode has to provide confidentiality terms.  Signing a standard company CIIA with wiser master terms might soften the obviously conflicting terms of the CIIA, since courts will read the documents together.  But that kind of self-contradiction is a far cry from the level of certainty written agreements are supposed to provide.

> ### Secrets<a id="Secrets"></a>
>
> The confidentiality obligations of these terms apply to the **Secrets** of both parties. _Secrets_ include these kinds of information, when not _Publicly Available_:
>
> 1.  _Information Marked Confidential_ from either party
>
> 2.  _Business Information_ from either party
>
> 3.  _Personal Information_ from either party

These definitions encompass the vast majority of what's usually defined and protected as "Confidential Information" under a standard NDA.

> 4.  the fact that _Company_ is _Developer_'s client for work on any _Project_

Note that protecting this as a secret---at least at the company's option---requires special provisions elsewhere.  Since open-source development is a fundamentally public process, and open-source software release is a form of publication, and thus disclosure, client anonymity has to be implemented in those terms, too.

> 5.  information about any _Closed Project_

Note the absence of "information about any Open Project".  Open Projects are open-source projects.  They will be disclosed.

> 6.  information about any _Company_ product or service that _Utilizes_ or motivates any _Open Project_
>
> 7.  information about the _Software_, services, systems, and other tools that _Company_ uses

A few technical points as well.  These are very arguably covered by other defined terms in the list, but help to call out their most common anticipated applications to the work of software development.

> ### Keeping Secrets<a id="Keeping_Secrets"></a>
>
> With the exceptions in [Work with Open Software Communities](#Work_with_Open_Software_Communities), unless compelled by a _Legal Requirement_, _Company_ and _Developer_ agree not to:
>
> 1.  disclose each other's _Secrets_ to anyone
>
> 2.  use each other's _Secrets_ for any purpose but _Project_ work
>
> 3.  use or disclose each other's _Secrets_ in violation of any _Legal Requirement_
>
> 4.  help others disclose or use each other's _Secrets_ in these ways
>
> ### Work with Open Software Communities<a id="Work_with_Open_Software_Communities"></a>

Switchmode's confidentiality terms accommodate open-source development both in the how Secrets is defined, and with particular exceptions to obligations to keep Secrets.

> #### Publishing Open Software<a id="Publishing_Open_Software"></a>
>
> _Developer_ may publish the _Software_ of any _Approved Release_ or _Open Project_ as _Open Software_, as long as _Developer_ removes all other _Company_ _Secrets_ before publishing.

This is likely implied when the IP terms and confidentiality terms are read together.  What's new is the obligation to remove extraneous company Secrets from an Approved Release before releasing.  Recall that preparing an Approved Release for publication is on the developer's time and dime by default.  There's nothing to stop a project statement for prerelease work, but the company doesn't commit to compensate the developer for that kind of thing just by approving a release.

> #### Collaborating with Open Software Developers<a id="Collaborating_with_Open_Software_Developers"></a>
>
> In specific circumstances, _Developer_ may disclose _Company_ _Secrets_ of a strictly technical nature to developers of _Open Software_:
>
> 1.  _Developer_ may only disclose _Secrets_ of a technical nature.
>
> 2.  _Developer_ may not disclose _Company_ _Secrets_, even of a technical nature, that would prevent or destroy intellectual property protection, such as patentable inventions or trade secrets, or that would afford _Company_ competitors any significant advantage over _Company_ in any line of business.
>
> 3.  _Developer_ may not disclose _Company_'s identity, any _Information Marked Confidential_, or any _Personal Information_.
>
> 4.  _Developer_ may disclose _Secrets_ only as needed for effective and efficient collaboration with _Open Software_ developers.
>
> 5.  _Developer_ may disclose only to receive technical support for, report a possible bug in, or to propose or discuss changes to, _Open Software_.
>
> 6.  The _Open Software_ must be _Software_ that a _Project_ _Utilizes_ or potentially _Utilizes_, or _Open Software_ used or potentially used to operate or develop _Project_ _Software_.
>
> 7.  _Developer_ may disclose by private message to an _Open Software_ developer, or by message to a public mailing list, bug tracking system, or revision control system.

Open-source software developers don't commit to provide maintenance, support, feature additions, or other services by publishing their code.  But those are key aspects of open-source development---a system of generous give-and-take.  Under the terms of a typical NDA, coders aren't free to disclose much of anything, and take substantial risk each time they reach out to open-source software developers.

Part of the point of hiring an outside developer steeped in open-source development is to leverage someone whose experience and good name afford them access to substantial help from other members of the broader open-source community.  This exception to confidentiality, with a checklist of do's and do-nots, is designed to unlock that value while remaining clear---legally and practically---that the developer does not receive any kind of blank check to disclose about their client willy-nilly.

> #### Technical Representative Guidance<a id="Technical_Representative_Guidance"></a>
>
> _Company_ agrees that _Developer_ can rely on written messages from the _Technical Representative_ that disclosing specific information, or sending a specific message, would fall under [Collaborating with Open Software Developers](#Collaborating_with_Open_Software_Developers).

Lawyers would call this a "safe harbor".  Whether a particular communication to the open-source community actually meets the requirements of the agreement or not, if the Technical Representative pre-approves it, the developer's relieved of the risk of breaching their confidentiality obligations by sending it.

> ### Copies, Changes, and Disposal<a id="Copies,_Changes,_and_Disposal"></a>
>
> _Company_ and _Developer_ agree to provide copies of, update, or dispose of all copies of materials containing each other's _Secrets_ that they have, on written request.
>
> ### Security Precautions<a id="Security_Precautions"></a>
>
> _Company_ and _Developer_ agree to take good security precautions to keep each other's _Secrets_ confidential. _Company_ and _Developer_ agree that on _Notice_ of new security requirements, they will either implement the new security requirements or destroy copies of materials containing _Secrets_ covered by the new requirements they will not implement.
>
> ### Leaks and Disclosures<a id="Leaks_and_Disclosures"></a>
>
> _Company_ and _Developer_ agree to give immediate _Notice_ summarizing what _Secrets_ may be affected, who may receive _Secrets_, and any relevant _Legal Requirement_ whenever:
>
> 1.  they believe a _Leak_ may happen
>
> 2.  they learn that a _Leak_ has happened
>
> 3.  they believe a _Legal Requirement_ will force them to disclose _Secrets_, before making the disclosure, if possible

Standard NDA fare, written as plainly as I could manage.

> ### Confidentiality Clarifications<a id="Confidentiality_Clarifications"></a>
>
> 1.  This agreement does not give either _Company_ or _Developer_ any legal rights in the other's _Secrets_, except the permission needed to review and use disclosed _Secrets_ for _Project_ work.
>
> 2.  This agreement does not require either _Company_ or _Developer_ to disclose any _Secrets_.
>
> 3.  Neither _Company_ nor _Developer_ makes any guarantee that any _Secrets_ they provide will be complete or reliable.

Also standard NDA fare.  Such terms are comforting, but I'm not yet convinced they are legally necessary.

> ### Court Orders<a id="Court_Orders"></a>
>
> Money alone would not fully compensate either _Company_ or _Developer_ for the damage caused by a breach of obligations in [Confidentiality](#Confidentiality). _Company_ and _Developer_ agree that in addition to other legal remedies, they may request court orders not to breach those obligations, to stop breaching those obligations, or both, without posting any bond.

The usual "equitable remedies" clause, without using the dusty, foreign phrase "equitable remedies".

> ## Agreement Term<a id="Agreement_Term"></a>
>
> This agreement will continue until one year has passed since _Developer_ there was any ongoing _Project_. However, both _Company_ and _Developer_ can end this agreement early by giving _Notice_ when there is no ongoing _Project_. Obligations in [Confidentiality](#Confidentiality) will continue for five calendar years after this agreement ends.

Automatic termination to keep a stale agreement from lingering on in perpetuity, plus a right to terminate at will when that won't take a project with it.  Note the separate terms for early project termination.

> ## Kind of Working Relationship<a id="Kind_of_Working_Relationship"></a>
>
> ### Independence<a id="Independence"></a>
>
> No matter what any _Project Summary_ says, _Company_ and _Developer_ intend for _Developer_ to decide when, where, and how to do _Project_ work, with the discretion of an independent contractor, rather than as an employee. _Developer_ agrees that _Developer_ will not receive any employee benefits.
>
> ### Taxes<a id="Taxes"></a>
>
> Both _Company_ and _Developer_ agree to do their respective parts for tax compliance concerning fees and expenses paid to _Developer_ as an independent contractor under this agreement.

The usual 1099-not-W-2 language, ineffective though it often is against facts that point decidedly toward employment, plain and short.

> ## General Contract Terms<a id="General_Contract_Terms"></a>
>
> ### Law<a id="Law"></a>
>
> The law of the state where _Company_'s headquarters are located governs all rights and duties under this agreement.
>
> ### Lawsuits<a id="Lawsuits"></a>
>
> _Company_ and _Developer_ agree to take _Legal Action_ related to this agreement only in the federal or state courts nearest _Company_'s headquarters, and to pay the other's attorney fees and costs if they lose in court.

Every fill-in-the-blank in a legal form is an invitation for mishandling.  The company-client almost always has the leverage to pull a contractor under its local law.

> ### Whole Agreement<a id="Whole_Agreement"></a>
>
> This agreement and each _Project Summary_ list all the terms that _Company_ and _Developer_ intend to apply to _Project_ work.

These often omit any mention of the subsidiary terms documents, like statements of work.

> ### Assignment<a id="Assignment"></a>
>
> With two exceptions, neither _Company_ nor _Developer_ can assign any right under this agreement without _Notice_ of the other's permission. Any attempt to assign against the terms of this agreement has no legal effect. The exceptions are:
>
> 1.  _Developer_ can assign this agreement, as a whole, to any new business entity that _Developer_ sets up for software contracting or consulting work.
>
> 2.  _Company_ can assign this agreement, as a whole, to another business entity that acquires its stock or substantially all its assets, or to a new business entity set up to change _Company_'s legal form or jurisdiction.

Contractors shouldn't be punished by process for maturing their practices and taking basic legal precautions.  Their clients don't want to repaper, either.

Company counsel insist on the latter as a matter of course.

> ### Delegation<a id="Delegation"></a>
>
> Neither _Company_ nor _Developer_ can delegate any duty under this agreement. Any attempt to delegate against the terms of this agreement has no legal effect.

Switchmode is for individual developers working on a person-to-person level with at least one company employee, the Technical Representative.

> ### Unenforceable Terms<a id="Unenforceable_Terms"></a>
>
> If a court decides that any part of this agreement cannot be enforced, for any reason, the rest of this agreement will continue to apply, so long as that wouldn't defeat the purpose of this agreement in [Purpose](#Purpose).

A standard contract clause, somewhat improved by a handy place to reference for an overarching principle to decide whether the terms are at all salvageable.

> ### Signatures<a id="Signatures"></a>
>
> _Company_ and _Developer_ can sign this agreement and any _Project Summary_ however they like, so long as it creates a written record, accessible to both parties, that shows they agreed.

Nothing rankles computer people like wet signature requirements.

> ## Dictionary<a id="Dictionary"></a>
>
> 1.  **Affiliate** means a legal entity that has _Control_ over, is under the _Control_ of, or is under common _Control_ with another legal entity.
>
> 2.  **Business Information** means information that is not _Publicly Available_ about how and with whom a party or or any _Affiliate_ has done, does, or plans to do business. Information about these terms and _Developer_'s compensation is _Business Information_. Information about customers, suppliers, employees, consultants, professional service providers, officers, directors, advisers, employees, and contractors is _Business Information_. Information about transactions, prices, costs, market share, strategy, and financial performance is _Business Information_.
>
> 3.  **Control** means ownership of substantially all the assets of a legal entity or the power to direct management and policies of a legal entity, such as by vote or by contract. _Control_ can be direct or indirect.
>
> 4.  **Copyright Derivative** means the same as "derivative work" under the United States' Copyright Act of 1976.
>
> 5.  **Derivative** means all of these:
>
>     1.  any _Copyright Derivative_
>
>     2.  any _Technology Derivative_ of a _Technology_
>
>     3.  any technology, invention, product, or other item directly or indirectly incorporating or deriving from either of these:
>
>         1.  any part of a _Technology_
>
>         2.  any _Technology Derivative_ of a _Technology_
>
> 6.  **Developed Intellectual Property** means all of these, created by _Developer_ during work on a _Project_, alone or with _Company_ personnel:
>
>     1.  all _Intellectual Property Rights_ in _Technology_ that _Developer_ creates as a result of _Developer_'s work on a _Project_
>
>     2.  every _Derivative_ of any _Developed Intellectual Property_
>
>     3.  every _Embodiment_ of any _Developed Intellectual Property_
>
> 7.  **Embodiment** means:
>
>     1.  documentation, drafts, papers, designs, schematics, diagrams, models, prototypes, _Software_, computer-stored data, computer storage media, manuscripts, and other items
>
>     2.  that describe, embody, record, or store all or any part of a _Technology_, any _Derivative_, any _Intellectual Property Rights_ or related information.
>
> 8.  **Generic Improvement to Open Source** means:
>
>     1.  a _Copyright Derivative_ of _Open Software_
>
>     2.  that is suitable for submission as a patch to the _Open Software_ project from which it derives
>
>     3.  but is not a _Derivative_ or _Embodiment_ of any _Company_ _Secrets_
>
> 9.  **Information Marked Confidential** means information that is not _Publicly Available_, disclosed in materials marked or identified in writing as "Secret", "Confidential", "Proprietary", or similar.
>
> 10.  **Infringement** means infringement of _Intellectual Property Rights_, before or after the date of this agreement.
>
> 11.  **Intellectual Property Rights** means patents, patent rights, copyrights, mask work rights, moral rights, trade names, trademarks, service marks, rights in trade dress and packaging, trade secrets, know-how, goodwill, Internet-based service accounts and account names, domain names, intellectual property rights and proprietary rights, and registrations and applications for _Intellectual Property Rights_, under the laws of the United States and any other state, country, or jurisdiction
>
> 12.  **Leak** means unauthorized disclosure or loss of _Secrets_ from or by a party or any other person a party suspects has obligations to keep the _Secrets_ confidential. A _Leak_ is a _Leak_ whether caused by accident or due to an intentional security breach.
>
> 13.  **Legal Action** means any legal action or claim, ignoring the historical distinction between actions "in law" and "in equity".
>
> 14.  **Legal Requirement** means a requirement of a law, regulation, or order from a court, administrative body, or government institution with legal jurisdiction.
>
> 15.  **Notice** means an email from one party to the other, delivered to the address provided with their signature, or to another address they specify by _Notice_ after signing.
>
> 16.  **Open License** means a form public license approved by the Open Source Initiative as an open source license, or the Creative Commons CC0 1.0 Universal form license.
>
> 17.  **Open Software** means software licensed to the public on the terms of an _Open License_.
>
> 18.  **Personal Information** means all information subject to laws governing collection, storage, use, transfer, and processing of data about individuals, or implicating personal privacy, broadly understood, about individuals who interact with a party, its products, or its services. _Personal Information_ is _Personal Information_ no matter how it is stored and whether or not it is attributable to specific individuals by name or other identifier, aggregated, or anonymized.
>
> 19.  Information is **Publicly Available** in all of these situations:
>
>     1. The information became publicly known for some reason other than breach of this agreement.
>
>     2. The party disclosing the information has made the same information available to others without obligations to keep it confidential.
>
>     3. The party receiving the information received the same information from someone else before, and did not know at the time that the person providing the information was breaking a confidentiality obligation to the other party. The party receiving the information must show this is the case with documents created before it disclosed the information.
>
>     4. The party receiving the information developed the same information, without any help from the party disclosing the information or using any of its _Secrets_, before receiving it from the other party. The party receiving the information must show this is the case with documents created at the time it independently developed the information.
>
> Information is not _Publicly Available_ just because it synthesizes other information that is _Publicly Available_.
>
> 20.  <a id="Separate_MIT_License"></a>**Separate MIT License** means The MIT License, in the form standardized by Software Package Data eXchange with the identifier "MIT", interpreted as an entirely independent legal document, without reference to these terms or the circumstances of _Developer_ and _Company_'s contractor-client relationship.
>
> 21.  **Software** means computer code and software configuration, whether in source, script, or compiled form, for any software or hardware platform, and stored in any format.
>
> 22.  **Technology** means inventions, technology, ideas, concepts, processes, business plans, documentation, financial projections, and models.
>
> 23.  **Technology Derivative** means an improvement, change, alteration, adaptation, enhancement, or new version of a _Technology_.
>
> 24.  _Software_ **Utilizes** another work when it explicitly depends on, installs, configures, invokes, or links to the other work, directly or indirectly.
