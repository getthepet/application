# Contributing to Get The Pet

You want to contribute to Get The Pet? Welcome! Please read this document to understand what you can do:
 * [Help Others](#help-others)
 * [Analyze Issues](#analyze-issues)
 * [Report an Issue](#report-an-issue)
 * [Contribute Code](#contribute-code)

## Help Others

You can help Get The Pet by helping others who use it and need support.

## Analyze Issues

Analyzing issue reports can be a lot of effort. Any help is welcome!
Go to [the GitHub issue tracker](https://github.com/getthepet/backend/issues?state=open) and find an open issue which needs additional work or a bugfix.

Additional work could include any further information, or a gist, or it might be a hint that helps understanding the issue. Maybe you can even find and [contribute](#contribute-code) a bugfix?

## Report an Issue

If you find a bug - behaviour of Get The Pet code contradicting your expectation - you are welcome to report it.
We can only handle well-reported, actual bugs, so please follow the guidelines below.

Once you have familiarized with the guidelines, you can go to the [GitHub issue tracker for Get The Pet](https://github.com/getthepet/backend/issues/new) to report the issue.

### Quick Checklist for Bug Reports

Issue report checklist:
 * Real, current bug
 * No duplicate
 * Reproducible
 * Good summary
 * Well-documented
 * Minimal example


### Issue handling process

When an issue is reported, a committer will look at it and either confirm it as a real issue, close it if it is not an issue, or ask for more details.

An issue that is about a real bug is closed as soon as the fix is committed.


### Reporting Security Issues

If you find a security issue, please act responsibly and report it not in the public issue tracker, but directly to us on hello@waggel.co.uk, so we can fix it before it can be exploited.


### Issue Reporting Disclaimer

We want to improve the quality of Get The Pet and good bug reports are welcome! But our capacity is limited, thus we reserve the right to close or to not process insufficient bug reports in favor of those which are very cleanly documented and easy to reproduce. Even though we would like to solve each well-documented issue, there is always the chance that it will not happen.

Bug report analysis support is very welcome! (e.g. pre-analysis or proposing solutions)


## Contribute Code

You are welcome to contribute code to Get The Pet in order to fix bugs or to implement new features.

There are three important things to know:

1.  You **agree to the Contributors License Agreement**.
2.  There are **several requirements regarding code style, quality, and product standards** which need to be met (we also have to follow them). The respective section below gives more details on the coding guidelines.
3.  **Not all proposed contributions can be accepted**. Some features may e.g. just fit a third-party add-on better. The code must fit the overall direction of Get The Pet and really improve it. The more effort you invest, the better you should clarify in advance whether the contribution fits: the best way would be to just open an issue to discuss the feature you plan to implement (make it clear you intend to contribute).

### Contributor License Agreement

Thank you for your interest in contributing to open source software projects (“Projects”) made available by Get The Pet. This Individual Contributor License Agreement (“Agreement”) sets out the terms governing any source code, object code, bug fixes, configuration changes, tools, specifications, documentation, data, materials, feedback, information or other works of authorship that you submit or have submitted, in any form and in any manner, to Get The Pet in respect of any of the Projects (collectively “Contributions”). If you have any questions respecting this Agreement, please contact hello@waggel.co.uk.


You agree that the following terms apply to all of your past, present and future Contributions. Except for the licenses granted in this Agreement, you retain all of your right, title and interest in and to your Contributions.


**Copyright License.** You hereby grant, and agree to grant, to Get The Pet a non-exclusive, perpetual, irrevocable, worldwide, fully-paid, royalty-free, transferable copyright license to reproduce, prepare derivative works of, publicly display, publicly perform, and distribute your Contributions and such derivative works, with the right to sublicense the foregoing rights through multiple tiers of sublicensees.


**Patent License.** You hereby grant, and agree to grant, to Get The Pet a non-exclusive, perpetual, irrevocable,
worldwide, fully-paid, royalty-free, transferable patent license to make, have made, use, offer to sell, sell,
import, and otherwise transfer your Contributions, where such license applies only to those patent claims
licensable by you that are necessarily infringed by your Contributions alone or by combination of your
Contributions with the Project to which such Contributions were submitted, with the right to sublicense the
foregoing rights through multiple tiers of sublicensees.


**Moral Rights.** To the fullest extent permitted under applicable law, you hereby waive, and agree not to
assert, all of your “moral rights” in or relating to your Contributions for the benefit of Get The Pet, its assigns, and
their respective direct and indirect sublicensees.


**Third Party Content/Rights.** If your Contribution includes or is based on any source code, object code, bug
fixes, configuration changes, tools, specifications, documentation, data, materials, feedback, information or
other works of authorship that were not authored by you (“Third Party Content”) or if you are aware of any
third party intellectual property or proprietary rights associated with your Contribution (“Third Party Rights”),
then you agree to include with the submission of your Contribution full details respecting such Third Party
Content and Third Party Rights, including, without limitation, identification of which aspects of your
Contribution contain Third Party Content or are associated with Third Party Rights, the owner/author of the
Third Party Content and Third Party Rights, where you obtained the Third Party Content, and any applicable
third party license terms or restrictions respecting the Third Party Content and Third Party Rights. For greater
certainty, the foregoing obligations respecting the identification of Third Party Content and Third Party Rights
do not apply to any portion of a Project that is incorporated into your Contribution to that same Project.


**Representations.** You represent that, other than the Third Party Content and Third Party Rights identified by
you in accordance with this Agreement, you are the sole author of your Contributions and are legally entitled
to grant the foregoing licenses and waivers in respect of your Contributions. If your Contributions were
created in the course of your employment with your past or present employer(s), you represent that such
employer(s) has authorized you to make your Contributions on behalf of such employer(s) or such employer
(s) has waived all of their right, title or interest in or to your Contributions.


**Disclaimer.** To the fullest extent permitted under applicable law, your Contributions are provided on an "asis"
basis, without any warranties or conditions, express or implied, including, without limitation, any implied
warranties or conditions of non-infringement, merchantability or fitness for a particular purpose. You are not
required to provide support for your Contributions, except to the extent you desire to provide support.


**No Obligation.** You acknowledge that Get The Pet is under no obligation to use or incorporate your Contributions
into any of the Projects. The decision to use or incorporate your Contributions into any of the Projects will be
made at the sole discretion of Get The Pet or its authorized delegates.


**Disputes.** This Agreement shall be governed by and construed in accordance with the laws of the United Kingdom,
without giving effect to its principles or rules regarding conflicts of laws,
other than such principles directing application of UK law. The parties hereby submit to venue in, and
jurisdiction of the courts located in the UK for purposes relating to this Agreement. In the event
that any of the provisions of this Agreement shall be held by a court or other tribunal of competent jurisdiction
to be unenforceable, the remaining portions hereof shall remain in full force and effect.


**Assignment.** You agree that Get The Pet may assign this Agreement, and all of its rights, obligations and licenses
hereunder.



### Contribution Content Guidelines

These are some of the rules we try to follow:

-   Use variable naming conventions like in the other files you are seeing
-   No console.log() - use logging service
-   Run the linting code check and make it succeed
-   Comment your code where it gets non-trivial
-   Keep an eye on performance and memory consumption
-   Write relevant unit tests
-   Do not do any incompatible changes without discussion with the team, especially do not modify the name or behaviour of public API methods or properties

### How to contribute - the Process

1.  Make sure the change would be welcome (e.g. a bugfix or a useful feature); best do so by proposing it in a GitHub issue
2.  Create a branch forking the backend repository and do your change
3.  Commit and push your changes on that branch
4.  In the commit message
 - Describe the problem you fix with this change.
 - Describe the effect that this change has from a user's point of view. App crashes and lockups are pretty convincing for example, but not all bugs are that obvious and should be mentioned in the text.
 - Describe the technical details of what you changed. It is important to describe the change in a most understandable way so the reviewer is able to verify that the code is behaving as you intend it to.
5.  If your change fixes an issue reported at GitHub, add the following line to the commit message:
    - ```Fixes #(issueNumber)```
    - Do NOT add a colon after "Fixes" - this prevents automatic closing.
6.  Create a Pull Request
7.  Wait for our code review and approval, possibly enhancing your change on request
    -   Note that the Get The Pet developers also have their regular duties, so depending on the required effort for reviewing, testing and clarification this may take a while
9.  Once the change has been approved we will inform you in a comment
10.  We will close the pull request, feel free to delete the now obsolete branch
