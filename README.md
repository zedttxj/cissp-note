# CISSP Note
Notes for CISSP exam

Learn NIST 800-53 & 800-53a, ISO27001 & 27002, GDPR, CMMC (NIST
800-171), and NIST CSF. These are biggest frameworks/regulations you'll
come across. When it comes to NIST documents the "a" in it is the
assessment portion. So, for example the "how to" assess NIST 800-53 is
found in the -53a document. For ISO27001, the how to assess is found in
27002. I'd be happy to dive into more detail on them with you after the
break.

Optional Chapter (ESVF):

Chapter 1

1.  Alignment of Security Function to Business Strategy, Goals,
    Missions, and Objectives

    a.  Strategic Plan: is a long-term plan that is fairly stable. It
        > defines the organization's security purpose. It defines the
        > security function and aligns it to the goals, mission, and
        > objectives of the organization. It's useful for about five
        > years, if it's maintained and updated annually. The strategic
        > plan also serves as the planning horizon. Long-term goals and
        > visions for the future are discussed in a strategic plan. A
        > strategic plan should include a risk assessment.

    b.  Tactical Plan: the tacitical plan is a midterm plan developed to
        > provide more details on accomplishing the goals set forth in
        > the strategic plan, or can be crafted ad hoc based on
        > unpredicted events. A tactical plan is typically useful for
        > about a year and often prescribes and schedules the tasks
        > necessary to accomplish organizational goals. Some examples of
        > tactical plans are project plans, acquisition plans, hiring
        > plans, budget plans, maintenance plans, support plans, and
        > system development plans

    c.  Operational Plan: is a short-term, highly detailed plan based on
        > the strategic and tactical plans. It's valid or useful only
        > for a short time. Operational plans must be updated often
        > (such as monthly or quarterly) to retain compliance with
        > tactical plans. Operational plans spell out how to accomplish
        > the various goals of the organization. They include resource
        > allotments, budgetary requirements, staffing assignments,
        > scheduling, and step-by-step or implementation procedures.
        > Operational plans include details on how the implementation
        > processes are in compliance with the organization's security
        > policy. Examples of operational plans are training plans,
        > system deployment plans, and product design plans.

        **Top-down approach**: **Upper (or senior) management** is
        responsible for initiating and defining policies for the
        organization. Security policies provide direction for all levels
        of the organization's hierarchy. **Middle Management** flesh out
        the security policy into standards, baselines, guidelines, and
        procedures. The **operational managers** or **security
        processions** must then implement the configurations prescribed
        in the security management documentation. Finally, the **end
        users** must comply with all the security policies of the
        organization.

        **Bottom-up approach**: the IT staff makes security decisions
        directly without input from senior management. It's rarely used
        and is considered problematic in the IT industry.

        **Security management** is a responsibility of **upper
        management**, not the **IT staff**, and is considered an issue
        of business operations rather than IT administration. The
        information security (InfoSec) team should be led by a
        designated (CISO) who reports directly to senior management,
        such as the CIO, CEO, or the board of directors.

        Every security plan is **useless** without approval of senior
        management.

2.  Organizational Processes

    a.  Acquisitions and mergers place an organization at an increased
        > level of risk. Such risks include inappropriate information
        > disclosure, data loss, downtime, or failure to achieve
        > sufficient return on investment (ROI).

        Chapter 3

<!-- -->

1.  Project Scope and Planning

    a.  Perform a structured review of the business's organization from
        > a crisis planning point of view

        i.  Operational departments that are responsible for the core
            > services the business provides to its client

        ii. Critical support services, such as the IT department,
            > facilities and maintenance personnel, and other groups
            > responsible for the upkeep of systems that support the
            > operational departments

        iii. corporate security teams responsible for physical security,
             > since they are many times the first responders to an
             > incident and are also responsible for the physical
             > safeguarding of the primary facility and alternate
             > processing facility

        iv. senior executives and other key individuals essential for
            > the ongoing viability of the organization

    b.  Create a BCP team with the approval of senior management

        i.  representatives from each of the organization\'s departments
            > responsible for the core services performed by the
            > business

        ii. business unit team members from the functional areas
            > identified by the organizational analysis

        iii. IT subject-matter experts with technical expertise in areas
             > covered by the BCP

        iv. cybersecurity team members with knowledge of the BCP process

        v.  Physical security and facility management teams responsible
            > for the physical plant

        vi. attorneys familiar with corporate legal, regulatory, and
            > contractual responsibilities

        vii. human resources team members who can address staffing
             > issues and the impact on individual employees

        viii. public relations team members who need to conduct similar
              > planning for how they will communicate with stakeholders
              > and the public in the event of a disruption

        ix. senior management representatives with the ability to set
            > the vision, define priorities, and allocate resources

    c.  Assess the resources available to participate in business
        > continuity activities

        i.  **BCP Development** The BCP team will require some resources
            > to perform the four elements of the BCP process (project
            > scope and planning, business impact analysis, continuity
            > planning, and approval and implementation). It\'s more
            > than likely that the major resource consumed by this BCP
            > phase will be effort expended by members of the BCP team
            > and the support staff they call on to assist in the
            > development of the plan

        ii. **BCP Testing, Training, and Maintenance** The testing,
            > training, and maintenance phases of BCP will require some
            > hardware and software commitments. Still, once again, the
            > major commitment in this phase will be the effort of the
            > employees involved in those activities.

        iii. **BCP Implementation** When a disaster strikes and the BCP
             > team deems it necessary to conduct a full-scale
             > implementation of the business continuity plan, the
             > implementation will require significant resources. Those
             > resources include a large amount of effort (BCP will
             > likely become the focus of a large part, if not all, of
             > the organization) as well as direct financial expenses.
             > For this reason, the team must use its BCP implementation
             > powers judiciously yet decisively.

    d.  Analyze the legal and regulatory landscape that governs an
        > organization's response to a catastrophic event

        i.  Be sure to keep your attorneys involved throughout the
            > lifetime of your BCP, including the testing and
            > maintenance phases.

        ii. If your contracts include commitments to customers expressed
            > as service-level agreements (SLAs), you might find
            > yourself in breach of those contracts if a disaster
            > interrupts your ability to service your clients. Many
            > clients may feel sorry for you and want to continue using
            > your products/services, but their own business
            > requirements might force them to sever the relationship
            > and find new suppliers

2.  Business Impact Analysis

    a.  Quantitative Impact Assessment: To begin the quantitative
        > assessment, the BCP team should sit down and draw up a list of
        > organization assets and then assign an asset value (AV) in
        > monetary terms to each asset. The MTD is the maximum length of
        > time a business function can tolerate a disruption before
        > suffering irreparable harm. The recovery time objective (RTO)
        > for each business function is the amount of time in which you
        > think you can feasibly recover the function in the event of a
        > disruption. The recovery point objective (RPO) is the data
        > loss equivalent to the time-focused RTO. The RPO defines the
        > point in time before the incident where the organization
        > should be able to recover data.

    b.  Qualitative Impact Assessment: The BCP team must sit down and
        > discuss (preferably with the involvement of senior management)
        > qualitative concerns: Loss of goodwill among your client base,
        > Loss of employees to other jobs after prolonged downtime,
        > Social/ethical responsibilities to the community, and Negative
        > publicity. Qualitative concerns may justify elevating or
        > lowering the priority of risks that already exist on the
        > ALE-sorted quantitative list.

    c.  A full listing of risks facing your organization will require
        > input from all members of the BCP team. Be sure to gather
        > input from all parts of the organization, especially from any
        > areas not represented on the BCP team.

    d.  The risk identification portion of the process is purely
        > qualitative. At this point in the process, the BCP team should
        > not be concerned about the likelihood that each type of risk
        > will materialize or the amount of damage such an occurrence
        > would inflict upon the continued operation of the business.
        > The results of this analysis will drive both the qualitative
        > and quantitative portions of the remaining BIA tasks.

    e.  Remember that a contract is not normally sufficient due
        > diligence when choosing a cloud provider. You should also
        > verify that they have the controls in place to deliver on
        > their contractual commitments. Although it may not be possible
        > for you to physically visit the vendor\'s facilities to verify
        > their control implementation, you can always do the next best
        > thing-send someone else. The vendor may have already hired an
        > independent auditing firm to conduct an assessment of its
        > controls. They can make the results of this assessment
        > available to you in the form of a Service Organizational
        > Control (SOC) report.

3.  Continuity Planning

    a.  Strategy development: The BCP team must now take the prioritized
        > list of concerns raised by the quantitative and qualitative
        > resource prioritization exercises and determine which risks
        > will be addressed by the business continuity plan. Fully
        > addressing all the contingencies would require the
        > implementation of provisions and processes that maintain a
        > zero-downtime posture in the face of every possible risk. For
        > obvious reasons, implementing a policy this comprehensive is
        > impossible. The BCP team should look back to the MTD estimates
        > created during the early stages of the BIA and determine which
        > risks are deemed acceptable and which must be mitigated by BCP
        > continuity provisions.

    b.  Provisions and processes: 3 categories of assets must be
        > protected through this stage:

        i.  People: Management should provide team members with all the
            > resources they need to complete their assigned tasks.

        ii. Building/facilities

            1.  Hardening Provisions

            2.  Alternate Sites

        iii. Infrastructure: The BCP must address how the organization
             > will protect these systems against risks identified
             > during the strategy development phase. There are two main
             > methods of providing this protection:

             1.  Physically Hardening Systems

             2.  Alternative Systems

4.  Approval and Implementation

    a.  Plan Approval: If possible, you should attempt to have the plan
        > endorsed by the top executive in your business-the CEO,
        > chairperson, president, or similar business leader. It gives
        > more credibility the eyes of other senior managers, who might
        > otherwise brush it off as a necessary but trivial IT
        > initiative.

    b.  Plan Implementation

        i.  Start implementing the plan with a clear schedule

        ii. Make sure the plan is kept up to date

    c.  Training and Education

        i.  Everyone in the organization should receive at least a plan
            > overview briefing. These briefings provide employees with
            > the confidence that business leaders have considered the
            > possible risks posed to the continued operation of the
            > business and have put a plan in place to mitigate the
            > impact on the organization should a disruption occur.

        ii. Furthermore, at least one backup person should be trained
            > for every BCP task to provide redundancy in the event
            > personnel and injured or cannot reach the workplace during
            > an emergency.

    d.  BCP Documentation (by all BCP team member): to guide someone
        > else if the senior BCP team members are not present to guide
        > the effort, for historical record to understand the needs for
        > changes, and for "sanity check".

    e.  Continuity Planning Goals: First, the plan should describe the
        > goals of continuity planning as set forth by the BCP team and
        > senior management. These goals should be decided on at or
        > before the first BCP team meeting and will most likely remain
        > unchanged throughout the life of the BCP. Most common goal is
        > to ensure the continuous of the operation of the business in
        > the face of an emergency. Other goals may be added for
        > organizational needs.

    f.  Statement of Importance: The statement of importance reflects
        > the criticality of the BCP to the organization\'s continued
        > viability. This document commonly takes the form of a letter
        > to the organization\'s employees, stating the reason that the
        > organization devoted significant resources to the BCP
        > development process and requesting the cooperation of all
        > personnel in the BCP implementation phase. If you can put out
        > this letter under the signature of the CEO or an officer at a
        > similar level, the plan will carry tremendous weight as you
        > attempt to implement changes throughout the organization.

    g.  Statement of Priorities: When listing priorities, you should
        > also include a statement that they were developed as part of
        > the BCP process and reflect the importance of the functions to
        > continued business operations in the event of an emergency and
        > nothing more. Otherwise, the list of priorities could be used
        > for unintended purposes and result in a political turf battle
        > between competing organizations to the detriment of the
        > business continuity plan.

    h.  Statement of Organizational Responsibility: The statement of
        > organizational responsibility also comes from a senior-level
        > executive and can be incorporated into the same letter as the
        > statement of importance. It echoes the sentiment that
        > \"business continuity is everyone\'s responsibility!\"

    i.  Statement of Urgency and Timing: The statement of urgency and
        > timing expresses the criticality of implementing the BCP and
        > outlines the implementation timetable decided on by the BCP
        > team and agreed to by upper management. The wording of this
        > statement will depend on the actual urgency assigned to the
        > BCP process by your organization\'s leadership. Consider
        > including a detailed implementation timeline to foster a sense
        > of urgency.

    j.  Risk Assessment: Include the actual AV, EF, ARO, SLE, and ALE
        > figures in the quantitative analysis. Also, describe the
        > thought process behind the analysis to the reader. Keep in
        > mind that the assessment reflects a point-in-time evaluation.

    k.  Risk Acceptance/Mitigation: Business continuity planners should
        > resist these statements and ask business leaders to document
        > their risk acceptance decisions formally. If auditors later
        > scrutinize your business continuity plan, they will most
        > certainly look for formal artifacts of any risk acceptance
        > decisions made in the BCP process.

        i.  For risks that were deemed acceptable, it should outline the
            > reasons the risk was considered acceptable as well as
            > potential future events that might warrant a
            > reconsideration of this determination.

        ii. For risks that were deemed unacceptable, it should outline
            > the risk management provisions and processes put into
            > place to reduce the risk to the organization\'s continued
            > viability.

    l.  Vital Records Program: Sit down with functional leaders and ask,
        > \"If we needed to rebuild our organization today in a
        > completely new location without access to any of our computers
        > or files, what records would you need?\" (asking the team).
        > You should be able to identify the storage locations for each
        > document identified in your vital records inventory.

    m.  Emergency Response Guidelines: How the first employee to detect
        > an emergency react? These guidelines should include the
        > following:

        i.  Immediate response procedures

        ii. A list of the individuals to notify of the incident

        iii. Secondary response procedures that first responders should
             > take while waiting for the BCP team to assemble

    n.  Maintenance: The BCP documentation and the plan itself must be
        > living documents. The BCP team should not disband after the
        > plan is developed but should still meet periodically to
        > discuss the plan and review the results of plan tests to
        > ensure that it continues to meet organizational needs. Keep in
        > mind that drastic changes in an organization\'s mission or
        > resources may require going back to the BCP drawing board and
        > beginning again.

    o.  Testing and Exercises: The BCP documentation should outline a
        > formalized exercise program to ensure that the plan remains
        > current.

        Chapter 4

<!-- -->

1)  Criminal Law

    a.  Computer Fraud and Abuse Act, the Electronic Communications
        > Privacy Act, and the Identity Theft and Assumption Deterrence
        > Act (among others) provide criminal penalties for serious
        > cases of computer crime.

    b.  

2)  Civil Law

    a.  Civil laws form the bulk of the U.S. body of laws. They are
        > designed to provide for an orderly society and govern matters
        > that are not crimes but that require an impartial arbiter to
        > settle between individuals and organizations. Examples of the
        > types of matters that may be judged under civil law include
        > contract disputes, real estate transactions, employment
        > matters and estate/probate procedures.

    b.  Civil laws also are used to create the framework of government
        > that the executive branch uses to carry out its
        > responsibilities. These laws budgets for governmental
        > activities and lay out the authority granted to the executive
        > branch to create administrative laws.

    c.  Civil laws are enacted in the same manner as criminal laws. They
        > must pass through the legislative process before enactment and
        > are subject to the same constitutional parameters and judicial
        > review procedures. At the federal level, both criminal and
        > civil laws are embodied in the United States Code (USC).

3)  Administrative Law

    a.  Executive branch agencies have some leeway to enact
        > administrative law, in the form of executive orders, policies,
        > procedures, and regulations that govern the daily operations
        > of the agency. Administrative law is published in the Code of
        > Federal Regulations (CFR).

4)  Computer Crime

    Because of the global reach of the internet, most computer crimes
    cross state lines and, therefore, fall under federal jurisdiction
    and are prosecuted in the federal court system. However, in some
    circumstances, state laws can be more restrictive than federal laws
    and impose harsher penalties.

    a.  Computer Fraud and Abuse Act (CFAA):

        i.  Access classified information or financial information in a
            > federal system without authorization or in excess of
            > authorized privileges

        ii. Access a computer used exclusively by the federal government
            > without authorization

        iii. Use a federal computer to perpetrate a fraud (unless the
             > only object of the fraud was to gain use of the computer
             > itself)

        iv. Cause malicious damage to a federal computer system in
            > excess of \$1,000

        v.  Modify medical records in a computer when doing so impairs
            > or may impair the examination, diagnosis, treatment, or
            > medical care of an individual

        vi. Traffic in computer passwords if the trafficking affects
            > interstate commerce or involves a federal computer system

            The threshold of damage was raised to \$5,000:

<!-- -->

i.  Any computer used exclusively by the U.S. government

ii. Any computer used exclusively by a financial institution

iii. Any computer used by the government or a financial institution when
     > the offense impedes the ability of the government or institution
     > to use that system

iv. Any combination of computers used to commit an offense when they are
    > not all located in the same state

    National Information Infrastructure Protection Act of 1996:

    i.  Broadens the CFAA to cover computer systems used in
        > international commerce in addition to systems used in
        > interstate commerce

    ii. Extends similar protections to portions of the national
        > infrastructure other than computing systems, such as
        > railroads, gas pipelines, electric power grids, and
        > telecommunications circuits

    iii. Treats any intentional or reckless act that causes damage to
         > critical portions of the national infrastructure as a felony

    <!-- -->

    a.  Federal Sentencing Guidelines

        i.  The guidelines formalized the prudent person rule, which
            > requires senior executives to take personal responsibility
            > for ensuring the due care that ordinary, prudent
            > individuals would exercise in the same situation.

        ii. The guidelines allowed organizations and executives to
            > minimize punishment for infractions by demonstrating that
            > they used due diligence in the conduct of their
            > information security duties

        iii. The guidelines outlined three burdens of proof for
             > negligence: First, the person accused of negligence must
             > have a legally recognized obligation. Second, the person
             > must have failed to comply with recognized standards.
             > Finally, there must be a causal relationship between the
             > act of negligence and subsequent damages

    b.  Federal Information Security Management Act

        FISMA requires federal agencies implement an information
        security program that covers the agency\'s operations and
        government agencies include the activities of contractors in
        their security management programs. It replaces Computer
        Security Act of 1987 and Government Information Security Reform
        Act of 2000. NIST (responsible for developing the FISMA
        implementation guidelines) outlines the following elements for
        effective information security program:

        i.  Periodic assessments of risk, including the magnitude of
            > harm that could result from the unauthorized access, use,
            > disclosure, disruption, modification, or destruction of
            > information and information systems that support the
            > operations and assets of the organization

        ii. Policies and procedures that are based on risk assessments,
            > cost-effectively reducing information security risks to an
            > acceptable level and ensuring that information security is
            > addressed throughout the lifecycle of each organizational
            > information system

        iii. Subordinate plans for providing adequate information
             > security for networks, facilities, information systems,
             > or groups of information systems, as appropriate.

        iv. Security awareness training to inform personnel (including
            > contractors and other users of information systems that
            > support the operations and assets of the organization) of
            > the information security risks associated with their
            > activities and their responsibilities in complying with
            > organizational policies and procedures designed to reduce
            > these risks

        v.  Periodic testing and evaluation of the effectiveness of
            > information security policies, procedures, practices, and
            > security controls to be performed with a frequency
            > depending on risk, but no less than annually

        vi. A process for planning, implementing, evaluating, and
            > documenting remedial actions to address any deficiencies
            > in the information security policies, procedures, and
            > practices of the organization

        vii. Procedures for detecting, reporting, and responding to
             > security incidents

        viii. Plans and procedures to ensure continuity of operations
              > for information systems that support the operations and
              > assets of the organization

    c.  Federal Cybersecurity Laws of 2014

        The first of these was the confusingly named Federal Information
        Systems Modernization Act (also bearing the acronym FISMA). The
        2014 FISMA modified the rules of the 2002 FISMA by centralizing
        federal cybersecurity responsibility with the Department of
        Homeland Security. There are two exceptions to this
        centralization: defense-related cybersecurity issues remain the
        responsibility of the secretary of defense, and the director of
        national intelligence bears responsibility for
        intelligence-related issues.

        Second, Congress passed the Cybersecurity Enhancement Act, which
        charges NIST with responsibility for coordinating nationwide
        work on voluntary cybersecurity standards. NIST produces the 800
        series of Special Publications related to computer security in
        the federal government.

        The following are commonly used NIST standards:

        i.  NIST SP 800-53: Security and Privacy Controls for Federal
            > Information Systems and Organizations. This standard is
            > required for use in federal computing systems and is also
            > commonly used as an industry cybersecurity benchmark.

        ii. NIST SP-171: Protecting Controlled Unclassified Information
            > in Nonfederal Information Systems and Organizations.
            > Compliance with this standard\'s security controls (which
            > are quite similar to those found in NIST 800-53) is often
            > included as a contractual requirement by government
            > agencies. Federal contractors must often comply with NIST
            > SP 800-171

        iii. The NIST Cybersecurity Framework (CSF) is a set of
             > standards designed to serve as a voluntary risk-based
             > framework for securing information and systems.

    d.  Intellectual Property (IP)

        Many products depend on secret recipes or production
        techniques-take the legendary secret formula for Coca-Cola or
        KFC\'s secret blend of herbs and spices, for example.

        These intangible assets are collectively referred to as
        intellectual property (IP). We\'ll explore the laws surrounding
        the four major types of intellectual property-copyrights,
        trademarks, patents, and trade secrets.

        i.  Copyright and the Digital Millennium Copyright Act

            Eight board categories of works qualify for copyright
            protection:

            1.  Literary works

            2.  Musical works

            3.  Dramatic works

            4.  Pantomimes and choreographic works

            5.  Pictorial, graphical, and sculptural works

            6.  Motion pictures and other audiovisual works

            7.  Sound recordings

            8.  Architectural works

                There has been some question over whether copyrights can
                be extended to cover the \"look and feel\" of a software
                package\'s graphical user interface. If you will be
                involved in this type of issue, you should consult a
                qualified intellectual property attorney to determine
                the current state of legislation and case law.

                There\'s a formal procedure to obtain a copyright that
                involves sending copies of the protected work along with
                an appropriate registration fee to the U.S. Copyright
                Office. However, officially registering a copyright is
                not a prerequisite for copyright enforcement. Indeed,
                the law states that the creator of a work has an
                automatic copyright from the instant the work is
                created. If you can prove in court that you were the
                creator of a work (perhaps by publishing it), you will
                be protected under copyright law. Official registration
                merely provides the government\'s acknowledgment that
                they received your work on a specific date.

                Copyright ownership always defaults to the creator of a
                work. The exceptions to this policy are works for hire.
                For example, when an employee in a company\'s public
                relations department writes a press release, the press
                release is considered a work for hire. A work may also
                be considered a work for hire when it\'s made as part of
                a written contract declaring it as such.

                Current copyright law provides for a lengthy period of
                protection. Works by one or more authors are protected
                until 70 years after the death of the last surviving
                author. Works for hire and anonymous works are provided
                protection for 95 years from the date of first
                publication or 120 years from the date of creation,
                whichever is shorter.

                The Digital Millennium Copyright Act (DMCA) serves to
                bring U.S. copyright law into compliance with terms of
                two World Intellectual Property Organization (WIPO)
                treaties. The first major provision of the DMCA provides
                for penalties of up to \$1 million and 10 years in
                prison for repeat offenders. Nonprofit institutions such
                as libraries and schools are exempted from this
                provision.

                The DMCA also limits the liability of internet service
                providers (ISPs) when their circuits are used by
                criminals violating the copyright law. To qualify for
                this exemption, the service provider\'s activities must
                meet the following requirements (quoted directly from
                the Digital Millennium Copyright Act of 1998, U.S.
                Copyright Office Summary, December 1998):

<!-- -->

1.  The transmission must be initiated by a person other than the
    > provider

2.  The transmission, routing, provision of connections, or copying must
    > be carried out by an automated technical process without selection
    > of material by the service provider.

3.  The service provider must not determine the recipients of the
    > material

4.  Any intermediate copies must not ordinarily be accessible to anyone
    > other than anticipated recipients and must not be retained for
    > longer than reasonably necessary.

5.  The material must be transmitted with no modification to its
    > content.

    The DMCA also exempts activities of service providers related to
    system caching, search engines, and the storage of information on a
    network by individual users. However, in those cases, the service
    provider must take prompt action to remove copyrighted materials
    upon notification of the infringement.

    The DMCA spells out the application of copyright law principles to
    the streaming of audio and/or video content over the internet. The
    DMCA states that these uses are to be treated as \"eligible
    nonsubscription transmissions.\"

    i.  Trademarks

        If you use a trademark in the course of your public activities,
        you are automatically protected under any relevant trademark law
        and can use the TM symbol to show that you intend to protect
        words or slogans as trademarks. If you want official recognition
        of your trademark, you can register it with the United States
        Patent and Trademark Office (USPTO). This process generally
        requires an attorney to perform a due diligence comprehensive
        search for existing trademarks that might preclude your
        registration. The entire registration process can take more than
        a year from start to finish. Once you\'ve received your
        registration certificate from the USPTO, you can denote your
        mark as a registered trademark with the R symbol.

        \"Intent to use\" application is that you register a trademark
        that you intend to use but are not necessarily already using.

        The acceptance of a trademark application in the United States
        depends on these two main requirements:

        1.  The trademark must not be confusingly similar to another
            > trademark-you should determine this during your
            > attorney\'s due diligence search. There will be an open
            > opposition period during which other companies may dispute
            > your trademark application.

        2.  The trademark should not be descriptive of the goods and
            > services that you will offer. For example, \"Mike\'s
            > Software Company\" would not be a good trademark candidate
            > because it describes the product produced by the company.
            > The USPTO may reject an application if it considers the
            > trademark descriptive.

            In the United States, trademarks are granted for an initial
            period of 10 years and can be renewed for unlimited
            successive 10-year periods.

    ii. Patents

        Utility patents protect the intellectual property rights of
        inventors. They provide a period of 20 years from the time of
        the invention (from the date of initial application) during
        which the inventor is granted exclusive rights to use the
        invention (whether directly or via licensing agreements). At the
        end of the patent exclusivity period, the invention is in the
        public domain available for anyone to use.

        Patents have three main requirements:

        1.  The invention must be new. Inventions are patentable only if
            > they are original ideas.

        2.  The invention must be useful. It must actually work and
            > accomplish some sort of task.

        3.  The invention must not be obvious. You could not, for
            > example, obtain a patent for your idea to use a drinking
            > cup to collect rainwater. This is an obvious solution. You
            > might, however, be able to patent a specially designed cup
            > that optimizes the amount of rainwater collected while
            > minimizing evaporation.

            Patent Trolls: Some companies don\'t actually build anything
            or use the patents they own. Instead, they make money by
            suing other companies for using similar ideas. They just
            hold the patents to threaten legal action and get paid
            settlements.

    iii. Trade Secrets

         Two of the previously discussed intellectual property
         tools-copyrights and patents-could be used to protect this type
         of information, but with these two major disadvantages:

         1.  Filing a copyright or patent application requires that you
             > publicly disclose the details of your work or invention.
             > This automatically removes the \"secret\" nature of your
             > property and may harm your firm by removing the mystique
             > surrounding a product or by allowing unscrupulous
             > competitors to copy your property in violation of
             > international intellectual property laws.

         2.  Copyrights and patents both provide protection for a
             > limited period of time. Once your legal protection
             > expires, other firms are free to use your work at will
             > (and they have all the details from the public disclosure
             > you made during the application process!).

             There actually is an official process regarding trade
             secrets. By their nature you don\'t register them with
             anyone; you keep them to yourself. You must ensure that
             anyone who does have this type of access is bound by a
             nondisclosure agreement (NDA) that prohibits them from
             sharing the information with others and provides penalties
             for violating the agreement.

             Patent law doesn\'t provide adequate protection for
             computer software products. Copyright law protect only the
             actual text of the source code and doesn\'t prohibit others
             from rewriting your code in a different form and
             accomplishing the same objective.

             Economic Espionage Act of 1996 has these two major
             provisions:

             Anyone found guilty of stealing trade secrets from a U.S.
             corporation with the intention of benefiting a foreign
             government or agent may be fined up to \$500,000 and
             imprisoned for up to 15 years.

             Anyone found guilty of stealing trade secrets under other
             circumstances may be fined up to \$250,000 and imprisoned
             for up to 10 years.

    <!-- -->

    a.  Licensing

        Four common types of license agreements are in use today:

        i.  **Contractual license** agreements use a written contract
            > between the software vendor and the customer, outlining
            > the responsibilities of each. These agreements are
            > commonly found for high-priced and/or highly specialized
            > software packages.

        ii. **Shrink-wrap** licensing agreements are written on the
            > outside of the software packaging. They commonly include a
            > clause stating that you acknowledge agreement to the terms
            > of the contract simply by breaking the shrink-wrap seal on
            > the package

        iii. **Click-through** (also known as browser wrap) license
             > agreements are becoming more commonplace than shrink-wrap
             > agreements. In this type of agreement, the contract terms
             > are either written on the software box or included in the
             > software documentation. During the installation process,
             > you are required to click a button indicating that you
             > have read the terms of the agreement and agree to abide
             > by them. This adds an active consent to the process,
             > ensuring that the individual is aware of the agreement\'s
             > existences prior to installation.

        iv. **Cloud services** license agreements take click-through
            > agreements to the extreme. Most cloud services do not
            > require any form of written agreement and simply flash
            > legal terms on the screen for review. In some cases, they
            > may provide a link to legal terms and a check box for
            > users to confirm that they read and agree to the terms.
            > Most users, in their excitement to access a new service,
            > simply click their way through the agreement without
            > reading it and may unwittingly bind their entire
            > organization to onerous terms and conditions.

            Industry groups provide guidance and enforcement activities
            regarding software licensing. You can get more information
            from their websites. One major group is the Software
            Alliance.

    b.  Import/Export

        Two sets of federal regulations governing imports and exports
        are of particular interest to cybersecurity professionals:

        i.  The international Traffic in Arms Regulations (ITAR)
            > controls the export of items that are specifically
            > designated as military and defense items, including
            > technical information related to those items. The item
            > covered under ITAR appear on a list called the United
            > States Munitions List (USML), maintained in 22 CFR 121.

        ii. The Export Administration Regulations (EAR) cover a broader
            > set of items that are designed for commercial use but may
            > have military applications. Items covered by EAR appear on
            > the Commerce Control List (CCL) maintained by the U.S.
            > Department of Commerce. Notably, EAR includes an entire
            > category covering information security products.

    c.  Countries of Concern

        Currently, U.S. firms can export high-performance computing
        systems to virtually any country without receiving prior
        approval from the government. There are exceptions to this rule
        for countries designated by the Department of Commerce\'s Bureau
        of Industry and Security (BIS) as countries of concern based on
        the fact that they pose a threat of nuclear proliferation, they
        are classified as state sponsors of terrorism, or other
        concerns. These countries include North Korea, Sudan, and Syria.

    d.  Encryption Export Controls

        After a lengthy lobbying campaign by the software industry, the
        president directed the Commerce Department to revise its
        regulations to foster the growth of the American security
        software industry (it was treated like a weapon due to potential
        military purposes).

        Security software is now divided into \"retail\" and \"mass
        market\" categories.

        By regulation, this review should be completed within 30 days.
        Once approved, companies can export the software freely. In
        practice, government review often take longer than the 30-day
        legal deadline. Companies facing delays may either wait
        indefinitely or take the matter to court to force a decision.

    e.  Privacy

        The main source of this contention is that the Constitution\'s
        Bill of Rights does not explicitly provide for a right to
        privacy. However, this right has been upheld by numerous courts
        and is vigorously pursued by organizations such as the American
        Civil Liberties Union (ACLU).

        Europeans have also long been concerned with their privacy.

        i.  **Fourth Amendment** to the U.S. Constitution. It reads as
            > follows: The right of the people to be secure in their
            > persons, houses, papers, and effects, against unreasonable
            > searches and seizures, shall not be violated, and no
            > warrants shall issue, but upon probable cause, supported
            > by oath or affirmation, and particularly describing the
            > place to be searched, and the persons or things to be
            > seized.

        ii. **The Privacy Act of 1974** (later amended by the bellow
            > act) applies only to government agencies (not all
            > organizations): The Privacy Act mandates that agencies
            > maintain only the records that are necessary for
            > conducting their business and that they destroy those
            > records when they are no longer needed for a legitimate
            > function of government. It provides a formal procedure for
            > individuals to gain access to records the government
            > maintains above them and to request that incorrect records
            > be amended.

        iii. **Electronic Communications Privacy Act of 1986**: It
             > prohibits the interception or disclosure of electronic
             > communication and defines those situations in which
             > disclosure is legal (a fine of up to \$500 and a prison
             > term of up to five years).

        iv. **Communications Assistance for Law Enforcement Act (CALEA)
            > of 1994**: requires all communications carriers to make
            > wiretaps possible for law enforcement with an appropriate
            > court order.

        v.  **Economic Espionage Act of 1996**: extends the definition
            > of property to include proprietary economic information so
            > that the theft of this information can be considered
            > industrial or corporate espionage.

        vi. **Health Insurance Portability and Accountability Act of
            > 1996** (**HIPAA**, later amended by HITECH): Among the
            > provisions of HIPAA are privacy and security regulations
            > requiring strict security measures for hospitals,
            > physicians, insurance companies, and other organizations
            > that process or store private medical information about
            > individuals. HIPAA-covered entities that experience a data
            > breach must notify affected individuals of the breach and
            > must also notify both the secretary of health and human
            > services and the media when the breach affects more than
            > 500 individuals. Any relationship between a covered entity
            > and a business assocciate must be governed by a written
            > contract known as a business associate agreement (BAA).
            > Business associates are directly subject to HIPAA and
            > HIPAA enforcement actions.

        vii. **Health Information Technology for Economic and Clinical
             > Health Act of 2009: update privacy and security
             > requirements** (**HITECH**, implemented through the HIPAA
             > Omnibus Rule in 2013)

        viii. Data breach notification law (SB 1386) include: SSN,
              > Drier\'s license number, state identification card
              > number, credit or debit card number, bank account number
              > (including security code, access code, or password),
              > medical records, health insurance information.

        ix. Children\'s Online Privacy Protection Act of 1998 (COPPA):

            1.  Websites must have a privacy notice that clearly states
                > the type of information they collect and what it\'s
                > used for, including whether any information is
                > disclosed to third parties. The privacy notice must
                > also include contact information for the operators of
                > the site.

            2.  Parents must be provided with the opportunity to review
                > any information collected from their children and
                > permanently delete it from the site\'s records.

            3.  Parents must give verifiable consent to the collection
                > of information about children younger than the age of
                > 13 prior to any such collection. Exceptions in the law
                > allow websites to collect minimal information solely
                > for the purpose of obtaining such parental consent.

        x.  Gramm-Leach Bliley Act of 1999:

            Until the Gramm-Leach-Bliley Act (GLBA) became law in 1999,
            there were strict governmental barriers between financial
            institutions. GLBA somewhat realized the regulations
            concerning the services each organization could provide.
            When Congress passed this law, it realized that this
            increased latitude could have far-reaching privacy
            implications. Because of this concern, it included a number
            of limitations on the types of information that could be
            exchanged even among subsidiaries of the same corporation
            and required financial institutions to provide written
            privacy policies to all their customers.

        xi. USA PATRIOT Act of 2001

            Congress passed the Uniting and Strengthening America by
            Providing Appropriate Tools Required to Intercept and
            Obstruct Terrorism (USA PATRIOT) Act of 2001 in direct
            response to the September 11, 2001, terrorist attacks in New
            York City and Washington, DC.

            1.  Authorities can now get one warrant to monitor all
                > communications for a single person (including multiple
                > phones, computers, etc.)

            2.  The government can access detailed user activity data
                > using a subpoena, which is easier to get than a
                > wiretap.

            3.  The USA PATRIOT Act amends the Computer Fraud and Abuse
                > Act (yes, another set of amendments!) to provide more
                > severe penalties for criminal acts. The PATRIOT Act
                > provides for jail terms of up to 20 years and once
                > again expands the coverage of the CFAA.

        xii. Family Educational Rights and Privacy Act (FERPA)

             It grants certain privacy rights to students older than 18
             and the parents of minor students.

             1.  Parents/students have the right to inspect any
                 > educational records maintained by the institution on
                 > the student.

             2.  Parents/students have the right to request correction
                 > of records they think are erroneous and the right to
                 > include a statement in the records contesting
                 > anything that is not corrected.

             3.  Schools may not release personal information from
                 > student records without written consent, except under
                 > certain circumstances.

        xiii. Identity Theft and Assumption Deterrence Act

              In the past, the only legal victims of identity theft were
              the creditors who were defrauded. This act makes identity
              theft a crime against the person whose identity was stolen
              and provides severe criminal penalties (up to a 15-year
              prison term and/or a \$250,000 fine) for anyone found
              guilty of violating this law.

              If you\'re planning to monitor the communications of your
              employees, you should take reasonable precautions to
              ensure that there is no implied expectation of privacy.
              Here are some common measures to consider:

<!-- -->

1.  Clauses in employment contracts that state the employee has no
    > expectation of privacy while using corporate equipment

2.  Similar written statements in corporate acceptable use and privacy
    > policies

3.  Logon banners warning that all communications are subject to
    > monitoring

4.  Warning labels on computers and telephones warning of monitoring

    i.  European Union Privacy Law

        The European Union (EU) has served as a leading force in the
        world of information privacy, passing a series of regulations
        designed to protect individual privacy rights. These laws
        function in a comprehensive manner, applying to almost all
        individually identifiable information, unlike U.S. privacy laws,
        which generally apply to specific industries or categories of
        information

        1.  European Union Data Protection Directive (DPD)

            On October 24, 1995, the European Parliament passed a
            sweeping Data Protection Directive (DPD) outlining privacy
            measures that must be in place for protecting personal data
            processed by information systems. The directive went into
            effect three years later in October 1998, serving as the
            first broad-based privacy law in the world. The DPD required
            that all processing of personal data meet one of the
            following criteria:

            a.  Consent

            b.  Contract

            c.  Legal obligation

            d.  Vital interest of the data subject

            e.  Balance between the interests of the data holder and the
                > interests of the data subject

                The directive also outlined key rights of individuals
                about whom data is held and/or processed:

<!-- -->

1.  Right to access the data

2.  Right to know the data\'s source

3.  Right to correct inaccurate data

4.  Right to withhold consent to process data in some situations

5.  Right of legal action should these rights be violated

    The passing of the DPD forced organizations around the world, even
    those based outside Europe, to consider their privacy obligations
    due to transborder data flow requirements.

    1.  European Union General Data Protection Regulation (GDPR)

        The new law applies to all organizations that collect data from
        EU residents or process that information on behalf of someone
        who collects it (major difference from DPD). The key provisions
        of the GDPR include the following:

        a.  Lawfulness, fairness, and transparency says that you must
            > have a legal basis for processing personal information,
            > you must not process data in a manner that is misleading
            > or detrimental to data subjects, and you must be open and
            > honest about data processing activities.

        b.  Purpose limitation says that you must clearly document and
            > disclose the purposes for which you collect data and limit
            > your activity to disclosed purposes.

        c.  Data minimization says that you must ensure that the data
            > you process is adequate for your stated purpose and
            > limited to what you actually need for that purpose.

        d.  Accuracy says that the data you collect, create, or maintain
            > is correct and not misleading, that you maintain updated
            > records, and that you correct or erase inaccurate data.

        e.  Storage limitation says that you keep data only for as long
            > as it is needed to fulfill a legitimate, disclosed purpose
            > and that you comply with the \"right to be forgotten\"
            > that allows people to require companies to delete their
            > information if it is no longer needed.

        f.  Security says that you must have appropriate integrity and
            > confidentiality controls in place to protect data.

        g.  Accountability says that you must take responsibility for
            > actions you take with protected data and that you must be
            > able to demonstrate your compliance.

    2.  Cross-Border Information Sharing

        Organizations needing to conduct transfers between their
        subsidiaries have two options available for complying with EU
        regulations:

        a.  Organizations may adopt a set of standard contractual
            > clauses that have been approved for use in situations
            > where information is being transferred outside of the EU.
            > Those clauses are found on the EU website and are
            > available for integration into contracts.

        b.  Organizations may adopt binding corporate rules that
            > regulate data transfers between internal units of the same
            > firm. This is a very time-consuming process-the rules must
            > be approved by every EU member nation where they will be
            > used, to typically this path is only adopted by very large
            > organizations.

            Privacy Shield (now invalid) used to be an agreement between
            the U.S. and the EU to make data sharing easier. Companies
            had to prove they followed privacy rules to earn the
            \"Privacy Shield\". In 2020, the European Court of Justice
            struck it down in the Schrem II case.

            In some cases, conflicts arise between laws of different
            nations. For example, electronic discovery rules in the
            United States might require the production of evidence that
            is protected under GDPR. In those cases, privacy
            professionals should consult with attorneys to identify an
            appropriate course of action.

            The Asia-Pacific Economic Cooperation (APEC) publishes a
            privacy framework that incorporates many standard privacy
            practices, such as preventing harm, notice, consent,
            security, and accountability. This framework is used to
            promote the smooth cross-border flow of information between
            APEC member nations.

    <!-- -->

    i.  Canadian Privacy Law

        The Personal Information Protection and Electronic Documents Act
        (PIPEDA) is a national-level law that restricts how commercial
        businesses may collect, use, and disclose personal information.

        Generally speaking, PIPEDA covers information about an
        individual that is identifiable to that individual. The Canadian
        government provides the following examples of information
        covered by PIPEDA:

        1.  Race, national, or ethnic origin

        2.  Religion

        3.  Age

        4.  Marital status

        5.  Medical, education, or employment history

        6.  Financial information

        7.  DNA

        8.  Identifying numbers

        9.  Employee performance records

            The law excludes information that does not fit the
            definition of personal information, including the following
            examples provided by the Information Commissioner of Canada:

<!-- -->

1.  Information that is not about an individual, because the connection
    > with a person is too weak or far-removed

2.  Information about an organization such as a business

3.  Information that has been rendered anonymous, as long as it is not
    > possible to link that data back to an identifiable person

4.  Certain information about public servants such as their name,
    > position, and title

5.  A person\'s business contact information that an organization
    > collects, uses, or discloses for the sole purpose of communicating
    > with that person in relation to their employment, business, or
    > profession

    PIPEDA generally does not apply to nonprofit organizations,
    municipalities, universities, schools, and hospitals

<!-- -->

v.  State Privacy Laws

    The California Consumer Privacy Act (CCPA) is an excellent example
    of this principle in action. California passed this sweeping privacy
    law in 2018, modeling it after the European Union\'s GDPR.
    Provisions of the law went into effect in 2020, providing consumers
    with the following:

    1.  The right to know what information businesses are collecting
        > about them and how the organization uses and shares that
        > information

    2.  The right to be forgotten, allowing consumers to request that
        > the organization delete their personal information, in some
        > circumstances

    3.  The right to opt out of the sale of their personal information

    4.  The right to exercise their privacy rights without fear of
        > discrimination or retaliation for their use

<!-- -->

a)  Compliance

    PCI DSS has 12 main requirements.

<!-- -->

i.  Install and maintain a firewall configuration to protect cardholder
    > data.

ii. Do not use vendor-supplied defaults for system passwords and other
    > security parameters.

iii. Protect stored cardholder data.

iv. Encrypt transmission of cardholder data across open, public
    > networks.

v.  Protect all systems against malware and regularly update antivirus
    > software or programs.

vi. Develop and maintain secure systems and applications

vii. Restrict access to card holder data by business need-to-know.

viii. Identify and authenticate access to system components.

ix. Restrict physical access to cardholder data.

x.  Track and monitor all access to network resources and cardholder
    > data.

xi. Regularly test security systems and processes.

xii. Maintain a policy that addresses information security for all
     > personnel.

     Organizations that are not merchants but that store, process, or
     transmit credit card information on behalf of merchants must also
     comply with PCI DSS.

     Dealing with the many overlapping, and sometimes contradictory,
     compliance requirements facing an organization requires careful
     planning. Many organizations employ full-time IT compliance staff
     responsible for tracking the regulatory environment, monitoring
     controls to ensure ongoing compliance, facilitating compliance
     audits, and meeting the organization\'s compliance report
     obligations

     Organizations may be subject to compliance audits, either by their
     standard internal and external auditors or by regulators or their
     agents. Some regulations, such as PCI DSS, may require the
     organization to retain approved independent auditors to verify
     controls and provide a report directly to regulators.

     In addition to formal audits, organizations often must report
     regulatory compliance to a number of internal and external
     stakeholders. For example, an organization\'s board of directors
     (or, more commonly, that board\'s audit committee) may require
     periodic reporting on compliance obligations and status. Similarly,
     PCI DSS requires organizations that are not compelled to conduct a
     formal third-party audit to complete and submit a self-assessment
     report outlining their compliance status.

<!-- -->

b)  Contracting and Procurement

    The increased use of cloud services and other external vendors to
    store, process, and transmit sensitive information leads
    organizations to a new focus on implementing security reviews and
    controls in their contracting and procurement processes.

    These are some questions to cover during these vendor governance
    reviews:

<!-- -->

i.  What types of sensitive information are stored, processed, or
    > transmitted by the vendor?

ii. What controls are in place to protect the organization\'s
    > information?

iii. How is your organization\'s information segregated from that of
     > other clients?

iv. If encryption is relied on as a security control, what encryption
    > algorithms and key lengths are used? How is key management
    > handled?

v.  What types of security audits does the vendor perform, and what
    > access does the client have to those audits?

vi. Does the vendor rely on any other third parties to store, process,
    > or transmit data? How do the provisions of the contract related to
    > security extend to those third parties?

vii. Where will data storage, processing, and transmission take place?
     > If outside the home country of the client and/or vendor, what
     > implications does that have?

viii. What is the vendor\'s incident response process, and when will
      > clients be notified of a potential security breach?

ix. What provisions are in place to ensure the ongoing integrity and
    > availability of client data?

    Chapter 5: Protecting Security of Assets

    The Asset Security domain focuses on collecting, handling, and
    protecting information throughout its lifecycle. A primary step in
    this domain is classifying information based on its value to the
    organization. All follow-on actions vary depending on the
    classification. For example, highly classified data requires
    stringent security controls. In contrast, unclassified data uses
    fewer security controls.

<!-- -->

1.  Identifying and Classifying Information and Assets

    Organizations often include classification definitions within a
    security policy. Personnel then label assets appropriately based on
    the security policy requirements.

    a.  Sensitive data

        Sensitive data is any information that isn\'t public or
        unclassified. It can include confidential, proprietary,
        protected, or any other type of data that an organization needs
        to protect due to its value to the organization, or to comply
        with existing laws and regulations.

    b.  Personally Identifiable Information

        Personally identifiable information (PII) is any information
        that can identify an individual. National Institute of Standards
        and Technology (NIST) Special Publication (SP) 800-122 provides
        a more formal definition:

        Any information about an individual maintained by an agency,
        including

        i.  any information that can be used to distinguish or trace an
            > individual\'s identity, such as name, social security
            > number, date and place of birth, mother\'s maiden name, or
            > biometric records; and

        ii. any other information that is linked or linkable to an
            > individual, such as medical, educational, financial, and
            > employment information.

            Protection for personally identifiable information (PII)
            drives privacy and confidentiality requirements for rules,
            regulations, and legislation worldwide (especially in North
            America and the European Union). NIST SP 800-122, Guide to
            Protecting the Confidentiality of Personally Identifiable
            Information (PII), provides more information on how to
            protect PII. It\'s available from the NIST SP \*800 Series)
            download page.

    c.  Protected Health Information

        Protected health information (PHI) is any health-related
        information that can be related to a specific person. HIPAA
        mandates PHI protection. HIPAA provides a more formal definition
        of PHI:

        Health information means any information, whether oral or
        recorded in any form or medium, that-

        i.  is created or received by a heath care provider, health
            > plan, public health authority, employer, life insurer,
            > school or university, or health care clearinghouse; and

        ii. relates to the past, present, or future physical or mental
            > health or condition of any individual, the provision of
            > health care to an individual, or the past, present, or
            > future payment for the provision of health care to an
            > individual.

    d.  Proprietary Data

        Proprietary data refers to any data that helps an organization
        maintain a competitive edge. It could be software code it
        developed, technical plans for products, internal processes,
        intellectual property, or trade secrets.

2.  Defining Data Classifications

    Organizations typically include data classifications in their
    security policy or a data policy. The U.S. government provides clear
    definitions for these classifications. As you read them, note that
    the wording of each definition is close except for a few keywords.
    \*Top secret\* uses the phrase \"exceptionally grave damage,\"
    \*secret\* uses the phrase \"serious damage,\" and confidential uses
    \"damage\":

    a.  Top Secret The top secret label is \"applied to information, the
        > unauthorized disclosure of which reasonably could be expected
        > to cause exceptionally grave damage to the national security
        > that the original classification authority is able to identify
        > or describe.\"

    b.  Secret The secret label is \"applied to information, the
        > unauthorized disclosure of which reasonably could be expected
        > to cause serious damage to the national security that the
        > original classification authority is able to identify or
        > describe.\"

    c.  Confidential The confidential label is \"applied to information,
        > the unauthorized disclosure of which reasonably could be
        > expected to cause damage to the national security that the
        > original classification authority is able to identify or
        > describe.\"

    d.  Unclassified Within the United States, unclassified data is
        > available to anyone, though it often requires individuals to
        > request the information using procedures identified in the
        > Freedom of Information Act (FOIA).

        i.  There are additional subclassifications of unclassified,
            > such as for official use only (FOUO) and sensitive but
            > unclassified (SBU). Documents with these designations have
            > strict controls limiting their distribution. As an
            > example, the U.S. Internal Revenue Service (IRS) uses SBU
            > for individual tax records, restricting access to these
            > records.

            These classifications also apply to hardware assets. This
            includes any computing system or media that processes or
            holds this data.

            Nongovernmental organizations rarely need to classify their
            data based on potential damage to national security. Some
            nongovernmental organizations use labels such as Class 3,
            Class 2, Class 1, and Class 0. Other organizations use more
            meaningful labels such as confidential (or proprietary),
            private, sensitive, and public

    <!-- -->

    a.  Confidential or Proprietary As an example. attackers have
        > repeatedly attacked Sony, stealing more than 100 terabytes of
        > data, including full-length versions of unreleased movies.
        > These quickly showed up on file-sharing sites, and security
        > experts estimated that people downloaded these movies up to a
        > million times. The movie were proprietary, and the
        > organization might have considered it exceptionally grave
        > damage.

    b.  Private Many organizations label PII and PHI data as private.
        > It\'s also common to label internal employee data and some
        > financial data as private. As an example, the payroll
        > department of a company would have access to payroll data, but
        > this data is not available to regular employees.

    c.  Sensitive As an example, IT personnel within an organization
        > might have extensive data about the internal network,
        > including the layout, devices, operating systems, software,
        > Internet Protocol (IP) addresses, and more. If attackers have
        > easy access to this data, it makes it much easier for them to
        > launch attacks.

    d.  Public Although an organization doesn\'t protect the
        > confidentiality of public data, it does take steps to protect
        > its integrity.

        For the CISSP exam, remember that \"sensitive information\"
        typically refers to any information that isn\'t public or
        unclassified

        3\. Defining Asset Classifications

        A computer is processing top secret data, the computer should
        also be classified as a top secret asset.

        4\. Understanding Data States

    <!-- -->

    a.  Data at Rest system hard drives, solid-state drives (SSDs),
        > external USB drives, storage area networks (SANs), and backup
        > tapes. Strong symmetric encryption protects data at rest

    b.  Data in Transit A combination of symmetric and asymmetric
        > encryption protects data in transit

    c.  Data in Use It\'s important to flush these buffers when the data
        > is no longer needed. In some cases, it\'s possible for an
        > application to work on encrypted data using homomorphic
        > encryption

        5\. Determining Compliance Requirements

        Some organizations have created a formal position called a
        compliance officer. The person filling this role ensures that
        the organization is conducting all business activities by
        following the laws and regulations that apply to the
        organization. This starts by first determining everywhere the
        organization operates, and what compliance requirements apply.

        6\. Determining Data Security Controls

        Security administrators use the requirements defined in the
        security policy to identify security controls. For Table 5.1,
        the primary security control is strong encryption using AES 256.
        Administrators should identify methodologies, making it easy for
        employees to meet the requirements.

        Several software companies sell a range of products that
        organizations can use to automate these tasks. Users apply
        relevant labels to emails before sending them. These emails pass
        through a data loss prevention (DLP) server that detects the
        labels and applies the required protection.

        Any type of data that your organization wants to protect needs
        similar security definitions. For example, you should define
        requirements for data stored on assets such as servers, data
        backups stored onsite and offsite, and proprietary data.

        Additionally, IAM security controls help ensure that only
        authorized personnel can access resources. Chapter 13,
        \"Managing Identity and Authentication,\" and Chapter 14,
        \"Controlling and Monitoring Access,\" cover identity and access
        management security controls in more depth.

        7\. Establishing Information and Asset Handling Requirements

    <!-- -->

    a.  Data Maintenance

        Refers to ongoing efforts to organize and care for data
        throughout its lifetime.

        If an organization stores all sensitive data on one server, it
        is relatively easy to apply all the appropriate controls to this
        one server.

        Techniques such as air gaps ensure the two networks never
        physically touch each other: one network processes unclassified
        data only and another network processes classified data, for
        example. Additionally, the classified network can\'t access the
        internet, and internet attackers can\'t access it.

        There are times when personnel need to add data to the
        classified network (updates as an example):

        i.  One way is manual; personnel copy the data from the
            > unclassified network to a USB device and carry it to the
            > classified network.

        ii. Another method is to use a unidirectional network bridge
            > (data travel in only one direction).

        iii. A third method is to use a technical guard solution, which
             > is a combination of hardware and software placed between
             > the two networks. A guard solution allows properly marked
             > data to travel between the two networks.

    b.  Data Loss Prevention (DLP)

        DLP systems attempt to detect and block data exfiltration
        attempts. For example, imagine that your organization uses data
        classifications. A DLP system can scan files for these words and
        detect them.

        Pattern-matching DLP systems look for specific patterns. The DLP
        can look for this pattern and detect it. Cloud-based DLP systems
        can look for the same code words or strings.

        There are two primary types of DLP systems:

        i.  Network-Based DLP: Administrators place it on the edge of
            > the network to scan all data leaving the organization. The
            > DLP system will send an alert, such as an email to an
            > administrator. Cloud-based DLP is a subset of
            > network-based DLP.

        ii. Endpoint-Based DLP: An endpoint-based DLP can scan files
            > stored on a system as well as files sent to external
            > devices, such as printers. For example, an organization\'s
            > endpoint-based DLP can prevent users from copying
            > sensitive data to USB flash drives or sending sensitive
            > data to a printer. It\'s also possible to configure an
            > endpoint-based DLP system to regularly scan files (such as
            > on a file server) for files containing specific keywords
            > or patterns, or even for unauthorized file types, such as
            > MP3 files.

            Most DLP solutions also include discovery capabilities. The
            goal is to discover the location of valuable data within an
            internal network.

            As an example, a database server may include unencrypted
            credit card numbers. When the DLP discovers and reports this
            database administrators can ensure the numbers are
            encrypted. As another example, company policy may dictate
            that employee laptops do not contain any PII data. A DLP
            content discovery system can search these and discover any
            unauthorized data. Additionally, many content discovery
            systems can search cloud resources used by an organization.

    c.  Marking Sensitive Data and Assets

        Marking includes both physical and electronic marking and
        labels.

        i.  Physical labels remain on the system or media throughout its
            > lifetime.

        ii. Digital marks or labels can be including the classification
            > as a header or footer in a document or embed it as a
            > watermark. It can help DLP systems to detect. Some DLP
            > systems will also add metadata tags to the document when
            > they detect that the document is classified.

            Some organizations mandate specific desktop backgrounds on
            their computers. For example, a system used to process
            proprietary data might have a black desktop background with
            the word Proprietary in white and a wide orange border.

            In many secure environments, personnel also use labels for
            unclassified media and equipment. If the organization marks
            unclassified data, too, unlabeled media would be easily
            noticeable, and the user would view an unmarked tape with
            suspicion.

            Organizations often identify procedures to downgrade media.
            For example, if a backup tape includes confidential
            information, an administrator might want to downgrade the
            tape to unclassified. After administrator purge the tape,
            they can then downgrade it. It\'s rare to downgrade a
            system. In any event, approved procedures would need to be
            created to inform personnel what can be downgraded and what
            should be destroyed. It\'s often safer and easier just to
            purchase new media or equipment rather than follow through
            with the sanitization steps for reuse.

    d.  Handling Sensitive Information and Assets

        Handling refers to the secure transportation of media through
        its lifetime.

        A common occurrence is the loss of control of backup tapes.
        Backup tapes should be protected with the same level of
        protection as the data that they contain.

        Data stored in the cloud needs to be protected with the same
        level of protection with which it is protected on site. Amazon
        Web Services (AWS) Simple Storage Service (S3) is one of the
        largest cloud service providers. Data is stored in AWS buckets,
        which are like folders on Windows systems. Unfortunately, this
        concept eludes many AWS users. As an example, a bucket owned by
        THSuite, a cannabis retailer, exposed the PII of more than
        30,000 individuals in early 2020. Another example from 2020
        involved 900,000 before and after cosmetic surgery images and
        videos stored in an unsecured bucket.

        Chapter 17, \"Preventing and Responding to Incidents,\"
        discusses the importance of logging, monitoring, and auditing.
        These controls verify that sensitive information is handled
        appropriately before a significant loss occurs. If a loss does
        occur, investigators use audit trails to help discover what went
        wrong. Any incidents that occur because personnel didn\'t handle
        data appropriately should be quickly investigated and actions
        taken to prevent a reoccurrence.

    e.  Data Collection Limitation

        The guideline is clear. If the data doesn\'t have a clear
        purpose for use, don\'t collect it and store it. This is also
        why many privacy regulations mention limiting data collection.

    f.  Data Location

        Data location refers to the location of data backups or data
        copies. A best practice is to keep a backup copy on site and
        another backup copy off site. When using cloud storage for
        backups, some organizations may need to verify the location of
        the cloud storage to ensure it is in a separate geographical
        location.

    g.  Storing Sensitive Data

        Sensitive data should be stored in such a way that it is
        protected against any type of loss. Encryption methods prevent
        unauthorized entities from accessing the data even if they
        obtain databases or hardware assets.

        Additionally, environmental controls protect the media. This
        includes temperature and humidity controls such as heating,
        ventilation, and air-conditioning (HVAC) systems.

        The value of any sensitive data is much greater than the value
        of the media holding the sensitive data. It\'s cost-effective to
        purchase high-quality media, especially if the data will be
        stored for a long time, such as on backup tapes. Similarly, the
        purchase of high-quality USB flash drives with built-in
        encryption is worth the cost. Some of these USB flash drives
        include biometric authentication mechanisms using fingerprints,
        which provide added protection.

    h.  Data Destruction

        An organization\'s security policy or data policy should define
        the acceptable methods of destroying data based on the data\'s
        classification. For example, an organization may require the
        complete destruction of media holding highly classified data,
        but allow personnel to use software tools to overwrite data
        files classified at a lower level.

        NIST SP 800-88 Rev. 1, \"Guidelines for Media Sanitization,\"
        provides comprehensive details on different sanitization
        methods. Sanitization methods (such as clearing, purging, and
        destroying) help ensure that data cannot be recovered. Proper
        sanitization steps remove all sensitive data (like removing
        SSDs, CDs/DVDs, and USB drives) before disposing of a computer.

        Sanitization can also refer to using a trusted method to purge
        classified data from the media without destroying it.

    i.  Eliminating Data Remanence

        Data remanence is the data that remains on media after the data
        was supposedly erased (residual magnetic flux or slack space for
        example). It may includes any type of private and sensitive
        data.

        **Slack** space is the unused space within a disk cluster.
        Operating systems store files on hard disk drives in clusters,
        which are groups of sectors (the smallest storage unit on a hard
        disk drive). Imagine a cluster size of 4,096 bytes and a file
        size of 1,024 bytes. After storing the file, the cluster would
        have 3,072 bytes of slack space.

        Some operating systems fill this slack space with data from
        memory. That\'s why personnel should never process classified
        data on unclassified systems. Sophisticated users can also hide
        data within slack space using tools such as \`**bmap**\` (Linux)
        and \`slacker\` (Windows).

        Even when you use sophisticated tools to overwrite the media,
        traces of the original data may remain as less perceptible
        magnetic fields. This is like a ghost image that can remain on
        some older TV and computer monitors if the same data is
        displayed for long periods of time. Forensics experts and
        attackers have tools they can use to retrieve this data even
        after it has been supposedly overwritten. One way to remove data
        remanence is with a degausser. However, they are only effective
        on magnetic media. Degaussing SSDs won\'t remove data (SSDs use
        integrated circuitry instead of magnetic flux on spinning
        platters).

        Some SSDs include built-in erase commands to sanitize the entire
        disk, but unfortunately, these weren\'t effective on some SSDs
        from different manufacturers. The U.S. National Security Agency
        (NSA) requires the destruction of SSDs using an approved
        disintegrator. Approved disintegrators shred the SSDs to a size
        of 2 millimeters (mm) or smaller.

    j.  Common Data Destruction Methods

        i.  Erasing: In most cases, the deletion or removal process
            > removes only the directory or catalog link to the data.
            > The actual data remains on the drive.

        ii. Clearing (or Overwriting): a process of preparing media for
            > reuse and ensuring that the cleared data cannot be
            > recovered using traditional recovery tools

        iii. Purging: a more intense form of clearing. It provides a
             > level of assurance that the original data is not
             > recoverable using any known methods. Even though purging
             > is intended to remove all data remnants, it isn\'t always
             > trusted. For example, the U.S. government doesn\'t
             > consider any purging method acceptable to purge top
             > secret data. Some organizations donate or sell used
             > computer equipment rather than attempting to purge it.
             > They often remove and destroy storage devices that hold
             > sensitive data instead.

        iv. Degaussing: creates a strong magnetic field that erases data
            > on some media in a process called degaussing. We don\'t
            > recommend it. Degaussing a hard disk will normally destroy
            > the electronics used to access the data. Additionally,
            > someone could open the drive in a clean room and install
            > the platters on a different drive to read the data.
            > Degaussing doesn\'t affect optical CDs, DVDs, or SSDs.

        v.  Destruction: ensure that the media cannot be reused or
            > repaired and that data cannot be extracted from the
            > destroyed media. Methods of destruction include
            > incineration, crushing, shredding, disintegration, and
            > dissolving using caustic or acidic chemicals. You can
            > remove the platters in highly classified disk drives and
            > destroy them separately.

            Declassification involves any process that purges media or a
            system in preparation for reuse in an unclassified
            environment. Often, the efforts required to securely
            declassify media are significantly greater than the cost of
            new media for a less secure environment. **Instead** of
            taking the risk, many organizations choose not to declassify
            any media and instead destroy it when it is no longer
            needed.

    k.  Cryptographic Erasure (or cryptoshredding)

        If data is encrypted on a device, organizations can destroy both
        the encryption key and decryption key. You should use another
        method to overwrite the data. If the original encryption isn\'t
        strong, someone may be able to decrypt it without the key.
        Additionally, there are often backups of cryptographic keys, and
        if someone discovers a backup key, they can still access the
        data. When using cloud storage, cryptoshredding may be the only
        measure for secure deletion.

<!-- -->

8.  Ensuring Appropriate Data and Asset Retention

    Chapter 3, \"Business Continuity Planning,\" covers a vital records
    program, which can be referenced to identify records to retain.

    Records retention involves retaining and maintaining important
    information as long as it i needed and destroying it when it is no
    longer needed. Some laws and regulations (security policy or data
    policy) dictate the length of time that an organization should
    retain data. It must be identified by organizations even in the
    absence of external requirements.

    As an example, many organizations require the retention of all audit
    logs for a specific amount of time. These audit logs allow the
    organization to reconstruct the details of past security incidents.
    When an organization doesn\'t have a retention policy,
    administrators may delete valuable data earlier than management
    expects them to or attempt to keep data indefinitely. The longer an
    organization retains data, the more it costs in terms of media,
    locations to store it, and personnel to protect it.

    Retention Policies can reduce liabilities.

9.  Data Protection Methods

<!-- -->

a)  Encryption is a primary methods (discussed in the \"Understanding
    > Data States\").

b)  Digital Rights Management

    Here are some methods associated with DRM solutions:

<!-- -->

i.  DRM License: A license grants access to a product and defines the
    terms of use.

ii. Persistent Online Authentication: Persistent online authentication
    (also known as always-on DRM) requires a system to be connected with
    the internet to use a product.

iii. Continuous Audit Trail: tracks all use of a copyrighted product. It
     can detect abuse when combined with persistence such as concurrent
     use of a product simultaneously but in two geographically different
     locations.

iv. Automatic Expiration: Many products are sold on a subscription
    basis.

    Digital watermarks are sometimes placed within audio or video files
    using steganography. They don\'t prevent copying but can be used to
    detect the unauthorized copying of a file. They can also be used for
    copyright enforcement and prosecution. Similarly, metadata is
    sometimes placed into files to identify the buyer.

    People against DRM claim it isn\'t effective against people that
    want to bypass it but instead complicates the usage for legitimate
    users.

<!-- -->

c)  Cloud Access Security Broker (CASB)

    A CASB is software placed logically between users and cloud-based
    resources. It can be on-premises or within the cloud. It monitors
    all activity and enforces administrator-defined security policies.
    CASB can also log all access, monitor activity, and send alerts on
    suspicious activity. In general, any security controls that an
    organization has created internally can be replicated to a CASB
    (including any DLP functions implemented by an organization). CASB
    solutions can detect shadow IT (the use of IT resources without the
    approval or acknowledgement of the IT department) by collecting and
    analyzing logs from network firewalls and web proxies. Chapter 16,
    "Managing Security Operations," covers other cloud topics.

d)  Pseudonymization

    Pseudonymization refers to the process of using pseudonyms to
    represent other data. When pseudonymization is performed
    effectively, it can result in less stringent requirements that would
    otherwise apply under the EU GDPR, covered in Chapter 4. As an
    example, instead of including personal information such as the
    patient's name, address, and phone number, it could just refer to
    the patient as Patient 23456 in the medical record. The doctor's
    office still needs this personal information, and it could be held
    in another database linking it to the patient pseudonym (Patient
    23456).

    The GDPR refers to pseudonymization as replacing data with
    artificial identifiers.

e)  Tokenization

    In the past, credit card data has been intercepted and stolen at the
    POS system.

f)  Anonymization

    Anonymization is the process of removing all relevant data so that
    it is theoretically impossible to identify the original subject or
    person.

    Randomized masking can be an effective method of anonymizing data.
    Masking swaps data in individual data columns so that records no
    longer represent the actual data. However, the data still maintains
    aggregate values that can be used for other purposes, such as
    scientific purposes.

<!-- -->

10. Understanding Data Roles

    Different documentation refers to these roles a little differently.
    Some of the terms you may see match the terminology used in some
    NIST documents, and other terms match some of the terminology used
    in the EU GDPR.

    a.  Data Owners (or Organizational Owner)

        They have ultimate organizational responsibility for data. The
        owner can be CEO or a department head (DH).

        NIST SP 800-18 Rev. 1, "Guide for Developing Security Plans for
        Federal Information Systems," outlines the following
        responsibilities for the **information owner** (data owner in
        this case):

        i.  Establishes the rules for appropriate use and protection of
            > the subject data/information (rules of behavior)

        ii. Provides input to information system owners regarding the
            > security requirements and security controls for the
            > information system(s) where the information resides

        iii. Decides who has access to the information system and with
             > what types of privileges or access rights

        iv. Assists in the identification and assessment of the common
            > security controls where the information resides

            NIST SP 800-18 frequently uses the phrase "rules of
            behavior," which is effectively the same as an acceptable
            use policy (AUP). Both outline the responsibilities and
            expected behavior of individuals and state the consequences
            of not complying with the rules or AUP. Additionally,
            individuals are required to periodically acknowledge that
            they have read, understand, and agree to abide by the rules
            or AUP (with online electronic digital signature if
            necessary).

    b.  Asset Owners

        The asset own (or system owner) is the person who owns the asset
        or system that processes sensitive data. NIST SP 800-18 outlines
        the following responsibilities for the system owner:

        i.  Develops a system security plan in coordination with
            > information owners, the system administrator, and
            > functional end users

        ii. Maintains the system security plan and ensures that the
            > system is deployed and operated according to the
            > agreed-upon security requirements

        iii. Ensures that system users and support personnel receive
             > appropriate security training, such as instruction on
             > rules of behavior (or an AUP)

        iv. Updates the system security plan whenever a significant
            > change occurs

        v.  Assists in the identification, implementation, and
            > assessment of the common security controls.

            The system owner is typically the same person as the data
            owner, but it can sometimes be someone else, such as a
            different department head (DH). As an example, consider a
            web server used for ecommerce that interacts with a back-end
            database server. A software development department might
            perform database development and database administration for
            the database and the database server, but the IT department
            maintains the web server. In this case, the software
            development DH is the system owner for the database server,
            and the IT DH is the system owner for the web server.
            However, if software developers work within the IT
            department, the IT DH would be the system owner for both
            systems.

            The system owner is responsible for ensuring that data
            processed on the system remains secure. This includes
            identifying the highest level of data that the system
            processes. The system owner then ensures that the system is
            labeled accurately and that appropriate security controls
            are in place to protect the data. System owners interact
            with data owners to ensure that the data is protected while
            at rest on the system, in transit between systems, and in
            use by applications operating on the system.

            System and data owners are senior personnel within an
            organization. As a result, management teams typically
            include system and data owners. This is especially useful
            when a system has one owner for the system and another owner
            for the data.

    c.  Business/Mission Owners

        The business/mission owner role is viewed differently in
        different organizations. NIST SP 800-18 refers to the
        business/mission owner as a **program manager** or an
        **information system owner**. As such, the responsibilities of
        the business/mission owner can overlap with the responsibilities
        of the system owner or be the same role.

        Business owners might own processes that use systems managed by
        other entities. As an example, the sales department could be the
        business owner, but the IT department and the software
        development department could be the system owners for systems
        used in sales processes. Even though the sales department
        doesn't own these systems, it does own the **business
        processes** that generate sales using these systems, in which
        business owners have to make sure it brings value to the
        organization.

        Compare this with IT departments. If there are any successful
        attacks or data breaches, the fault is likely to fall on them.
        IT departments often recommend security controls or systems that
        don't add immediate value to the organization but reduce overall
        risks. The business owner is responsible for evaluating these
        recommendations and may decide that the potential loss related
        to the risks they eliminate is less than the loss of revenue
        they'll cause. The IT department doesn't generate revenue.
        Instead, it is a cost center generating costs. In contrast, the
        business side generates revenue as a profit center. Costs
        generated by the IT department may reduce risks, but they eat up
        profits generated by the business side.

    d.  Data Processors and Data Controllers

        Generically, a data processor is any system used to process
        data. However, in the context of the GDPR, **data processor**
        has a more specific meaning: "a natural or legal person, public
        authority, agency, or other body, which processes personal data
        solely on behalf of the data controllers." In this context, the
        **data controller** is the person or entity that controls the
        processing of the data: they decide what, why, and how to
        process these data.

        As an example, a company that collects personal information on
        employees for payroll is a data controller. If they pass this
        information to a third-party company to process payroll, the
        payroll company is the data processor. In this example, the
        payroll company must not use the data for anything other than
        process payroll at the direction of the data controller.

        The GDPR restricts data transfers to countries outside the EU.
        Companies (may face fines of up to 4% of their global revenue).
        Unfortunately, it is filled with legalese, presenting many
        challenges for organizations. As an example, clause 107 includes
        this single sentence statement:

        Consequently the transfer of personal data to that third country
        or international organisation should be prohibited, unless the
        requirements in this Regulation relating to transfers subject
        tot appropriate safeguards, including binding corporate rules,
        and derogations for specific situations are fulfilled.

        As a result, many organizations have created dedicated roles,
        such as a data privacy officer, to oversee the control of data
        and ensure the organization follows all relevant laws and
        regulations. The GDPR has mandated the role of a data protection
        officer for any organization that must comply with the GDPR. The
        person in this role is responsible for ensuring the organization
        applies the laws to protect individuals' private data.

    e.  Data Custodians

        Data owners often delegate day-to-day tasks to a data custodian.
        In practice, personnel within an IT department or system
        security administrators would typically be the custodians. They
        might be the same administrators responsible for assigning
        permissions to data.

    f.  Administrators

        Many organizations view anyone with elevated privileges as
        administrators. For example, help desk employees are granted
        some elevated privileges to perform their job but aren't granted
        full administrative privileges. They are sometimes referred to
        as administrators. In the context of data roles, a data
        administrator may be a data custodian or someone in another data
        role.

    g.  Users and Subjects

        A user is any person who accesses data via computing system to
        accomplish work tasks. You can also think of users as employees
        or end users (discussed further in Chapter 8, "Principles of
        Security Models, Design, and Capabilities," and Chapter 13.

        Subjects can be users, programs, processes, services, computers,
        or anything else that can access a resource.

        The GDPR defines a **data subject** as a person who can be
        identified through an identifier, such as a name, identification
        number, or other means. If a file includes PII on Sally Smith,
        Sally Smith is the data subject.

11. Using Security Baselines

    Chapter 16 covers imaging in the context of configuration management
    in more depth. As an introduction, administrators configure a single
    system with desired settings, capture it as an image, and then
    deploy the image to other systems. After deploying systems in a
    secure state, auditing processes periodically check the systems to
    ensure they remain in a secure state.

    NIST SP 800-53 Rev.5, "Security and Privacy Controls for Information
    Systems and Organizations," mentions security control baselines and
    identifies them as a set of minimum security controls defined for an
    information system. It stresses that a single set of security
    controls **does not** apply to all situations.

    NIST SP 800-53B, "Control Baselines for Information Systems and
    Organizations," includes a comprehensive list of security controls
    and has identified many of them to include in various baselines
    (four baselines based on the potential impact to an organization's
    mission if there is a loss of confidentiality, integrity, or
    availability of a system):

    a.  Low-Impact Baseline Controls in this baseline are recommended if
        > a loss of confidentiality, integrity, or availability will
        > have a low impact on the organization's mission.

    b.  Moderate-Impact Baseline Controls in this baseline are
        > recommended if a loss of confidentiality, integrity, or
        > availability will have a moderate impact on the organization's
        > mission.

    c.  High-Impact Baseline Controls in this baseline are recommended
        > if a loss of confidentiality, integrity, or availability will
        > have a high impact on the organization's mission.

    d.  Privacy Control Baseline This baseline provides an initial
        > baseline for any systems that process PII. Organizations may
        > combine this baseline with one of the other baselines.

        You would try to predict the impact of the compromise on the
        confidentiality, integrity, or availability of the system and
        any data it holds. If the impact is high, you would consider
        adding all the controls listed as high-impact in addition to the
        low-impact and moderate-impact controls. If the compromise would
        cause privacy data to be compromised, you would consider adding
        the security controls identified as privacy control baseline
        items to your baseline.

12. Comparing Tailoring and Scoping

    **Tailoring** refers to modifying the list of security controls
    within a baseline to align with the organization's mission. NIST SP
    800-53B formally defines it as "part of an organization-wide risk
    management process that includes framing, assessing, responding to,
    and monitoring information security and privacy risks" and indicates
    it includes the following activities:

    \- Identifying and designating common controls

    \- Applying scoping considerations

    \- Selecting compensating controls

    \- Assigning control values

    A selected baseline may not include commonly implemented controls.

    Imagine that a data center includes video cameras covering the
    external entry, the internal exit, and every row of servers, but the
    baseline only recommends a video camera cover the external entry.
    During the tailoring process, personnel will evaluate these extra
    cameras and determine if they are needed. They may decide to remove
    some to save costs or keep them.

    An organization might decide that a set of baseline controls applies
    perfectly to computers in their central location, but some controls
    aren't appropriate or feasible in a remote office location. As an
    example, imagine the account lockout policy is set to lock out users
    if they enter an incorrect password five times. In this example, the
    control value is 5, but the tailoring process may change it to 3.

    **Scoping** (part of the tailoring process) processes eliminate
    controls that are recommended in a baseline. For example, if a
    system doesn't allow any two people to log on to it simultaneously,
    there's no need to apply a concurrent session control.

13. Standards Selection

    Organizations need to ensure that the controls comply with external
    security standards. As an example, the PCI DSS defines requirements
    that organizations processing credit card transactions must follow.
    Similarly, organizations that collect or process data belonging to
    EU citizens must abide by the requirements in the GDPR.

    Chapter 16: Managing Security Operations-Provision Resources
    Securely

    An important consideration when provisioning resources securely is
    asset management. Chapter 13, "Managing Identity and
    Authentication," covers provisioning and deprovisioning for accounts
    as part of the identity and access provisioning lifecycle. This
    section focuses on resources such as hardware and software assets.

<!-- -->

1.  Information and Asset Ownership

    Data owners typically delegate data protection tasks to others in
    the organization. For example, employees in the data custodian
    security role typically perform daily tasks such as implementing
    access controls, performing backups, and managing data storage.

2.  Asset management

    **Tangible assets** include hardware and software assets owned by
    the company. **Intangible assets** include patents, copyrights, a
    company's reputation, and other assets representing potential
    revenue.

    Many organizations use an automated configuration management system
    (CMS) to help with hardware asset management. The primary purpose of
    a CMS is configuration management, discussed later in this chapter.
    The CMS needs to connect to hardware systems when checking
    configuration. The **CMS** needs to connect to hardware systems when
    checking configuration settings. While doing so, it verifies that
    the system is still in the network and turned on.

    a.  Hardware Asset Inventories

        Hardware assets are IT resources such as computers, servers,
        routers, switches, and peripherals. Many organizations use
        databases and inventory applications to perform inventories and
        track hardware assets through the entire equipment lifecycle.
        For example, bar-code systems are available that can print bar
        codes to place on equipment. The bar-code database includes
        relevant details on the hardware, such as the model, serial
        number, and location. When the hardware is purchased, it is
        bar-coded before it is deployed. On a regular basis, personnel
        scan all of the bar codes with a bar-code reader to verify that
        the organization still controls the hardware.

        A similar method uses radio frequency identification (RFID)
        tags. These tags transmit information to RFID readers. Personnel
        place the RFID tags on the equipment and use the RFID readers to
        inventory the equipment. RFID tags and readers are more
        expensive than bar codes and bar-code readers. However, RFID
        methods significanty reduce the time needed to perform an
        inventory.

        When equipment is at the end of its lifetime, it's easy for
        individuals to lose sight of the data that it contains, so using
        checklists to sanitize the system is often valuable. NIST
        800-88r1 and Chapter 5 have more information on procedures to
        sanitize drives.

        Portable media, such as USB drives, holding sensitive data is
        also managed as an asset.

    b.  Software Asset Inventories

        Software assets are operating systems and applications.
        Organizations pay for software, and license keys are routinely
        used to activate the software. The activation process often
        requires contracting a licensing server over the internet to
        prevent piracy. If the license keys are leaked outside the
        organization, it can invalidate the organization's use. It's
        also important to monitor **license compliance** to avoid legal
        issues.

        For example, an organization could purchase a license key for
        five software product installations but only install and
        activate one instance immediately. If the key is stolen and
        installed on four systems outside the organization, those
        activations will succeed. When the organization tries to install
        the application on internal systems, the activation will fail.
        Any type of license key is highly valuable to an organization
        and should be protected.

        Software licensing also refers to ensuring that systems do not
        have unauthorized software installed. Many tools are available
        that can inspect systems remotely to detect the system's
        details. This allows them to identify unauthorized software
        running on systems, and helps an organization ensure that it
        complies with software licensing rules.

    c.  Intangible Inventories

        These are intellectual assets (such as intellectual property,
        patents, trademarks, a company's reputation, and copyrights).

        The **senior management** team is typically the owner of these
        assets.

        As an example, imaging a company sells a product based on a
        patent. The revenue from these sales can be used to assign a
        value to the patent. Patents in the United States are valid for
        20 years, so this time frame can also be used when calculating
        the value. Failing to pay these fees can result in a loss of the
        patent, stressing the importance of tracking patents.

        Large organizations report the value of intangible assets on
        their balance sheets using generally accepted accounting
        principles (GAAP). This helps them review their intangible
        assets at least annually.

        Domain 3:

<!-- -->

1.  Research, implement and manage engineering processes using secure
    design principles

    a.  Threat Modeling

        Threat Modeling isn't meant to be a single event. Instead, it's
        meant to be initiated early in the design process of a system
        and continue throughout its lifecycle. For example, Microsoft
        uses a Security Development Lifecycle (SDL) with the motto of
        "Secure by Design, Secure by Default, Secure in Deployment and
        Communication" (known as SD3+C). It has two goals in mind with
        this processes: reducing the number of security-related design &
        coding defects and the severity of any remaining defects.

        **Defensive** approach: predicting threats and designing in
        specific defenses during the coding and crafting process.

        **Proactive** approach: integrated security solutions are more
        cost-effective and more successful than those shoehorned in
        later

        **Adversarial** approach (or threat hunting or **reactive**
        approach): takes place after a product has been created and
        deployed. This deployment could be in a test or laboratory
        environment or to the general marketplace. This technique of
        threat hunting is the core concept behind ethical hacking,
        penetration testing, source code review, and fuzz testing. This
        usually results in less effective security improvements (over
        defensive threat modeling) at the cost of potentially reducing
        functionality and user-friendliness.

        Identifying threats:

        i.  Focused on Assets

        ii. Focused on Attackers

        iii. Focused on Software

             Microsoft developed a threat categorization scheme known as
             the STRIDE threat model: Spoofing, Tampering, Repudiation,
             Information disclosure, Denial-of-service, and Elevation of
             privilege.

             Process for Attack Simulation and Threat Analysis (PASTA)
             is a seven-stage threat modeling methodology. It's a
             risk-centric approach that aims at selecting or developing
             countermeasures in relation the value of the assets to be
             protected.

<!-- -->

i.  Definition of the Objectives (DO) for the Analysis of Risks

ii. Definition of the Technical Scope (DTS)

iii. Application Decomposition and Analysis (ADA)

iv. Threat Analysis (TA)

v.  Weakness and Vulnerability Analysis (WVA)

vi. Attack Modeling & Simulation (AMS)

vii. Risk Analysis & Management (RAM)

     Visual, Agile, and Simple Threat (VAST) is a threat modeling
     concept that integrates threat and risk management into an Agile
     programming environment on a scalable basis.

     Determining and Diagramming Potential Attacks

     ![{958076D7-8EE8-4A29-B6C6-49E38DFC68DF}](media/image1.png){width="5.761805555555555in"
     height="3.673611111111111in"}

     Performing Reduction Analysis (decomposing the application, system,
     or environment):

<!-- -->

i.  Trust Boundaries: Any location where the level of trust or security
    > changes

ii. Dataflow paths: The movement of data between locations

iii. Input points: Locations where external input is received

iv. Privileged operations: Any activity (typically system changes or
    > altering security) that requires greater privileges than of a
    > standard user account or process.

    Prioritization and Response: DREAD ranking system: damage
    portential, reporducibility, exploitability, affected users, and
    discoverability.

    Supply chain risk management (SCRM) is the means to ensure that all
    of the vendors or links in the supply chain are reliable,
    trustworthy, reputable organizations that disclose their practices
    and security requirements to their business partners.

    The security requirements for new hardware, software, or services
    should always meet or exceed the security expected in the final
    product. This often requires a detailed review of SLAs, contracts,
    and actual performance. When a supply chain component provider is
    crafting software or providing a service (such as a cloud provider),
    then a service-level requirement (SLR) may need to be defined. An
    SLR is a statement of the expectations of service and performance
    from the product or service of a vendor. Often, an SLR is provided
    by the customer/client prior to the establishment of the SLA (which
    should incorporate the elements of the SLR if the vendor expects the
    customer to sign the agreement).

    The Principle of Least Privilege: states that subjects are granted
    only the privileges necessary to perform assigned work tasks and no
    more. Limiting and controlling privileges based on this concept
    protects confidentiality and data integrity. If users can modify
    only those data files that their work tasks require them to modify,
    it protects other files' integrity in the environment. However, the
    least privilege principle relies on the assumption that all users
    have a well-defined job description that peronnel understand.
    Without a specific job description, it's not possible to know what
    privileges users need.

    Separation of Duties (SoD) and responsibilities:

<!-- -->

i.  Two-Person control (two-man rule): requires the approval of two
    > individuals for critical tasks. **Split knowledge** combines the
    > concepts of separation of duties and two-person control into a
    > single solution.

ii. Job Rotation: act as a deterrent and a detection machanism. If
    > employees choose to take part in fraudulent activities so anyway,
    > individuals taking over the job responsibilities later are likely
    > to discover the fraud.

iii. Mandatory vacations: This provides a form of peer review and helps
     > detect fraud and collusion.

     a.  Shared responsibility: indicates that organizations don't
         > operate in isolation.

         i.  Everyone in an organization has some level or security
             > responsibility. It's the job of the CISO and security
             > team to establish security and maintain it. It's the job
             > of the regular employees to perform their tasks within
             > the confines of security. It's the job of the auditor to
             > monitor the environment for violations.

         ii. Organizations are responsible to their stakeholders to make
             > good security decisions in order to sustain the
             > organization.

         iii. When working with third parties, especially with cloud
              > providers, each entity needs to understand their portion
              > of the shared responsibility of performing work
              > operations and maintaining security (discussed in
              > Chapter 16)

         iv. Responsibly disclose new vulnerabilities and threats to the
             > proper vendor or to an **information sharing center**
             > (threat intelligence source or service). **Automated
             > indicator sharing** (AIS) facilitate free exchange of
             > indicators of compromise (**IoCs**) and other cyberthreat
             > information between the U.S. federal government and the
             > private sector. It makes full use of Structured Threat
             > Information eXpression (**STIX**) and Trusted Automated
             > eXchange of Intelligence Information (**TAXII**) to share
             > threat indicators (IoCs). AIS is managed by the National
             > Cybersecurity and Communications Integration Center
             > (NCCIC).

<!-- -->

2.  Assess and mitigate the vulnerabilities of security architectures,
    designs, and solution elements.

    a.  Shared Responsibility with Cloud service Models

        ![{E23DCD0A-F44D-4929-A483-4B657EF53B68}](media/image2.png){width="5.767361111111111in"
        height="2.7430555555555554in"}

        i.  Software as a Service (SaaS): SaaS models provide fully
            > functional applications typically accessible via web
            > browser. For example, Gmail is an SaaS application. The
            > vendor (Google in this example) is responsible for all
            > maintenance of the SaaS services.

        ii. Platform as a Service (Paas): PaaS models provide consumers
            > with a computing platform, including hardware, operating
            > systems, and a runtime environment (including programming
            > languages, libraries, services, and other tools supported
            > by the vendor. Customers deploy applications that they've
            > created or acquired, manage their applications, and
            > possibly modify some configuration settings on the host.
            > However, the vendor is responsible for maintenance of the
            > host and the underlying cloud infrastructure.

        iii. Infrastructure as a Service (IaaS).

             NIST SP 800-145, The NIST Definition of Cloud Computing,
             provides standard definitions for many cloud-based
             services. NIST SP 800-144, Guidelines on Security and
             Privacy in Public Cloud Computing, provides in-depth
             details on security issues related to cloud-based
             computing.

             The four cloud deployment models available are as follows:

<!-- -->

i.  A **public cloud** model includes assets available for any consumers
    > to rent or lease and is hosted by an external CSP.

ii. The **private cloud** deployment model is used for cloud-based
    > assets for a single organization. Organizations can create (and
    > also hold responsibility for) and host private clouds using their
    > own on-premises resources. Maintenance requirements are typically
    > split based on the service model (SaaS, PaaS, or IaaS).

iii. A **community cloud** deployment model provides cloud-based assets
     > to two or more organizations that have a shared concern, such as
     > similar mission, security requirements, policy, or compliance
     > considerations. Maintenance responsibilities are shared based on
     > who is hosting the assets and the service models.

iv. A **hybrid cloud** model includes a combination of two or more
    > clouds that are bound together by a technology that provides data
    > and application portability. Maintenance responsibilities are
    > similar to a community cloud model.

    a.  Cryptographic system

        i.  Asymmetric Cryptography: RSA (was once patent),
            > Merkle-Hellman Knapsack (proven ineffective when it was
            > broken in 1984), ElGamal (wasn't patent but has a major
            > disadvantage: the algorithm doubles the size of any
            > message that it encrypts), Elliptic Curve (3,072-bit RSA
            > key is cryptographically equivalent to a 256-bit elliptic
            > curve cryptosystem key)

        ii. Symmetric Cryptography: AES...

        iii. Hash: Numberous hashing algorithms are not addressed on the
             > exam, but in addition to SHA (cryptanalytic attacks
             > demonstrated that there are weakenesses in the SHA-1
             > algorithm, and therefore, NIST deprecated SHA-1 and web
             > browsers dropped support for SHA-1 in 2017), MD5, RIPEMD,
             > and HMAC, you should recognize HAVAL. Hash of Variable
             > Length (HAVAL) is a modification of MD5. HAVAL uses
             > 1,024-bit blocks and produces hash values of 128, 160,
             > 192, 224, and 256 bits.

             1.  SHA-1 produces a 160-bit message digest by processing a
                 > message in 512-bit block size.

             2.  SHA-2 has 4 variant: SHA-256 and SHA-224 produce a
                 > 256-bit and 224-bit message, respectively, by
                 > processing a message in 512-bit block size. SHA-512
                 > and SHA-384 produce a 512-bit and 384-bit message,
                 > respectively, by processing a message in 1024-bit
                 > block size.

             3.  In 2015, the federal government announced the release
                 > of the Keccak algorithm as the SHA-3 standard, which
                 > is slower than and provides the same level of
                 > security as SHA-2.

             4.  MD2 (secure hash function for 8-bit processors), MD4
                 > (for 32-bit processors), and MD5 (use 4 distinct
                 > rounds of computation and has the same padding
                 > requirements as MD4-the message length must be 64
                 > bits less than a multiple of 512 bits) are subjected
                 > to cryptanalytic attacks.

             5.  RIPEMD (128-bit digest), RIPEMD-128, and RIPEMD-160
                 > (most commonly used of the RIPEMD variants and
                 > produces a 160-bit hash value) are used in Bitcoin
                 > cryptocurrency implementations. RIPEMD-256 and
                 > RIPEMD-320 have the same level of security as
                 > RIPEMD-128 and RIPEMD-160, respectively.

                 Digital Signatures has two distinct goals: enforcing
                 non-repudiation and integrity. Additionally, software
                 vendors often use digital signature technology to
                 authenticate code distributions that you download from
                 the internet, such as applets and software patches.
                 Meanwhile, the hashed message authentication code
                 (HMAC) algorithm implements a partial digital
                 signature-it guarantees the integrity of a message
                 during transmission, but it doesn't provide for
                 non-repudiation.

                 Digital Signature **Standard**: The NIST specifies the
                 digital signature algorithms acceptable for federal
                 government use in Federal Information Processing
                 Standard (FIPS) 186-4, also known as the Digital
                 Signature Standard (DSS). This document specifies that
                 all federall y approved digital signature algorithms
                 must use the SHA-3 hashing functions. There are 3
                 currently approved standard encryption algorithms:

                 \- The DSA as specified in FIPS 186-4. This algorithm
                 is a variant of an algorithm developed by Dr. Taher
                 Elgamal.

                 \- The RSA algorithm, as specified in ANSI X9.31

                 \- The Elliptic Curve DSA (ECDSA), as specified in ANSI
                 X9.62.

                 \- The FIPS 186-5 remains in draft form. The draft
                 proposal removes DSA as an approved algorithm, retains
                 RSA and ECDSA, and adds the Edwards-Curve DSA (EdDSA)
                 to DSS.

    b.  PKI

        i.  Certificates:

            Before the TLS handshake: You, as the server, need to
            request and receive a certificate from the CA by submitting
            a CSR. Digital certificates (signed by a trusted CA) that
            conform to X.509 contain the following data:

            1.  Version of X.509 to which the certificate conforms.

            2.  Serial number (from the certificate creator)

            3.  Signature algorithm identifier (specifies the technique
                > used by the certificate authority to digitally sign
                > the contents of the certificate)

            4.  Issuer name (identification of the certificate authority
                > that issued the certificate)

            5.  Validity period (specifies the dates and times-a
                > starting data and time and an expiration data and
                > time-during which the certificate is valid)

            6.  Subject's name (contains the common name \[CN\] of the
                > certificate as well as the distinguished name \[DN\]
                > of the entity that owns the public key contained in
                > the certificate)

            7.  Subject's public key (the meat of the certificate-the
                > actual public key the certificate owner used to set up
                > secure communications).

                Certificates may be issued for a variety of purposes.
                These include providing assurance for the public keys of

                \- Computers/machines

                \- Individual users

                \- Email addresses

                \- Developers (code-signing certificates).

                Some major CAs: Symantec, IdenTrust, AWS, GlobalSign,
                Comodo, Certum, GoDaddy, DigiCert, Secom, Entrust,
                Actalis, Trustwave.

                If you configure your browser to trust a CA, it will
                automatically trust all of the digital certificates
                issued by that CA. Browser developers pre-configure
                browsers to trust the major CAs to avoid placing this
                burden on users. "Let's Encrypt!" is a well-known CA
                because they offer free certficates in an effort to
                encourage the use of encryption.

                Registration authorities (RAs) assist CAs with the
                burden of verifying users' identities prior to issuing
                digital certificates.

                CA must carefully protect their own private keys to
                preserve their trust relationships. They often use an
                **offline** CA to protect their **root certificate**,
                the top-level certificate for their entire PKI. This
                offline CA is disconneted from networks and powered down
                until it is needed.

                In the CA trust model, the use of a series of
                intermediate CAs is known as **certificate chaining**.
                CAs don't need to be third-party service providers. Many
                organizations operate internal CAs that provide
                self-signed certificates for use inside an organization.
                These certificates won't be trusted by the browsers of
                external users.

                Certificate Lifecycle:

        ii. Enrollment: The simplest, and most common, certificates are
            > Domain Validation (DV) certificates, where the CA simply
            > verifies that the certificate subject has control of the
            > domain name. Extended Validation (EV) certificates provide
            > a higher level of assurance and the CA takes steps to
            > verify that the certificate owner is a legitimate business
            > before issuing the certificate.

        iii. Verification: when you receive a digital certificate from
             > someone (typically the start of the TLS handshake) with
             > whom you want to communicate, you verify the certificate
             > by checking the CA's digital signature using the CA's
             > public key. Finally, you must check and ensure that the
             > certificate was not revoked using a certificate
             > revocation list (**CRL**) or the Online Certificate
             > Status Protocol (**OCSP**). In 2017, Google announced
             > that the Chrome browser would no longer trust Symantec
             > certificates. A series of seemingly small lapses in
             > procedure can decimate a CA's business.

        iv. Revocation: It may occur for one of the following reasons:
            > the certificate was compromised, the certificate was
            > erroneously issued, the details of the certificate
            > changed, and the security association changed. The primary
            > issue with OCSP is that it places a significant burden on
            > the OCSP servers operated by CAs. **Certificate stapling**
            > is an extension to the OCSP that relieves some of the
            > burden placed on certificate authorities by the original
            > protocol. In certificate stapling, the web server contacts
            > the OCSP server itself and receives a signed and
            > timestamped response from the OCSP server, which it then
            > attaches, or staples, to the digital certificate. Then,
            > when a user requests a secure web connection, the web
            > server sends the certificate with the stapled OCSP
            > response to the user. It's common to have stapled
            > certificates with a validity period of 24 hours.

            Certificate Formats:

            1.  The most common binary format is the Distinguished
                > Encoding Rules (DER) format, which has .der, .crt, or
                > .cer extension.

            2.  The Privacy Enhanced Mail (PEM) certificate format is an
                > ASCII text version of the DER format. PEM certificates
                > are normally stored in files with the .pem or .crt
                > extension

            3.  The Personal Information Exchange (PFX) format is
                > commonly used by Windows systems. PFX certificates may
                > be stored in binary form, using either .pdx or .p12
                > file extensions. Windows systems also use P7B
                > certificates, which are stored in ASCII text format.

    c.  Asymmetric Key Management

        i.  "Security through obscurity" (**STO**, protecting data by
            > hiding the details) is not an appropriate approach. Be
            > wary of systems that use a "**black-box**" (focusing only
            > inputs and outputs instead of internal) approach and
            > maintain that the secrecy of their algorithm is critical
            > to the integrity of the cryptosystem.

        ii. If you don't have a formal policy that you must follow,
            > select an appropriate interval based on the frequency with
            > which you use your key. You might want to change your key
            > pair every few months, if practical.

        iii. Back up your key! You may want to either create your own
             > backup or use a key escrow service that aintains the
             > backup for you. Talking about backing up the keys,
             > cryptoshredding is the only way to destroy cloud storage.

        iv. Hardware security modules (**HSMs**) also provide an
            > effective way to manage encryption keys. These hardware
            > devices store and manage encryption keys in a secure
            > manner that prevents humans from ever needing to work
            > directly with the keys. Many of them are also capable of
            > improving the efficiency of cryptographic operations, in a
            > process known as **hardware acceleration**. HSMs range in
            > scope and complexity from very simple devices, such as the
            > YubiKey (storing encrypted keys on a USB drive for
            > personal use). HSMs include tamper-resistance mechanisms
            > to prevent someone who gains physical access to the device
            > form accessing the cryptographic material it maintains.
            > There's also could-based HSMs that provide secure key
            > management for IaaS services.

    d.  Hybrid Cryptography: combines symmetric and asymmetric
        > cryptography to achieve the key distribution benefits of
        > asymmetric cryptosystems with the speed of symmetric
        > algorithms. These approaches work by setting up an initial
        > connection between two communicating entities using asymmetric
        > cryptography. That connection is used for only one purpose:
        > the exchange of a randomly generated shared secrety key, known
        > as an **ephemeral key**. The two parties then exchange
        > whatever data they wish using the shared secret key with a
        > symmetric algorithm.

    e.  Applied Cryptography

        i.  Portable devices: Current versions of popular operating
            > systems now include disk encryption capabilities that make
            > it easy to apply and manage encryption on portable
            > devices. For example, Microsoft Windows includes the
            > **BitLocker** and Encrypting File System (**EFS**)
            > technologies, macOS includes **FileVault** encryption, and
            > the **VeraCrypt** open source package allows the
            > encryption of disks on Linux, Windows, and Mac systems.

        ii. The Trusted Platform Module (**TPM**) is a chip that resides
            > on the motherboard of the device. The TPM serves a number
            > of purposes, including the storage and management of keys
            > used for full-disk encryption (**FDE**) solutions. The TPM
            > provides the operating system with access to the keys only
            > if the user successfully authenticates, preventing someone
            > from removing the drive to place it into another device.
            > Don't forget about smartphones when developing your
            > portable device encryption policy. Most major smartphone
            > and tablet platforms include enterprise-level
            > functionality that supports encryption of data stored on
            > the phone

        iii. Email: If you need confidentiality when sending an email
             > message, encrypt the message. If your message must
             > maintain integrity, you must hash the message. If your
             > message needs authentication, integrity, and/or
             > non-repudiation, you should digitally sign the message.
             > If your message requires confidentiality, integrity,
             > origin authentication, and non-repudiation, you should
             > encrypt and digitally sign the message. You'll find more
             > coverage of email security topics in Chapter 12, "Secure
             > Communications and Network Attacks."

             1.  Phil Zimmerman's Pretty Good Privacy (**PGP**) secure
                 > email system appeared on the computer security scene
                 > in 1991. It combines the CA hierarchy described
                 > earlier in this chapter with the "web of trust"
                 > concept-that is, you must become trusted by one or
                 > more PGP users to begin using the system. The most
                 > difficult obstruction was the U.S. government export
                 > regulations, which treated encryption technology as
                 > munitions and prohibited the distribution of
                 > encryption technology outside the US. Fortunately,
                 > this restriction has since been repealed. PGP is
                 > availabe in two versions: the commercial product that
                 > is now sold by Symantec and an open source variant
                 > called OpenPGP. These products allow for the use of
                 > modern encryption algorithms, hash functions, and
                 > signature standards within the PGP framework.

             2.  S/MIME: The Secure/Multipurpose Internet Mail
                 > Extensions (S/MIME) protocol uses the RSA encryption
                 > algorithm and has received the back of major industry
                 > players, including **RSA Security**. It has already
                 > been incorporated in **Microsoft Outlook and Office
                 > 265, Apple Mail,** and **Google G Suite Enterprise
                 > edition**. S/MINE relies on the use of X.509
                 > certificates.

        iv. Web Applications: Over the years, security researchers
            > discovered a number of critical flaws in the SSL protocol
            > that render it insecure for use today. However, SSL serves
            > as the technical foundation for its successor, TLS, which
            > remains widely used today. Cipher suites are usually
            > expressed in long strings that combine each of the four
            > combinations of encryption algorithms (for example,
            > TLS_DH_RSA_WITH_AES_256_CBC_SHA384). You may also see
            > cipher suites that use DHE or ECDHE. The "E" indicates the
            > algorithm uses different, ephemeral keys for each
            > communication to provide forward secrecy and reduce the
            > likelihood of key compromise. The "E" versions of these
            > algorithms provide added security, but this comes at the
            > cost of added computational complexity.

        v.  Tor and the Dark Web: Tor (formerly known as The Onion
            > Router) provides a mechanism for anonymously routing
            > traffic across the internet using encryption and a set of
            > relay nodes. It relies o a technology known as **perfect
            > forward secrecy**.

        vi. Steganography and Watermarking: It's also possible to embed
            > messages inside larger excerpts of text. Steganography
            > techniques are often used for illegal activities, such as
            > espionage and child pornography. Adding digital watermarks
            > to documents to protect intellectual property is
            > accomplished by means of steganography. If there's an
            > unauthorized copy of the content, the watermark can be
            > used to detect the copy and trace the offending copy back
            > to the source.

        vii. Networking:

             1.  Circuit Encryption: Security administrators use two
                 > types of encryption techniques to protect
                 > data-in-transit: **Link encryption** (creating a
                 > secure tunnel between two points using either a
                 > hardware solution or a software solution that
                 > encrypts all traffic entering one end of the tunnel
                 > and decrypts all traffic leaving the other end of the
                 > tunnel) and **end-to-end** encryption (TLS and SSH as
                 > examples). The critical difference between link and
                 > end-to-end encryption is that in link encryption, all
                 > the data, including the header, trailer, address, and
                 > routing data, is also encrypted. End-to-end moves
                 > faster from point to point but is more susceptible to
                 > sniffers and eavesdroppers. There are actually two
                 > versions of SSH: SSH1 (considered insecure) and SSH2
                 > (dropping support for DES and IDEA but adds support
                 > for the DHKE and the ability to run multiple sessions
                 > over a single SSH connection). SSH2 provides added
                 > protection against MITD attacks, eavesdropping, and
                 > IP/DNS spoofing.

             2.  IPsec: is a standard architecture set forth by the
                 > Internet Engineering Task Force (IETF) for setting up
                 > a secure channel to exchange information between two
                 > entites. IPsec relies on security associations and
                 > there are 2 main components: the Authentication
                 > Header (**AH**) and the Encapsulating Security
                 > Payload (ESP). ESP also provides some limited
                 > authentication, but not to the degree of the AH.
                 > Though ESP is sometimes used without AH, it's rare to
                 > see AH used without ESP. IPsec provides 2 discrete
                 > modes of operation: **transport** mode (for
                 > end-to-end encryption) and **tunnel** mode (for link
                 > encryption). You set up an IPsec session by creating
                 > a **security association** (SA, representing the
                 > communication session and records any configuration
                 > and statuts information about the connection). If you
                 > want a two-way channel, you need two SAs, one for
                 > each direction. Also, if you want to support a
                 > bidirectional channel using both AH and ESP, you will
                 > need to set up four SAs. Some of IPsec's greatest
                 > strengths come from being able to filter or manage
                 > communications on a per-SA basis so that clients or
                 > gateways between which security associations exist
                 > can be rigorously managed in terms of what kinds of
                 > protocols or services can use an IPsec connection.
                 > Further details of the IPsec algorithm are provided
                 > in Chapter 11.

             3.  Emerging applications

                 a.  Blockchain: MFA needs this. Blockchain technology
                     > might also be used to track supply chains,
                     > providing consumers with confidence that their
                     > produce came from reputable sources.

                 b.  Lightweight Cryptography: low-latency and
                     > power-saving. In cases where resiliency is
                     > extremely important, the easiest way to address
                     > is for the sender of data to retain a copy until
                     > the recipient confirms the successful receipt and
                     > decryption of the data.

                 c.  Homomorphic Encryption

             4.  Cryptographic Attacks:

                 a.  Analytic Attack: is an algebraic manipulation that
                     > attempts to reduce the complexity of the
                     > algorithm.

                 b.  Implementation Attack: exploits weaknesses in the
                     > implementation of a cryptography system.

                 c.  Statistical Attack: exploits statistical weaknesses
                     > such as floating-point errors and inability to
                     > produce truly random numbers.

                 d.  Brute-Force Attack

                 e.  Fault Injection Attack: compromise the integrity of
                     > a cryptographic device by causing some type of
                     > external fault

                 f.  Side-Channel Attack: computer systems generate
                     > characteristic footprints of activity.
                     > Side-channel attacks seek to use this information
                     > to monitor system activity and retrieve
                     > information that is actively being encrypted.

                 g.  Timing Attack: an example of a side-channel attack
                     > where the attacker measures precisely how long
                     > cryptographic operations take to complete,
                     > gaining information about the cryptographic
                     > process that may be used to undermine its
                     > security

    f.  Secure Design Principles

        i.  Closed and Open systems: a **closed system** is designed to
            > work well with a narrow range of other systems, generally
            > all from the same manufacturer. The standards for closed
            > systems are often proprietary and not normally disclosed.
            > Open systems are much easier to integrate with systems
            > from different many facturers that support the same
            > standards or that use compatible APIs. However, **closed
            > source** code is sometimes revealed through either vendor
            > compromise (a breach of ethics and often the law) or
            > through decompiling or disassembly (ethical reverse
            > engineering or systems analysis).

        ii. Secure Defaults: "a rigorous condition imposed by some
            > outside agency or force". Most devices have a default
            > password, which minimizes the costs of support when
            > installing or using the product for the first time.
            > Default settings often make discovery and exploitation of
            > equipment trivial for attackers. It's always up to the
            > system's administrator and/or company security staff to
            > alter a product's settings to comply with the
            > organization's security policies.

        iii. Fail Securely: One such mechanism, which is supported by
             > many languages, is a try..catch statement. The first
             > question to be resolved is whether the system can operate
             > in a fail-soft mode (to allow a system to continue to
             > operate after a component fails). In physical world
             > situations, it can be bank vault, medical lab, or even
             > data center. A fail-secure system prioritizes the
             > physical security of assets over any other consideration.
             > The terms **fail-open** is a synonym to **fail-safe** and
             > **fail-closed** is a synonym of **fail-secure**.

             ![{47531AF0-D185-443D-81E1-B3DAEFDDE28D}](media/image3.png){width="5.55in"
             height="1.7083333333333333in"}

        iv. "Keep it simple" (or KISS, "keep it stupid simple"):
            > encouragement to avoid overcomplicating the environment,
            > organization, or product design. Similar terms are "Don't
            > Repeat Yourself" (**DRY**, not repeating the same code in
            > multiple places, which increase the difficulty in
            > changes), **computing minimalism** (a goal of the program
            > evaluation and review technique, **PERT**), **rule of
            > least power**, "**worse is better**" (aka New Jersey
            > Style, fewer functions but maybe more secure), "**you
            > aren't gonna need it**" (YAGNI, don't add functions if
            > it's not necessary).

        v.  Zero Trust & Trust but Verify

        vi. Privacy by Design (**PbD**): integrate privacy protections
            > into products during the early design phase. The PbD
            > framework is based on seven foundational principles:

            1.  Proactive not reactive; preventive not remedial

            2.  Privacy as the default

            3.  Privacy embedded into design

            4.  Full functionality - positive-sum, not zero-sum

            5.  End-to-end security - full lifecycle protection

            6.  Visibility and transparency

            7.  Respect for user privacy

                The goal of PbD is to have developers integrate privacy
                protections into their solutions. It led to the **Global
                Privacy Standard** (GPS), creating a single set of
                universal privacy principles (which is integrated in
                EU's GDPR).

        vii. Ensuring CIA: confinement (allowing a process to read from
             > and write to only certain memory locations and resources,
             > or **sandboxing**), bounds (of a process consist of
             > limits set on the memory addresses and resources it can
             > access), isolation (used to protect the operating
             > environment, allowing for a fail-soft environment),
             > access control, trust (typically **trusted system**,
             > where all protection mechanisms work together to process
             > sensitive data for many types of users while maintaining
             > a stable and secure computing environment) and assurance
             > (the degree of confidence in satisfaction of security
             > needs)

    g.  Hardware: we all know

    h.  Processor: CPU

    i.  Execution Types:

        i.  Multitasking: handling two or more tasks simultaneously

        ii. Multicore: CPU contains two or more independent execution
            > cores. Some chips contain over 10000 cores.

        iii. Multiprocessing: using more than 1 processor to complete
             > the execution of a multi-threaded application.

        iv. Multiprogramming: similar to multitasking. It involves the
            > pseudo-simultaneous execution of two tasks on a single
            > processor coordinated by the OS to increase operational
            > efficiency.

        v.  Multi-threading: mentioned above, it permits multiple
            > concurrent tasks to be performed within a single process.

    j.  Protection Mechanisms: The ways in which running computers
        > implement and handle security at runtime may be broadly
        > described as a collection of protection mechanisms, such as
        > protection rings and operational states:

        i.  Protection rings: organize code and components in an OS
            > (like applications, utilities, or other code that runs
            > under the OS's control) into concentric rings. Though the
            > original Multics Implementation allowed up to seven rings
            > (numbered 0 through 6), most modern OSs use a four-ring
            > model (numbered 0 through 3). The part of an OS that
            > always remains resident in memory is called the
            > **kernel**. It occupies ring 0 and can preempt (prevent)
            > code running at any other ring. The remaining parts of the
            > OS occupy ring 1. Ring 2 is also somewhat privileged in
            > that it's where I/O drivers and system utilities reside;
            > these are able to access peripheral devices, special
            > files, and so forth that applications and other programs
            > cannot themselves access directly. Those applications and
            > programs occupy ring 3 (outermost ring).

            ![{4E3613C8-A3FC-4E9C-A45D-3E5C4400AC74}](media/image4.png){width="5.763194444444444in"
            height="5.822916666666667in"}

            Those processes that run in higher-numbered rings must
            generally ask a handler or a driver in a lower-numbered ring
            for services they need (aka **system call**), called
            **mediated-access model**. In practice, many moderns OSs use
            only two rings or divisions: one for system-level access
            (ring 0-2, kernel mode or privileged mode), and on for
            user-level programs and applications (ring 3, often called
            user mode).

        ii. Process states (or operating states): various forms of
            > execution in which a process may run. Where the OS is
            > concerned, it can be in one of two modes at any given
            > moment: operating in a privileged, all-access mode known
            > as **supervisor state** or operating in what's called the
            > **problem state** associated with user mode where all
            > access requests must be checked against credentials for
            > authorization.

    k.  Recording Microphone: can be controlled by MDM/UEM in sensitive
        > areas or meetings

    l.  Wi-Fi Direct: new name for the wireless topology of ad hoc or
        > peer-to-peer connections. Recommend use WPA2 or WPA3 in
        > business environments (cuz it has encryption).

    m.  Tethering and Hotspots: hotspots devices operate as portable
        > WAPs. It should be barred from use in most organizations cuz
        > they create direct link to the internet without a company's
        > security restrictions.

    n.  Contactless Payment Methods: some are based on NFC, RFID, SMS,
        > or optical camera-based solutions (QR-codes).

    o.  SIM Cloning: Physical control must be maintained on mobile
        > devices and an account or service lock established on mobile
        > services with the telco carrier.

    p.  Covert Channels:

        i.  Covert Timing Channel: conveys information by altering the
            > performance of a system component or modifying a
            > resource's timing in a predictable manner. Very difficult
            > to detect

        ii. Covert Storage Channel: conveys information by writing data
            > to common storage area where another process can read it.

    q.  Rootkits: malwre that embeds itself deep within an OS. Notice
        > when system files, such as device drivers and dynamic-link
        > libraries (DLLs), have file size and/or hash value change.
        > File hash tracking can be performed manually by an
        > administrator or automatically by HIDSs (host-based IDS) and
        > system monitoring security tools.

    r.  Incremental Attacks:

        i.  Data diddlings: attacker gains access to a system and makes
            > small, random, or incremental changes to data during
            > storage, processing, input, output, or transaction.

        ii. Salami attack: (myth) systematic whittling at assets in
            > accounts or other records with financial value.

    s.  Third-Party Application Stores: Sometimes are blocked to prevent
        > malware.

    t.  Industrial Control Systems (ICS): a form of computer-management
        > device that controls industrial processes and machines, also
        > known as **operational technology** (OT). Several forms of ICS
        > are distributed control systems (DCSs), programmable logic
        > controllers (PLCs), and supervisory control and data
        > acquisition (SCADA). A DCS focuses on processes and is state
        > driven, whereas SCADA focuses on data-gathering and is event
        > driven. A DCS is used to control processes using a network of
        > sensors, controllers, actuators, and operator terminals and is
        > able to carry out advanced process control techniques. SCADA
        > is suitable for managing systems over large geographic areas.
        > PLC units are effectively single-purpose or focused-purpose
        > digital computers. They are typically deployed for the
        > management and automation of various industrial
        > electromechanical operations.

    u.  Grid computing: a form of parallel distributed processing that
        > loosely groups a significant number of processing nodes to
        > work toward a specific processing goal. When a system is
        > otherwise in an idle state, it could join a grid group,
        > download a small portion of work, and being calculations.

    v.  Firmware (or microcode): software that is stored in a ROM or an
        > EEPROM. It often drives the basic operation of a computing
        > device.

    w.  Large-Scale Parallel Data Systems: a computation system designed
        > to perform numerous calculations simultaneously.

    x.  Serverless Architecture: a cloud computing concept where code is
        > managed by the customer and the platform or server is managed
        > by the cloud service provider (CSP). It's also known as
        > function as a service (**FaaS**). With this, the functions run
        > only when called and then terminate when their operations are
        > completed, thus minimizing costs.

    y.  Infrastructure as Code (IaC): is a change in how hardware
        > management is perceived and handled.

    z.  Software-defined everything (SDx): a trend of replacing hardware
        > with software using virtualization.

        i.  Virtual desktop infrastructure (VDI): hosting
            > desktop/workstation OS virtual machines on central servers
            > that are remotely accessed by the users. It's also known
            > as VDE (virtual desktop envirnment). Updating the host
            > system doesn't update the guest OSs. Don't forget to
            > update hypervisor as well.

        ii. VM sprawl occurs when an organization deploys numerous
            > virtual machines without an overarching IT management or
            > security plan in place.

        iii. Software-defined visibility (SDV): a framework to automate
             > the processes of network monitoring and response. It
             > provides security and IT management with oversight into
             > all aspects of the company network, both on-premises and
             > in the cloud, with an emphases on defense and efficiency.
             > SDV is another derivative of IaC.

        iv. Anything as a Service (XaaS): computing service or
            > capability that can be provided to customers through or
            > over a cloud solution. One area of growth in XaaS is
            > security as a service (SECaaS), also referred to as a
            > managed service provider (MSP) or a mangaed security
            > service provider (MSSP).

        v.  Containerization (or OS-virtualization): evolution of the
            > virtualization trend for both internally hosted systems
            > and cloud providers and services.

            ![{84B549E3-4675-47B3-8C84-B4333939AAE8}](media/image5.png){width="5.764583333333333in"
            height="2.7868055555555555in"}

            Some deployments claim to eliminate the hypervisor
            altogether and replace it with a collection of common
            binaries and libraries for the containers to call upon when
            needed.

            ![{B9B10998-E03B-4563-944A-C37A04FF161D}](media/image6.png){width="5.4in"
            height="4.525in"}

            ![{5D806677-BD3E-47C4-B347-7AABC22B66CD}](media/image7.png){width="5.291666666666667in"
            height="4.625in"}

<!-- -->

3.  Understand the fundamental concepts of security models (e.g., Biba,
    Star Model, Bell-LaPadula)

    A **capabilities list** maintains a row of security attributes for
    each controlled object. A subject performs actions or operations
    within the system while an object contains data or resources that
    the subject interacts with.

    ![{65E6BB6A-7011-4327-961D-D6C1AE6FEE61}](media/image8.png){width="5.7625in"
    height="4.978472222222222in"}

    a.  Trusted Computing Base: a design principle, a combination of
        > hardware, software, and controls that work together to form a
        > trusted base to enforce your security policy. It's the
        > responsibility of TCP components to ensure that a system
        > behaves properly in all cases and that it adheres to the
        > security policy under all circumstances.

    b.  Security Perimeter: an imaginary boundary that separates the TCB
        > from the rest of the system. It may allow for the use of a
        > **trusted shell** (allowing a subject to perform command-line
        > operations without risk to the TCB or the subject).

    c.  Reference Monitors and Kernels: a part of the TCB that validates
        > access to every resource prior to granting access requests.

    d.  State Machine Model: describes a system that is always secure no
        > matter what state it is in, based on the computer science
        > definition of a **finite state machine** (FSM). An FSM
        > combines an external input with an internal machine state to
        > model all kinds of complex systems, including parsers,
        > decoders, and interpreters. Given an input and a state, an FSM
        > transitions to another state and may create an output.
        > Mathematically, the next state is a function of the current
        > state and the input next state. Likewise, the output is also a
        > function of the input and the current state output. **State
        > transition** occur when accepting input or producing output.
        > All state transitions must be evaluated. If each possible
        > state transition results in another secure state, the system
        > can be called a **secure state machine**.

    e.  Information Flow Model: focuses on controlling the flow of
        > information and are based on the state machine model. Not only
        > they deal with the direction of information but also address
        > the type of flow. They prevent unauthorized information flow,
        > often between different levels of security (multilevel
        > models). Information flow can be between subjects and objects
        > at the same or different classification levels. An information
        > flow model allows all authorized information flows, and
        > prevents all unauthorized information flows. Another
        > interesting perspective on the information flow model is that
        > it is used to establish a relationship between two versions or
        > states of the same object when those two versions or states
        > exist at different points in time. Bell-LaPadula Model is an
        > example.

    f.  Noninterference Model: is loosely based on the information flow
        > model. Instead, this model is concerned with how the actions
        > of a subject at a higher security level affect the one at a
        > lower security level. This model can be imposed to provide a
        > form of protection against damage caused by malicious
        > programs, such as Trojan horses, backdoors, and rootkits.

    g.  Some models that fall into the information flow category build
        > on the notion of inputs and outputs between multiple systems.
        > These are called **composition theories**:

        i.  Cascading: Input for one system comes from the out of
            > another system

        ii. Feedback: One system provides input to another system, which
            > reciprocates by reversing those roles (so that system A
            > first provides input for system B and then system B
            > provides input to system A).

        iii. Hookup: One system sends input to another system but also
             > sends input to external entities.

    h.  Take-Grant Model: A subject (X) with the grant right can grant
        > another subject (Y) or another object (Z) any right that
        > subject (X) possesses. Likewise, a subject (X) with the take
        > right can take a right from another subject (Y).

        ![{9C5F25E2-3F3E-4232-84D2-011F8E0BB9BC}](media/image9.png){width="5.7659722222222225in"
        height="4.405555555555556in"}

        i.  Take rule: Allows a subject to take rights over an object

        ii. Grant rule: Allows a subject to grant rights to an object

        iii. Create rule: Allows a subject to create new rights

        iv. Remove rule: Allows a subject to remove rights it has

            It is interesting to ponder that the take and grant rules
            are effectively a copy function. This can be recognized in
            modern OSes in the process of inheritance, such as subjects
            inheriting a permission from a group or a file inheriting
            ACL values from a parent folder.

    i.  Access Control Matrix

        ![{68019AEA-2425-4AEA-BDBC-9C551E7ECFA4}](media/image10.png){width="5.767361111111111in"
        height="2.9375in"}

    j.  Bell-LaPadula Model:

        i.  The Simple Security Property states that a subject may not
            > read information at a higher sensitivity level (no
            > read-up)

        ii. The \* (start) Security Property states that a subject may
            > not write information to an object at a lower sensitivity
            > level (no write-down). This is also known as the
            > Confinement Property.

        iii. The Discretionary Security Property states that the system
             > uses an access matrix to enforce discretionary access
             > control.

             The Bell-LaPadula model was designed in the 1970s, so it
             doesn't support many operations that are common today, such
             as file sharing and networking. It also assumes secure
             transitions between security layers and doesn't address
             **covert channels** (Chapter 9).

    k.  Biba Model: designed after the Bell-LaPadula model but focuses
        > on integrity:

        i.  The Simple Integrity Property states that a subject cannot
            > read an object at a lower integrity level (no read-down).

        ii. The \* (star) Integrity Property states that a subject
            > cannot modify an object at a higher integrity level (no
            > write-up).

            Biba address 3 integrity issues: prevent modification of
            objects by unauthorized subjects, prevent unauthorized
            modification of objects by authorized subjects ,and protect
            internal and external object consistency. However, critiques
            of the Biba model reveal a few drawbacks: It addresses only
            integrity, not confidentiality or availability; It focuses
            on protecting objects from external threats, assuming that
            internal threats are handled programmatically; It does not
            address access control management, and it doesn't provide a
            way to assign or change an object's or subject's
            classification level; It doesn't prevent covert channels.

    l.  Clark-Wilson Model: uses a multifaceted approach to enforcing
        > adta integrity. It doesn't require the use of a lattice
        > structure; it uses a three-part relationship of
        > subject/program/object (or subject/transaction/object, known
        > as triple or an **access control triplet**). Objects can be
        > accessed only through programs. Throught the use of
        > "well-formed transactions" and "separation of duties", this
        > model provides an effective means to protect integrity.
        > Well-formed transactions take the form of programs. A subject
        > is able to access objects only by using a program, interface,
        > or access portal. Each program has specific limitations on
        > what it can and cannot do to an object (such as database or
        > other resource). This effectively limits the subject's
        > capabilities.

        ![{3F5895E1-F350-47B3-8E96-749A4119D2B1}](media/image11.png){width="5.7625in"
        height="1.9381944444444446in"}

        Clark-Wilson defines the following items and procedures:

        i.  A **constrained data item** (CDI) is any data item whose
            > integrity is protected by the security model

        ii. An **unconstrained data item** (UDI) is any data item that
            > is not controlled by the security model. Any data that is
            > to be input and hasn't been validated, or any output.

        iii. An **integrity verification procedure** (IVP) is a
             > procedure that scans data items and confirms their
             > integrity.

        iv. **Transformation procedures** (TPs) are the only procedures
            > that are allowed to modify a CDI.

    m.  Brewer and Nash Model: permit access controls to change
        > dynamically based on a user's previous activity (a kind of
        > state machine model as well). It's sometimes known as the
        > Chinese Wall model, ethical wall, or cone of slience

    n.  Goguen-Meseguer Model: a less well-known integrity model. It's
        > said to be the foundation of noninterference conceptual
        > theories. It's based on predetermining the set or domain (a
        > list) of objects that a subject can access. It's based on
        > automation theory and domain separation. Thus, subjects are
        > unable to interfere with each other's activities.

    o.  Sutherland Model: another integrity model. It focuses on
        > preventing interference in support of integrity. It's based on
        > the idea of defining a set of system states, initial states,
        > and state transitions. It's used to prevent a covert channel
        > from being used to influence the outcome of a process or
        > activity.

    p.  Graham-Denning Model: focused on the secure creation and
        > deletion of both subjects and objects. Additionally, securely
        > provide the read, grant, delete, and transfer access right.

    q.  Harrison-Ruzzo-Ullman Model (HRU): an extension of
        > Graham-Denning model. The state of access rights under HRU can
        > be expressed in a matrix. It defines the intersection of each
        > row and column with procedures allowed. Additionally, a finite
        > set of commands (or primitives) controls how the matrix can be
        > modified by authorized subjects

4.  Select Controls Based on Systems Security Requirements

    Buyers are often willing to consider only systems that have been
    subjected to formal evaluation processes in advance and have
    received some kind of security rating.

    a.  Common Criteria (CC): was designed as a dynamic subjective
        > product evaluation model and replaced previous static systems,
        > such as the U.S. Department of Defense's Trusted Computer
        > System Evaluation Criteria (TCSEC) and the EU's Information
        > Technology Security Evaluation Criteria (ITSEC). A document
        > titled "**Arrangement on the Recognition of Common Criteria
        > Certificates in the Field of IT Security**" was signed by
        > representatives from government organizations in Canada,
        > France, Germany, the UK, and the US in 1998, making the
        > document an international standard. The original arrangement
        > documentation has been formally adopted as a standard and
        > published as ISO/IEC 15408-1, -2, and -3 and primarily labeled
        > as "Information technology \-- Security techniques \--
        > Evaluation criteria for IT security." The objectives of the CC
        > guidelines are as follows:

        i.  To add to buyers' confidence in the security of evaluated IT
            > products

        ii. To eliminate duplicate evaluations

        iii. To keep making security evaluations more cost-effective and
             > efficient

        iv. To make sure evaluations of IT products adhere to high and
            > consistent standards

        v.  To promote evaluation and its availability

        vi. To evaluate the functionality and assurance of the target of
            > evaluation (**TOE**).

            **Protection profiles** (PPs) specify for a TOE the security
            requirements and protections, which are considered the
            security desires from a customer. **Security targets** (STs)
            specify the claims of security from the vendor that are
            built into a TOE. The client initially selects a vendor
            based on publised or marketed **evaluation assurance
            levels** (EALs) for currently available systems. Using CC to
            choose a vendor allows clients to request exactly what they
            need for security rather than having to use static fixed
            security levels.

            ![{F512C9FA-14B3-46DC-A984-F18C49CF7840}](media/image12.png){width="5.616666666666666in"
            height="6.5in"}

            ![{44A49EC4-F93A-4EE4-9E1D-C65EE0428974}](media/image13.png){width="5.763194444444444in"
            height="3.1104166666666666in"}

    b.  Authorize to Operate (ATO): to obtain an official approval to
        > use secured equipment for operational objects. The assessment
        > and assignment of an ATO is performed by an Authorizing
        > Official (AO). Other terms for AO are designated approving
        > authority (DAA), Approving Authority (AA), Security Control
        > Assessor (SCA), and Recommending Official (RO). A typical ATO
        > lasts for 5 years and must be reobtained when:

        i.  The ATO time frame has expired

        ii. The system experiences a signification security breach or
            > change (decided by the AO)

            An AO can issue four types of authorization decisions:

            \- Authorization to Operate

            \- Common Control Authorization: when a security control is
            inherited from another provider and when the risk associated
            with the common control is acceptable and already has a ATO
            from the same AO.

            \- Authorization to Use: when a third-party provider (such
            as a cloud service) provides IT/IS servers that are deemed
            to have risk at an acceptable level; it's also used to allow
            one AO to accept an ATO granted by another AO.

            \- Denial of Authorization

            The RMF ATO concept replace the previous certification and
            accreditation (C&A) process like C.F.D (Candidates for
            Deletion).

5.  Understand Security Capabilities of Information Systems

    a.  Memory Protection: isolation, virtual memory, segmentaion,
        > memory management, and protection rings are discussed in
        > chapter 9. Additionally, memory overflows.

    b.  Virtualization: In chapter 9

    c.  Trusted Platform Module: already discussed

    d.  Interfaces: **constrained** (or **restricited**) **interface**
        > is implemented within an application to restrict what users
        > can do or see based on their privileges. It's a practical
        > implementation of the Clark-Wilson model of security (which I
        > skipped).

    e.  Fault Tolerance: ability of a system to suffer a fault but
        > continue to operate (Chapter 18).

    f.  Encryption/Decryption: Chapter 6 and 7

6.  Apply Security Principles to Site and Facility Design

    a.  Secure Facility Plan: outlines the security needs of your
        > organization and emphasizes methods or mechanisms to employ to
        > provide security. It's developed through **risk assessment**
        > and **critical path analysis**. Critical path analysis is a
        > systematic effort to identify relationships between
        > mission-critical applications, processes, and operations.

        i.  Site Selection

        ii. Facility Design:

            1.  Guidelines and requirements from Occupational Safety and
                > Health Administration (OSHA) and the Environmental
                > Protection Agency (EPA).

            2.  Consider include combustibility, fire rating,
                > construction materials, load rating, placement, and
                > control of items such as walls, doors, ceilings,
                > flooring, HVAC, power, water, sewage, gas, and so on.

            3.  Forced intrusion, emergency access, resistance to entry,
                > direction of entries and exits, use of alarms, and
                > conductivity are other important aspects to evaluate.

            4.  Crime Prevention Through Environmental Design (CPTED)
                > addresses facility design, landscaping, entrance,
                > concepts, campus layouts, lighting, road placement,
                > and traffic management of vehicles and those on foot.

        iii. Implement Site and Facility Security Controls

             1.  Administrative physical security controls: facility
                 > construction and selection, site management, building
                 > design, personnel controls, awareness training, and
                 > emergency response and procedures.

             2.  Technical physical security controls: building access
                 > controls; intrusion detection; alarms; security
                 > cameras; monitoring; heating, ventilation, and
                 > air-conditioning (HVAC) power supplies; and fire
                 > detection and suppression.

             3.  Physical controls for physical security include
                 > fencing, lighting, locks, construction materials,
                 > access control vestibules (mantraps), guard dogs, and
                 > security guards.

             4.  Wiring Closets:

                 a.  Entrance facility (demarcation point or MDF): the
                     > entrance point to the building where the cable
                     > from the provider connects the internal cable
                     > plant.

                 b.  Equipment room: main wiring closet for the
                     > building, often connected to or adjacent to the
                     > entrace facility

                 c.  Backbone distribution system: provides wired
                     > connections between the equipment room and the
                     > telecommunications room, including cross-floor
                     > connections

                 d.  Wiring closet: connection needs of a floor or a
                     > section of a large building by providing space
                     > for networking equipment and cabling systems.

                 e.  Horizontal distribution system: provides the
                     > connection between the telecommunications room
                     > and work areas, often including cabling,
                     > cross-connection blocks, patch panels, and
                     > supporting hardware infrastructure.

                     Protected cable distribution or protective
                     distribution systems (PDSs) are the means.

             5.  Server Rooms/Data Centers: smart/dumb cards, proximity
                 > devices and readers biometrics, IDSs (focusing on
                 > physical intruders), and a design based around
                 > defense in depth.

             6.  Smartcards and Badges: badges maybe color-coded by
                 > facility or classification level, and they often
                 > include pictures, magnetic stripes, QR codes or bar
                 > codes for optical decoding, smartcard chips, RFID,
                 > NFC, and personal details to help a security guard
                 > verify identity. Smartcards are credit card-sized
                 > IDs, badges, or security passes with an embedded
                 > magnetic stripe, bar code, or integrated circuit
                 > chip. In most cases, they are used in a multifactor
                 > configuration.

             7.  Proximity device: can be a passive device, a
                 > field-powered device, or a transponder to control
                 > physical access.

             8.  IDS

             9.  Noise (mostly electromagnetic noise by wires)

             10. Water: wet pipe system, dry pipe system, preaction
                 > system, deluge system

             11. Gas: EPA-approved substitutes for halon. CO2 should be
                 > implemented only in special circumstances.
                 > Water-based system is inappropriate.

             12. Fire: rate-of-rise detection system, flame-actuated
                 > system, smoke-actuated system, incipient smoke
                 > detection system

                 ![{05CAB4B5-3C7A-45ED-856B-1A29C3BAFF9A}](media/image14.png){width="5.7652777777777775in"
                 height="2.4784722222222224in"}

             13. Motion Detectors: digital motion detector monitors,
                 > passive infrared (PIR), wave pattern motion detector,
                 > capacitance motion detector, photoelectric motion
                 > detector, passive audio motion detector

             14. Intrusion alarms: deterrent alarms, repellent alarms,
                 > notification alarms, local alarm system, central
                 > station system, auxiliary alarm system

             15. Secondary Verification Mechanisms: should be in place
                 > after motion detectors, sensors, and alarms are used
                 > to prevent false alarms.

                 Domain 4: Communication and Network Security

<!-- -->

1.  Chapter 11: Secure Network Architecture and Components

    a.  OSI model.

        i.  Peer layer communication: the information removed by each
            > layer contains instructions, checksums, and so on that can
            > be understood only by the peer layer that originally added
            > or created the information.

        ii. Protocol data unit (PDU): a network container that
            > encapsulates data at layer 5, 6, and 7.

        iii. TCP/UDP: layer 4.

        iv. Packet: layer 3

        v.  Frame: layer 2

        vi. Bits: layer 1

        vii. Application layer: the protocols and services required to
             > transmit files, exchange messages, connect to remote
             > terminals, and so on.

        viii. Presentation layer: responsible for transforming data into
              > a format that any system following the OSI model can
              > understand.

              Encryption in relation to network communication can occur
              in at least five locations:

              1.  Pre-network encryption where the software encrypts
                  > prior to sending the data into the Application layer

              2.  TLS for Transport

              3.  VPN at layer 2, 3, or 4 such as L2TP, IPsec, or
                  > OpenVPN, respectively.

              4.  Wireless encryption at the Data Link layer

              5.  Bulk encryption at Physical layer (device external to
                  > the NIC).

        ix. Session layer: establishing, maintaining, and terminating
            > communication sessions between two computers. Manages
            > **dialog discipline** or **dialog control** (simplex,
            > half-duplex, full-duplex). Establishes checkpoints for
            > grouping and recovery, and retransmits PDUs that have
            > failed.

            1.  Simplex: one-way communication

            2.  Half-duplex: two-way communication, but only one
                > direction can send data at a time.

    b.  TCP/IP: Application, Transport, Internet, and Link layers.

    c.  Protocol analyzer: same as sniffer, network evaluator, network
        > analyzer, traffic monitor, or packet-capturing utility.

        i.  Port:

            1.  Telnet/tcp: 23 (not recommed, use ssh instead)

            2.  FTP/tcp: 20 for active mode, 21 for passive mode

            3.  TFTP/udp: 69

            4.  SMTP/tcp: (not recommend, recommend SMTPS cuz it has
                > TLS) used for transmit email, 25.

            5.  POP3 (Post Office Protocol)/tcp: used to pull email
                > messages from an inbox, 110 (recommend POPS)

            6.  IMAP4 (Internet Message Access Protocol)/tcp: (recommend
                > IMAPS) same usage as POP and can retrieve only headers
                > or delete messages directly off the email server
                > (**server arching**), 143.

            7.  DHCP, udp: 67

            8.  HTTP, tcp: 80

            9.  HTTPS, tcp: 443

            10. LPD (Line printer Daemon), tcp: 515, recommend enclosed
                > data in VPN

            11. X Window, tcp: 6000-6063 (recommend use with VPN).

            12. NFS (Network File System), tcp: network service that
                > supports file sharing between dissimilar systems, 2049
                > (recommend use with VPN).

            13. SNMP, udp: used to collect network health and status
                > information, 161 (162 for **Trap Messages**)
                > (recommend SNMPv3 only). 161 is used by the SNMP agent
                > (network device) to receive requests while 162 is used
                > by the mangement console to receive responses and
                > notifications (trap messages).

        ii. Transport layer: port number ranges from 0 to 65535 (2\^16).

            1.  Socket: a combination of an IP address and a port number

            2.  Multiplexing over IP: ports allow a single IP address to
                > be able to support multiple simultaneous
                > communications.

            3.  Well-known ports or service ports (exclusively used by
                > servers): 0-1,023

            4.  Registered software ports (registered with the
                > International Assigned Numbers Authority IANA): 1,024
                > to 49,151

            5.  Random, dynamic, or ephemeral ports (used randomly by
                > clients as a source port): 49,152 to 65,535. However,
                > most OSs allow for any port from 1,024 to be used as a
                > dynamic client source port as long as it is not
                > already in use on that local system.

            6.  DNS: links IP addresses and human-friendly fully
                > qualified domain names (FQDNs) together. An FQDN
                > consists of three main parts:

                a.  Top-level domain (TLD)-the com in
                    > [www.google.com](http://www.google.com)

                b.  Registered domain name-the google in
                    > [www.google.com](http://www.google.com)

                c.  Subdomain(s) or hostname-the www in
                    > [www.google.com](http://www.google.com)

            7.  Zone file: collection of resource records or details
                > about the specific domain. Dozens of these can be
                > found on
                > [www.iana.org/assignments/dns-parameters/dns-parameters.xhtml](http://www.iana.org/assignments/dns-parameters/dns-parameters.xhtml)
                > such as A records linking an FQDN to an IPv4 address
                > and AAAA records linking an FQDN to an IPv6 address.

            8.  Every registered domain name has an assigned
                > authoritative name server.

                a.  Primary authoritative name server: hosts the
                    > original editable zone file for the domain

                b.  Secondary authoritative name server: can be used to
                    > host read-only copies of the zone file.

            9.  DNSSEC (dnssec.net): a security improvement to the
                > existing DNS infrastructure. Provide mutual
                > certificate authentication and encrypted sessions
                > between devices during DNS operations. It has been
                > widely adopted and can prevent **zone file poisoning**
                > and **DNS cache poisoning**.

            10. Non-DNS servers (mostly client devices) should consider
                > using **DNS over HTTPS** (DoH), creating encrypted
                > session with a DNS server of TLS-protected HTTP which
                > is used (the encrypted session) as a VPN to protect
                > the DNS query and response. **Oblivious DoH** (ODoH)
                > is the late 2020 enhancement of DoH, adding a DNS
                > proxy between the client and the DNS resolver so that
                > the identity of the requesting client is isolated from
                > the DNS resolver.

            11. Rogue DNS Server: capture any DNS query or specific one
                > then send the false IP information.

            12. Performing DNS Cache Poisoning: attackers focus on
                > caching real DNS servers or clients (storing false DNS
                > records into their system).

            13. DNS Pharming: malicious redirection of a valid website's
                > URL or IP address to a **fake website**. Occurs by
                > modifying the locat hosts file or DNS
                > poisoning/spoofing DNS resolution.

            14. Altering the Hosts file (stored on individual
                > end-point).

            15. Corrupt the IP configuration: the DNS server address is
                > typically distributed to clients through DHCP, but it
                > can also be assigned statically. Attacks to alter a
                > client's DNS server lookup address can be performed by
                > compromising DHCP or through a script.

            16. DNS Query Spoofing: eavesdrop DNS query then spoof.

            17. Proxy falsification: although not strictly a DNS issue,
                > a proxy falsification attack could be implemented via
                > DNS if the proxy's domain name has to be resolved by
                > the client to use the proxy. *Many organizations use a
                > proxy server to filter traffic, enforce policies, or
                > improve security. The proxy server is typically
                > accessed using a domain name (e.g.,
                > proxy.company.com).*

            18. Zone transfer: the process of copying DNS zone files
                > from one DNS server to another. This is mainly used to
                > synchronize DNS records between a primary (master) DNS
                > server and a secondary (slave) DNS server to ensure
                > redundancy and availability.

            19. Defense to DNS poisoning:

                a.  Limit zone transfer from internal DNS servers to
                    > external DNS servers (blocking inbound TCP port 53
                    > (zone transfer requests) and inbound UDP port 53
                    > (queries)).

                b.  Require internal clients to resolve all domain names
                    > through the internal DNS (blocking outbound UPD
                    > port 53 while keeping open outbound TCP port 53).

                c.  Limit the external DNS servers from which internal
                    > DNS servers pull zone transfers.

                d.  Deploy a network IDS (NIDS) & install HIDS.

                e.  Use DNSSEC, DoH, or ODoH on all clients where
                    > supported.

                f.  DNS sinkhole: a specific example of a false
                    > telemetry system (aka sinkhole server, internet
                    > sinkhole, and blackhole DNS), an effectively DNS
                    > spoofing used as a defense. It provides false
                    > responses to DNS queries from malware, such as
                    > bots, to prevent access to command and control
                    > systems.

            20. Domain Hijacking (or domain theft): XSRF, hijecking a
                > session, using an on-path/MitM attack, or exploiting a
                > flaw in the domain registrar's systems.

                a.  Best defense: use strong multifactor authentication
                    > when logging into your domain registrar.

                b.  Defense against letting your domain registration
                    > lapse (fails to renew domain name before the
                    > expiration date): set up auto-renew and
                    > double-check the payment method a week before the
                    > renewal date.

            21. Typosquatting: when users mistypes the domain name or IP
                > address

            22. Homograph attack: for example, in many fonts, some
                > letters in Cyrillic look like Latin characters; for
                > example, the l (I.e., lowercase L) in Latin looks like
                > the Palochka Cyrillic letter.

            23. URL hijacking

            24. Clickjacking: any mouse click or selection will be
                > captured by the floating frame and redirected

        iii. Internet Protocol (IP) Networking: it was designed to
             > perform "best effort" in finding a path or route to a
             > destination, in spite of a damaged or corrupted network
             > structure. Thus, you must employ TCP with IP to gain
             > reliable and controlled communication sessions.

             1.  IPv4 (32-bit) vs IPv6 (128-bit):

                 a.  Autoconfiguration removes the need for both DHCP
                     > and NAT. It works on IPv6 and the security is
                     > handled by firewall rules instead of NAT compared
                     > to IPv4. Also, IPsec is native to IPv6, but it is
                     > an add-on for IPv4. Some of IPv6's new features
                     > are scoped addresses, autoconfiguration, and
                     > quality of service (QoS) priority values. Scoped
                     > addresses give administrators the ability to
                     > group and then bock or allow access to network
                     > services, such as file servers or printing. QoS
                     > priority values allow for traffic management
                     > based on prioritized content (IPv4 has ToS-Type
                     > of Services but it seemed to go unused and was
                     > converted into the Differentiated Services-DS by
                     > later specification).

                 b.  Migration to IPv6 raises several security concerns:

                     i.  IP filtering and block lists will be less
                         > effective because of more IP addresses.

                     ii. Secure deployment of IPv6 requires security
                         > filtering and monitoring products be
                         > upgraded. Otherwise, it will serve as a
                         > covert channel.

                     iii. Loss or lack of NAT. NAT is not necessary and
                          > isn't addressed in the specification.
                          > Privacy is lost or reduced without NAT since
                          > a system's locally assigned IP address is
                          > not masked by NAT to a public address. Most
                          > networks already using stateful inspection
                          > firewall in addition to NAT in IPv4 network.

                 c.  For IPv6 and IPv4 coexist:

                     i.  Dual stack: having systems operate both IPv4
                         > and IPv6 and using the appropriate protocol
                         > for each conversation.

                     ii. Tunneling: allows most systems to operate a
                         > single stack of either IPv4 or IPv6 and use
                         > an encapsulation tunnel to access systems of
                         > the other protocol.

                     iii. NAT-PT (RFC-2766) (Network Address
                          > Translation-Protocol Translation): used to
                          > convert between IPv4 and IPv6 network
                          > segments similar to how NAT converts
                          > internal and external addresses.

                 d.  IPv4
                     > classes:![{6350F840-152D-40DB-9240-1E6264F0B6E0}](media/image15.png){width="5.333333333333333in"
                     > height="2.1666666666666665in"}

                 e.  CIDR notation: using /16 instead of 255.255.0.0 as
                     > a subnet mask representation for example.

                 f.  ICMP: unfortunately, its features were often
                     > exploited in various forms of bandwidth-based DoS
                     > attacks, such as **ping of death**, **smurf
                     > attacks,** and **ping floods**. This fact has
                     > shaped how networks handle ICMP traffic today.

                 g.  IGMP: allows systems to support multicasting. **RFC
                     > 1112** discusses the requirements to perform IGMP
                     > multicasting.

                 h.  ARP:

                     i.  Best defense: port security on the switch,
                         > local or software firewall, HIDPS, or sepcial
                         > endpoint security products to block
                         > unrequested ARP replies/announcements. One
                         > popular tool used to detect ARP poisoning is
                         > **arpwatch**.

                     ii. Another defense: static ARP entries.

        iv. Secure Communication Protocols

            1.  IPsec: a standard of IP security extensions used as an
                > add-on for IPv4 and integrated into IPv6.

            2.  Kerberos: offers a SSO solution for users and provides
                > protection for logon credentials. Kerberos is
                > discussed further in chapter 14.

            3.  SSH: can be used to encrypt numerous plaintext utilities
                > (like **rcp, rlogin,** and **rexe**), serve as a
                > protocol encrypter (such as with SFTP), and function
                > as a transport mode VPN.

            4.  Signal Protocol: a cryptographic protocol that provides
                > end-to-end encryption for voice communications,
                > videoconferencing, and text message services. It's
                > **nonfederated**.

            5.  Secure Remote Procedure Call (S-RPC): an authentication
                > service for cross-network service communications,
                > preventing unauthorized execution of code on remote
                > systems.

            6.  Transport Layer Security (TLS): TLS operates at OSI
                > layer 4 but it can encrypt any Application layer
                > protocol. TLS replaced SSL.

                a.  Often implemented as the initial payload of a TCP
                    > packages, allowing it to encapsulate all
                    > higher-layer protocol payloads.

                b.  Can be used to encrypt UDP and SIP (session
                    > initiation protocol, a protocol that is associated
                    > with VoIP) connections.

            7.  VPN: \[ Ethernet \[ IPsec \[ IP \[ TCP \[ TLS \[ HTTP
                > \[Payload\] \] \] \] \] \] \]

            8.  Encapsulation is not always implemented for benign
                > purposes. Numerous covert channel communication
                > mechanisms use encapsulation to hide or isolate an
                > unauthorized protocol inside another authorized one.

                a.  For example, if a network blocks the use of FTP but
                    > allows HTTP, then tools such as **HTTPTunnel** can
                    > be used to bypass this restriction: \[ Ethernet \[
                    > IP \[ TCP \[ HTTP \[ FTP \[Payload\] \] \] \] \].

                b.  Another example, with utilities such as **Loki**,
                    > ICMP is transformed into a tunnel protocol to
                    > support TCP communications: \[Ethernet \[ IP \[
                    > ICMP \[ TCP \[ HTTP \[Payload\] \] \] \] \] \]

                c.  **Unbouded encapsulation support**: ability to jump
                    > between VLANs.

            9.  Few drawbacks of multilayer protocols:

                a.  Covert channels are allowed

                b.  Filters can be bypassed

                c.  Logically imposed network segment boundaries can be
                    > overstepped.

            10. DNP3 (Distributed Network Protocol 3): primarily used in
                > the electric and water utility and management
                > industries. It's used to support communications
                > between data acquisition systems and the system
                > control equipment: substation computers, remote
                > terminal units (RTUs) (I.e., devices controlled by an
                > embedded microprocessor), intelligent electronic
                > devices (IEDs), and SCADA primary stations (i.e.,
                > control centers)
                > [www.dnp.org/About/Overview-of-DNP3-Protocol](http://www.dnp.org/About/Overview-of-DNP3-Protocol)

        v.  Converged Protocols: merging of specialty or proprietary
            > protocols with standard protocols like those from TCP/IP
            > suite. Primary benefit: able to use existing TCP/IP
            > supporting network infrastructure to host special or
            > proprietary services without the need for unique
            > deployments of alternate networking hardware.

            1.  Storage Area Network (SAN): secondary network,
                > consolidating network-accessible storage container.
                > It's often used to enhance networked storage devices
                > such as hard drives, drive arrays, optical jukeboxes,
                > and tape libraries so that they can be made to appear
                > to servers as if they were local storage. Sans operate
                > by encapsulating or converging data storage signals
                > into TCP/IP communications in order to separate
                > storage and proximity. A SAN can be a single point of
                > failure, so redundancy needs to be integrated to
                > provide protection of availability. In some instances,
                > a SAN may implement deduplication in order to save
                > space by not retaining multi copies of the same file.
                > However, this can sometimes result in data loss if the
                > one retained original is corrupted.

            2.  Fibre Channel over Ethernet (FCoE): Fibre Channel: a
                > form of network data-storage solution (SAN or
                > network-attached storage \[NAS\]) that allows for
                > high-speed file transfer upward of 128 Gbps. It
                > operates at layer 2. It's was designed to be operated
                > over fiber-optic cables; support for copper cables was
                > added later to offer less expensive options. It
                > typically requires its own dedicated infrastructure
                > (separate cables). However, FCoE can be used to
                > support it over the existing network infrastructure.
                > FCoE is used to encapsulate Fibre Channel
                > communications over Ethernet networks. It typically
                > requires 10 Gbps Ethernet in order to support the
                > Fibre Channel protocol. With this technology, Fibre
                > Channel operates as a Network layer or OSI layer 3
                > protocol, replacing IP as the payload of a standard
                > Ethernet network. Fibre Channel over IP (FCIP) further
                > expands the use of Fibre Channel signaling to no
                > longer require any specific speed of network. It's the
                > SAN equivalent of VoIP.

            3.  MPLS (Multiprotocol Label Switching): a high-throughput
                > high-performance network technology that directs data
                > across a network based on short path labels rather
                > than longer network addresses. This technique saves
                > significant time over tranditional IP-based routing
                > processes, which can be quite complex. Furthermore,
                > MPLS is designed to handle a wide range of protocols
                > through encapsulation. Thus, the network is not
                > limited to TCP/IP and compatible protocols. This
                > enables the use of many other networking technologies,
                > including T1/E1, ATM, Frame Relay, SONET, and Digital
                > Subscriber Line (DSL).

            4.  Internet Small Compuer System Interface (iSCSI) Internet
                > Small Computer System Interface (iSCSI) is a
                > networking storage standard based on IP that operates
                > at layer 3. This technology can be used to enable
                > location-independent file storage, transmission, and
                > retrieval over LAN, WAN, or public internet
                > connections. iSCSI is often viewed as a low-cost
                > alternative to Fibre Channel.

        vi. VoIP: a tunneling mechanism that encapsulates audio, video,
            > and other data into IP packets to support voice calls and
            > multimedia collaboration. It's inexpensive telephony
            > solution for companies and individuals worldwide. Some
            > VoIP solutions are software only (Skype) and somes require
            > specialized hardware to either replace tranditional
            > telephone handsets/base stations or allow these to connect
            > to and functions over the VoIP system. Hackers can wage a
            > wide range of potential attacks against a VoIP solution:

            1.  Caller ID can be falsified easily using any number of
                > VoIP tools, so hackers can perform vishing (VoIP
                > phishing) or Spam over Internet Telephony (SPIT)
                > attacks.

            2.  The call manager systems and VoIP phones themselves
                > might be a vulnerable to host operating system attacks
                > and DoS attacks. If a device's or software's host OS
                > or firmware has vulnerabilities, there is increased
                > risk of exploits.

            3.  Attackers might be able to perform MitM/on-path attacks
                > by spoofing call managers or endpoint connection
                > negotiations and/or responses.

            4.  Depending on the deployment, there are also risks
                > associated with deploying VoIP phones off the same
                > switches as desktop and server systems. This could
                > allow for 802.1X authentication falsification as well
                > as VLAN and VoIP hopping (i.e., jumping across
                > authenticated channels).

            5.  Since VoIP traffic is just network traffic, it's often
                > possible to listen in on VoIP communications by
                > decoding the VoIP traffic when it isn't encrypted.

                Secure Real-Time Transport Protocol or Secure RTP (SRTP)
                is a security improvement over the Real-Time Transport
                Protocol (RTP) that is used in many VoIP communications.
                SRTP aims to minimize the risk of DoS, on-path attacks,
                and other VoIP exploits through robust encryption and
                reliable authentication. RTP or SRTP takes over after
                Session Initiation Protocol (SIP) establishes the
                communication link between endpoints.

        vii. Software-Defined Networking (SDN):

             1.  The concept is based on the theory that the
                 > complexities of a traditional network with on-device
                 > configuration (i.e., routers and switches) often
                 > force an organization to stick with a single device
                 > vendor, and limit the flexibility of the network to
                 > adapt to changing physical and business conditions,
                 > as well as optimize costs of acquiring new devices.

             2.  It aims at separating the **infrastructure layer** (aka
                 > the data plane and the forwarding plane)\--hardware
                 > and hardware-based settings\--from the control
                 > layer\--network services of data transmission
                 > management.

             3.  The control plane uses protocols to decide where to
                 > send traffic, and the data plane includes rules that
                 > decide whether traffic will be forwarded.

             4.  This form of traffic management also involves access
                 > control over what systems can communicate which
                 > protocols to whom. This type of access control is
                 > typically attribute-based access control (ABAC)
                 > focused or based.

             5.  SDN gives the option to handle traffic routing using
                 > simpler network devices that accept instructions from
                 > the SDN controller. This eliminates some of the
                 > complexity related to traditional networking
                 > protocols and concepts: IP addressing, subnets,
                 > routing, and the like from needing to be programmed
                 > into or be deciphered by hosted applications.

             6.  Using SDN frees an organization from having to purchase
                 > devices from a single vendor. The configuration and
                 > management of hardware are then controlled through a
                 > centralized management interface. In addition, the
                 > settings applied to the hardware can be changed and
                 > adjusted dynamically as needed.

             7.  It allows data transmission paths, communication
                 > decision trees, and flow control to be virtualized in
                 > the SDN control layer rather than being handled on
                 > the hardware on a per-device basis.

             8.  SAN is a network technology that combines multiple
                 > individual storage devices into a single consolidated
                 > network-accessible storage container. They are often
                 > used with multiple or clustered servers that need
                 > high-speed access to a single shared dataset. These
                 > have historically been expensive due to the complex
                 > hardware requirements of the SAN.

             9.  Virtual SAN (VSAN) bypass the complexities of the SAN
                 > with virtualization. A virtual SAN or a
                 > software-defined shared storage system is a virtual
                 > re-creation of a SAN on top of a virtualized network
                 > or an SDN.

             10. Software-defined storage (SDS) is another derivative of
                 > SDN. SDS is a SDN version of a SAN or NAS. SDS is a
                 > storage management and provisioning solution that is
                 > policy driven and is independent of the actual
                 > underlying storage hardware. It's effectively virtual
                 > storage.

             11. Software-defined wide-area networks (SDWAN or SD-WAN)
                 > is an evolution of SDN that can be used to manage the
                 > connectivity and control services between distant
                 > data centers, remote locations, and cloud services
                 > over WAN links.

        viii. Microsegmentation: is dividing an internal network into
              > numerous subzones, potentially as small as a single
              > deice, such as a high-value server or event a client or
              > endpoint device. Each zone is separated from the others
              > by internal segmentation firewalls (ISFWs), subnets,
              > VLANs, or other virtual networking solutions.
              > Microsegmetation is a key element in implementing zero
              > trust.

              1.  Boosting Performance Network

              2.  Reducing Communication Problems

              3.  Providing Security

                  Another often-overlooked network segmentation concept
                  is the creation of an out-of-band pathway. This is
                  often performed to create a separate and distinct
                  network structure for traffic that would otherwise
                  interfere with the production network or that may
                  itself be put at risk if placed on the production
                  network. Secondary (or additional) network paths or
                  segments may be created to support data storage
                  traffic (such as with SANs), VoIP, backup data, patch
                  distribution, and mangement operations.

        ix. Virtual eXtensible LAN (VXLAN) enables VLANs to be stretched
            > across subnets and geographic distances.

        x.  Wireless network: can be deployed in either ad hoc mode or
            > infrastructure mode.
            > ![{E998AAE4-6644-40EA-B607-D74DB911D6F5}](media/image16.png){width="5.7652777777777775in"
            > height="2.4833333333333334in"}

            1.  **Wi-Fi Direct** is an upgraded version of ad hoc mode
                > that can support WPA2 and WPA3 (ad hoc supported only
                > WEP).

            2.  Infrastructure mode means that a wireless access point
                > (WAP) is required and restrictions for wireless
                > network access are enforced.

            3.  An **enterprise extended mode** deployment is when
                > multiple wireless access point (WAPs) are used to
                > connect a large physical area to the same wired
                > network. Each WAP will use the same **extended service
                > set identifier** (**ESSID**) so that clients can roam
                > the area while maintaining network connectivity, even
                > while their wireless NICs change associations from one
                > WAP to another.

            4.  A **bridge mode** deployment is when a wireless
                > connection is used to link two wired networks. This
                > often uses dedicated wireless bridges and is used when
                > wired bridges are inconvenient, such as when linking
                > networks between floors or
                > building.![{556E4EC7-49FA-404D-BF6D-2F227E97514F}](media/image17.png){width="5.767361111111111in"
                > height="2.3222222222222224in"}

            5.  A **fat access point** is a base station that is a fully
                > managed wireless system, which operates as a
                > standalone wireless solution. A **thin access point**
                > is little more than a wireless transmitter/receiver,
                > which must be managed from a separate external
                > centralized management console called a **wireless
                > controller**.

        xi. Securing the SSID

            1.  Wireless networks are assigned a SSID to differentiate
                > one wireless network from another. There are 2 types
                > of infrastructure mode SSIDs:

                a.  ESSID (extended SSID): name of a wireless network
                    > when a WAP is used.

                b.  BSSID (basic SSID): MAC address of the base station,
                    > which is used to differentiate multiple base
                    > stations supporting an ESSID.

                    ISSID (Independent SSID): used by Wi-Fi Direct or ad
                    hoc mode.

                c.  If a wireless client knows the SSID, they can
                    > configure their wireless NIC to communicate with
                    > the associated WAP. Knowledge of the SSID does not
                    > always grant entry, though, because the WAP can
                    > use numerous security features to block unwanted
                    > access.

                d.  SSID are defined by default by vendors and thus are
                    > well known. Standard security practice dictates
                    > that the SSID should be changed to something
                    > unique before deployment

                e.  Beacon frame: the SSID broadcast by the WAP. This
                    > default broadcast can be disabled to attempt to
                    > keep the wireless network secret. However,
                    > attackers can still use wireless sniffer since the
                    > SSID is still used in transmissions between
                    > connected wireless clients and the WAP. Instead,
                    > use WPA2 or WPA3 rather than trying to hide the
                    > network.

            2.  Wireless channels: Think of channels as lanes on the
                > same highway. To avoid channel overlap interference,
                > configure nearby access points to use non-overlapping
                > channels whenever possible. This means that if APs are
                > close to each other, they should be set to different
                > channels that do not interfere. For example, in the
                > 2.4 GHz Wi-Fi band, the non-overlapping channels are
                > 1, 6, and 11. 5 GHz wireless was designed to avoid
                > this channel overlap and interference issue. While 2.4
                > GHz channels are 22 MHz wide and 5 MHz apart, 5 GHz
                > channels are 20 MHz wide and 20 MHz apart. Therefore,
                > adjacent 5 GHz channels do not interfere with one
                > another. Furthermore, adjacent channels can be
                > combined or bonded into a larger width channel for
                > faster throughput.

                a.  US: 11 channels defined within the 2.4 GHz frequency
                    > range

                b.  Europe: 13 channels

                c.  Japan: 14 channels

                    5GHz is often preferred for internal networks. Most
                    of the mesh Wi-Fi options are based on 5 GHz and use
                    three or more mini-WAP devices to provide
                    ML-optimized coverage throughout a home or office.
                    There is 6 GHz that provides for more top-speed
                    connections than earlier forms of Wi-Fi. However, 6
                    GHz is even more restricted by obstacles and
                    distance.

            3.  Conducting a Site Survey

                a.  Site survey: a formal assessment of wireless signal
                    > strength, quality, and interference using an RF
                    > signal detector

                b.  Heat map: a mapping of signal strength measurements
                    > over a building's blueprint

                c.  Hot spots: oversaturation of signal

                d.  Cold spots: lack of signal

            4.  Wireless security:

                a.  Encryption is only between the client device and the
                    > base station.

                b.  Use a VPN for end-to-end encryption.

                c.  The original IEEE 802.11 defined two methods that
                    > wireless clients can use to authenticate to WAPs
                    > before normal network communications can occur
                    > across the wireless link.

                    i.  OSA (open system authentication): no real
                        > authentication is required

                    ii. SKA (shared key authentication). The 802.11
                        > standard defines one optional technique for
                        > SKA known as Wired Equivalent Privacy (WEP).
                        > Later amendments add WPA, WPA2, WPA3, and
                        > others.

                d.  Common AAA services: UDP 1812 for RADIUS and TCP 49
                    > for TACACS+

                e.  Extensible Authentication Protocol (EAP): an
                    > authentication framework

                f.  LEAP (Lightweight Extensible Authentication
                    > Protocol): Cisco proprietary alternative to TKIP
                    > for WPA

                g.  PEAP (Protected Extensible Authentication Protocol):
                    > encapsulates EAP methods within a TLS tunnel.

                h.  WPS (Wi-Fi Protected Setup): a security standard for
                    > wireless networks. Operates by auto-connecting and
                    > automatically authenticating the first new
                    > wireless client to initiate a connection to the
                    > network once WPS is triggered (by a button on the
                    > WAP or a code or PIN that can be sent to the base
                    > station remotely).

                i.  Wireless MAC Filter: can be used on a WAP to limit
                    > or restrict access

                j.  Wireless Antenna Management: can be used for
                    > wireless clients and base stations

                    i.  Pole or straight antenna: omnidirectional
                        > antenna

                    ii. Directional antennas: Yagi, cantenna, panel, and
                        > parabolic

                    iii. Consider this guidelines:

                         1.  Use a central location

                         2.  Avoid solid physical obstructions

                         3.  Avoid reflective or other flat metal
                             > surfaces

                         4.  Avoid electrical equipment.

                k.  Captive Portals: an authentication technique that
                    > redirects a newly connected client to a web-based
                    > portal access control page. Most located at
                    > hotels, restaurants, bars, airports, libraries,
                    > and so on. The **portal page** may require the
                    > user to input payment information, provide logon
                    > credentials, or input an access code. Also used to
                    > display AUP, privacy policy, and tracking policy
                    > to the user, who must consent to the policies
                    > before being able to communicate across the
                    > network.

                l.  General Wi-Fi Security
                    > Procedure:![{A6F50CD8-836F-435C-8607-3E4D14364A53}](media/image18.png){width="5.725in"
                    > height="6.575in"}

                m.  Wireless Communications:

                    i.  To manage the simultaneous use of the limited
                        > radio frequencies, several alternative
                        > spectrum-use techniques were developed:

                        1.  Spread spectrum: a message is broken into
                            > pieces sent at the same time at different
                            > frequency

                        2.  FHSS: like spread spectrum but only one
                            > frequency at a time

                        3.  DSSS: use **chipping code** to allow a
                            > receiver to reconstruct data

                        4.  OFDM: requires a smaller frequency set
                            > (channel bands) to employs a digital
                            > multicarrier modulation
                            > (perpendicular/orthogonal modulated
                            > signals) scheme that allows for a more
                            > tightly compacted transmission.

                    ii. Bluetooth: defined in IEEE 802.15 and uses the
                        > 2.4 GHz. It suffers to a wide range of attacks

                        1.  Bluesniffing

                        2.  Bluesmacking

                        3.  Bluejacking

                        4.  Bluesnarfing: it's possible against
                            > nondiscoverable devices if their Bluetooth
                            > MAC addresses are known, which could be
                            > gathered using bluesniffing.

                        5.  Bluebugging

                        6.  Best defense: just minimize the use in
                            > public

                    iii. RFID:

                    iv. NFC (near-field communication): a standard that
                        > establishes radio communications between
                        > devices in close proximity

                n.  Wireless attacks:

                    i.  Wi-Fi scanners: detect wireless network even
                        > SSID broadcast disabled.

                    ii. Rogue access points: should be discovered and
                        > removed

                    iii. Evil Twin

                    iv. Disassociation: disconnect a client from one WAP

                        1.  Network with hidden SSIDs: disassociation
                            > packet with a MAC address spoofed as that
                            > of the WAP is sent to a connected client
                            > that causes the client to lose its
                            > connection and then send a Reassociation
                            > Request packet, which includes the SSID in
                            > the clear.

                        2.  An attack can send repeated disassociation
                            > frame to a client to prevent reassociation
                            > thus causing a DoS.

                        3.  A session hijack event can be initiated by
                            > using diassociation frames to keep the
                            > client disconnected while the attacker
                            > impersonates the client and takes over
                            > their wireless session with the WAP.

                        4.  An on-path attack can be implemented by
                            > using a disassociation frame to disconnect
                            > a client. Then the attacker provides a
                            > stronger singal from their rogue/fake WAP
                            > using the same SSID and MAC as the
                            > original WAP; once the client connects to
                            > the false WAP, the attacker connects to
                            > the valid WAP.

                        5.  Best defense is to operate a WIDS, which
                            > monitors for wireless abuses.

                    v.  Jamming: to avoid or minimize interference and
                        > jamming, start by adjusting the physical
                        > location of devices. Next, check for devices
                        > using the same frequency and/or channel. If
                        > there are conflicts, change the frequency or
                        > channel in use on devices you control.

                    vi. IV (initialization vector) abuse: for example,
                        > cracking WEP encryption using the wesside-ng
                        > tool from the Aircrack-ng suite at
                        > aircrack-ng.org.

                    vii. Replay

                    viii. Other Communication Protocols

                          1.  LiFi (light fidelity)

                          2.  Satellite communications

                          3.  Narrow-band wireless is widely used by
                              > SCADA

                          4.  Zigbee: an IoT equipment communications
                              > concept that is based on Bluetooth

                    ix. Cellular Networks: 2G, 3G, 4G, 5G (latest)

                    x.  Content Distribution Networks (CDNs)

                    xi. Secure Operation of Hardware

                    xii. Common Network Equipment

                         1.  Repeaters, concentrators, amplifiers...

                         2.  Sensor: collects information and then
                             > transits it back to a central system for
                             > storage and analysis, common for fog
                             > computing, ICS, IoT, IDS/IPS, and
                             > SIEM/security orchestration, automation,
                             > and response (SOAR) solutions.

                         3.  Collector: any system that gathers data
                             > into a log or record file.

                         4.  Aggregators: type of multiplexor.

                    xiii. Network Access Control (NAC): concept of
                          > controlling access to an environment through
                          > strict adherence to and enforcement of
                          > security policy. Originally, 802.1X (which
                          > provides port-based NAC) was thought to
                          > embody NAC, but most supporters believe that
                          > 802.1X is only a simple form of NAC or just
                          > one optional component in a complete NAC
                          > solution. NAC can be implemented with a
                          > preadmission philosophy or a postadmission
                          > philosophy, or aspects of both:

                          1.  The preadmission philosophy requires a
                              > system to meet all current security
                              > requirements (such as patch application
                              > and malware scanner updates) before it
                              > is allowed to communicate with the
                              > network

                          2.  The postadmission phlosophy allows and
                              > denies access based on user activity,
                              > which is based on a predefined
                              > authorization matrix.

                    xiv. Carrier-Sense multiple access (CSMA): the LAN
                         > media access technology that performs
                         > communications using these steps:

                         1.  The host listens to the LAN media to
                             > determine whether it is in use

                         2.  If the LAN media is not being used, the
                             > host transmits its communication

                         3.  The host waits for an acknowledgment

                         4.  If no acknowledgment is received after a
                             > time-out period, the host starts over at
                             > step 1.

                    xv. Carrier-Sense Multiple Access with Collision
                        > Detection (CSMA/CD): also LAN media access
                        > technology

                        1.  The host listens to the LAN media to
                            > determine whether it is in use

                        2.  If the LAN media is not being used, the host
                            > transmits its communication

                        3.  While transmitting, the host listens for
                            > collisions (in other words, two or more
                            > hosts transmitting simultaneously).

                        4.  If a collision is detected, the host
                            > transmits a jam signal.

                        5.  If a jam signal is received, all hosts stop
                            > transmitting. Each host waits a random
                            > period of time and then starts over at
                            > step 1.

                    xvi. Carrier-Sense Multiple Access with Collision
                         > Avoidance (CSMA/CA): also LAN media access
                         > technology

                         1.  The host has two connections to the LAN
                             > media: inbound and outbound. The host
                             > listens on the inbound connection to
                             > determine whether the LAN media is in
                             > use.

                         2.  If the LAN media is not being used, the
                             > host requests permission to transmit.

                         3.  If permission is not granted after a
                             > time-out period, the host starts over at
                             > step 1.

                         4.  If permission is granted, the host
                             > transmits its communication over the
                             > outbound connection.

                         5.  The host waits for an acknowledgement.

                         6.  If no acknowledgement is received after a
                             > time-out period, the host starts over at
                             > step 1.

                    xvii. Token Passing: LAN media access technology
                          > that performs communications using a digital
                          > token. Token passing was used by ring
                          > topology-based networks, such as legacy
                          > Token Ring and Fiber Distributed Data
                          > Interface (FDDI). Token passing prevents
                          > collisions since only the system possessing
                          > the token is allowed to transmit data.

                    xviii. Polling: LAN media access technology that ...
                           > using a primary-secondary configuration.
                           > Polling can be configured to grant one
                           > system (or more) priority over other
                           > systems. For example, if the standard
                           > polling pattern was 1,2,3,4, then to give
                           > system 1 priority, the polling pattern
                           > could be changed to 1,2,1,3,1,4

                           Chapter 12:

<!-- -->

1.  Assess and implement secure design principles in network
    architectures

    a.  Internet Protocol (IP) networking (e.g., Internet Protocol
        > Security IPsec)

    b.  Internet Protocol (IP) v4/6

2.  Implement secure communication channels according to design

    a.  Voice

    b.  Multimedia collaboration

    c.  Remote access

    d.  Data communications

    e.  Virtualized networks

    f.  Third-party connectivity

Blockchain and cryptocurrency regulations are rapidly evolving areas of
law and compliance. Here's an overview to help you get started:

### **1. Key Regulatory Bodies and Frameworks** {#key-regulatory-bodies-and-frameworks}

**U.S. SEC (Securities and Exchange Commission)**  
The SEC has played a significant role in regulating cryptocurrencies,
especially in terms of whether certain tokens qualify as **securities**
under the Howey Test. If a cryptocurrency is considered a security, it
must comply with securities laws, including registration requirements.
For example, **Initial Coin Offerings (ICOs)** can face scrutiny if they
are found to involve unregistered securities.

**CFTC (Commodity Futures Trading Commission)**  
The **CFTC** has jurisdiction over certain cryptocurrencies when they
are considered **commodities**, like Bitcoin. It has the authority to
regulate the trading of cryptocurrency futures, such as those listed on
exchanges like the CME (Chicago Mercantile Exchange).

**FATF (Financial Action Task Force)**  
The **FATF** provides international guidelines for **anti-money
laundering (AML)** and **counter-financing of terrorism (CFT)**
regulations. Its **Travel Rule** requires crypto businesses to share
sender and recipient information for transactions above a certain
threshold, similar to how traditional financial institutions operate.

Chapter 13:

1.  Controlling Access to Assets

    a.  In additional to personnel, assets can be these:

        i.  Information: Logical access controls attempt to prevent
            > unauthorized access to the information.

        ii. Systems: IT systems that provide one or more services like a
            > simple file server that stores user files is a system.
            > Additionally, a web server working with a database server
            > to provide an ecommerce service is a system. Permissions
            > assigned to user and system accounts **control system
            > access**.

        iii. Devices: computing system (like routers, switches,
             > smartphones, and external devices such as printers).
             > Organizations have increasingly adopted policies allowing
             > employees to connect their personally owned devices (such
             > as smartphones or tablets) to an organization's network.
             > Although the employees may own the devices,
             > organizational data stored on the devices is still an
             > asset of the organization.

        iv. Facilities: physical location that it owns or rents
            > (individual rooms, entire buildings, or whole complexes of
            > several buildings). **Physical security controls** help
            > protect facilities.

        v.  Applications: provide access to an organization's data.
            > Permissions are an easy way to restrict logical access to
            > applications and be assigned to specific users or groups.

2.  Controlling Physical and Logical Access

    a.  Physical Security Requirements (Chapter 10):

        i.  Perimeter security controls: fences, gates, guards,
            > turnstiles

        ii. Environmental controls: HVAC and fire suppression.

        iii. Organizations often have a server room where servers are
             > running (commonly have routers and switches).

        iv. Desktop computers typically aren't as valuable as servers,
            > but regular physical security controls such as locks
            > provide protection.

    b.  Logical access controls: used to protect access to information,
        > systems, devices, and applications. They includes these:

        i.  Authentication

        ii. Authorization

        iii. Permissions

             Similarly, they restrict access to configuration settings
             on systems and network devices to only authorized
             individuals. Many of these logical access controls can
             apply to resources on site or in the cloud.

3.  The CIA Triad and Access Controls.

4.  Managing Identification and Authentication

    a.  Identification: A core principle with authentication is that all
        > subjects must have unique identities.

    b.  Authentication: the authentication information used to verify
        > identity is private and needs to be protected. As an example,
        > passwords are rarely stored in clear text within a database.

    c.  The roles of subject and object can switch back and forth (like
        > programs, services, and computers for example).

    d.  Registration, Proofing, and Establishment of Identity

        i.  Acceptable documentation for in-person identity proofing
            > includes: passport, driver's license, birth certificate,
            > and more.

        ii. After verifying the documents, employees (from the HR
            > department) begin the registration process.

        iii. Online organizations often use knowledge-based
             > authentication (KBA) for identity proofing of someone
             > new.

        iv. Cognitive password (security questions): used when a known
            > user is trying to change a password. One flaw is that the
            > information is often available on social media sites or
            > with internet searches. **NIST SP-800-63B** "Digital
            > Identity Guidelines: Authentication and Lifecycle
            > Management" discourages using these static questions.

        v.  Authorization and Accoutability: Identification and
            > authentication are "all-or-nothing" aspects of access
            > control. Either a user's credentials prove a professed
            > identity, or they don't. In contrast:

            1.  Authorization: occupies a wide range of variations. For
                > example, a user may be able to read a file but not
                > delete it, or they may be able to print a document but
                > not alter the print queue.

            2.  Accountability: like auditing, logging, and monitoring
                > to ensure subjects can be held accountable.

        vi. Authentication Factors Overview:

            1.  Something you know (type 1 authentication factor): like
                > password, PIN, or passphrase.

                a.  Authoritative password recommendations:

                    i.  NIST SP-800-63B, "Digital Identity Guidelines:
                        > Authentication and Lifecycle Management"

                        1.  Password must be hashed

                        2.  Passwords should not expire

                        3.  Users should not be required to use special
                            > characters: NIST analyzed breached
                            > password databases and discovered that
                            > special characters in passwords didn't
                            > provide the desired benefits.

                        4.  Users should be able to copy and paste
                            > passwords.

                        5.  Users should be able to use all characters

                        6.  Password length should be at least eight
                            > characters and as many as 64 characters

                        7.  Password systems should screen passwords

                            We occasionally visit government websites
                            that requires passwords based on old advice.
                            As an example, one government contracting
                            website still includes the following rules:

<!-- -->

a)  Password expire after 60 days

b)  Password must be at least 15 characters

c)  Password must contain at least one uppercase letter

d)  Passwords must contain at least one lowercase letter

e)  Passwords must contain at least one number

f)  Passwords must contain at least one special character.

    i.  Payment Card Industry Data Security Standards (PCI DSS) version
        > 3.2.1

        1.  Password expire at least every 90 days.

        2.  Passwords must be at least seven characters long

    <!-- -->

    1.  Something you have (type 2 authentication factor): smartcard,
        > hardware token, memory card, or USB drive.

        a.  Smartcard (credit card-size ID or badge): has an integrated
            > circuit chip embedded in it. It's tamper-resistant and
            > provide users with an easy way to carry and use complex
            > encryption keys.

        b.  Tokens (token device or hardware token): password-generating
            > device that user can carry with them. Common token used
            > today includes a display that shows a six- to eight-digit
            > number. An authentication server stores the details of the
            > token, so at any moment, the server knows what number is
            > displayed on the user's token. It uses dynamic OTP
            > (onetime passwords).

            i.  Synchronous Dynamic Password Tokens: They generate a new
                > PIN periodically, such as every 60 seconds, requiring
                > the token and the server to have accurate time. A
                > common way this is used is by requiring the user to
                > enter a username, a static password, and the PIN into
                > a web page. Other times, the system prompts users to
                > enter the PIN after first entering their username and
                > password.

            ii. Asynchronous Dynamic Password Tokens: generates PINs
                > based on an algorithm and an incrementing counter.

            iii. Hardware tokens do have failings. If the battery dies
                 > or the device breaks, the user won't be able to gain
                 > access. Some provide the PIN via a software
                 > application running on the user's device
                 > (**Symantec** for example).

    2.  Something you are: fingerprints, face scans, retina patterns,
        > iris paterns, and palm scans (biometric factors).

        a.  False Rejection Rate, FRR (type I error)

        b.  False Acceptance Rate, FAR (type II error)

        c.  Crossover error rate, CER (or equal error rate ERR): the
            > point where the FRR and FAR percentages are equal. Lower
            > CERs means higher accuracy.

            Biometric devices can be ineffective or unacceptable due to
            factors known as enrollment time, throughput rate, and
            acceptance. During enrollment, a subject's biometric factor
            is sampled and stored in the device's database. These stored
            sample is known as **reference profile** (or reference
            template).

            In general, enrollment times over 2 minutes are
            unacceptable. Also, user may enroll again at regular
            intervals, adding inconvenience.

    <!-- -->

    i.  Addition to authentication factors above, we also have:

        1.  Somewhere you are: geographic location identified by an IP
            > address or a phone number identified by Caller ID.

        2.  Context-Aware Authentication: many MDM systems use this. If
            > the user meets all the requirements (location, time, and
            > type of device in this example), it allows the user to log
            > on using the other methods, such as with a username and
            > password.

    ii. Multifactor Authentication: must be different factors (password
        > and a PIN is not multifactor authentication because both are
        > from a single authentication factor) used to authenticate at
        > the same time.

    iii. Two-Factor Authentication (2FA) with Authenticator Apps: for
         > example, Microsoft Authenticator or Google Authenticator.
         > Consider this context: You open Google Authenticator on your
         > smartphone and see a six-digit PIN displayed. After entering
         > the six-digit PIN, you have access. In this scenario, your
         > smartphone is effectively mimicking a hardware token, making
         > this two-factor authentication, though many organizations
         > such as Google call it two-step authentication. This process
         > typically takes advantage of the following standards:

         1.  HOTP: HMAC-based OTP. It's similar to the asynchrounous
             > dynamic passwords created by tokens. The HOTP value
             > remains valid until used.

         2.  TOTP: The Time-based OTP. It uses timestamp and remains
             > valid for a certain time frame. It's similar to the
             > synchronous dynamic passwords used by tokens.

    iv. NIST Deprecates SMS for 2FA: the method of using SMS to send
        > users a text with the PIN has a problem (but still better than
        > just using a password). NIST SP 800-63B has pointed out
        > several vulnerabilities with using SMS for two-step
        > authentication and deprecated its use for federal agencies.

        1.  If an attacker stole the smartphone or tablet, they would
            > have access to the PIN

        2.  Attacker may be able to convince a mobile operator to
            > redirect SMS messages to an attacker's devices (possible
            > via SIM card fraud). If successful, attackers may be able
            > to intercept SMS messages.

    v.  Password Authentication: static passwords are the weakest form
        > of authentication. Worse, as IT departments attempt to force
        > users into creating longer and more complex passwords with
        > expiration dates, users engage in risky behavior like writing
        > down their passwords or creating weaker passwords.
        > **Passwordless** authentication allows users to log into
        > systems without entering a password.

        1.  Fast Identity Online (FIDO) Alliance: an open industry
            > association with a stated mission of reducing the
            > over-reliance on passwords. They have created recommended
            > frameworks and protocol standards: the FIDO2 project (now
            > known as Web Authentication or WebAuthn) and the World
            > Wide Web Consortium (W3C). Some of the problems they've
            > identified with passwords are these:

            a.  Users have as many as 90 online accounts

            b.  Up to 51 percent of passwords are reused

            c.  Passwords are the root cause of over 80 percent of data
                > breaches

            d.  Users abandon one-third of online purchases due to
                > forgotten passwords

    vi. Device Authentication: More and more employees are bringing
        > their own mobile devices to work and hooking them up to the
        > network. These devices aren't necessarily able to join a
        > domain, but it's possible to implement device identification
        > and authentication methods.

        1.  Device fingerprinting: Users can register their devices with
            > the organization and associate them with their user
            > accounts. The device authentication system then captures
            > the characteristics of the device (often accomplished by
            > having the user access a web page with the device). The
            > registration system then identifies the device using
            > attributes such as the operating system and version, web
            > browser, browser fonts, browser plug-ins (extensions),
            > time zone, data storage, screen resolution, cookie
            > settings, and HTTP headers. Even though some of these
            > characteristics change over time, this has proven to be a
            > successful device authentication method. Organizations
            > often use third-party tools like SecureAuth Identity
            > Provider (IdP). MDM systems use contexts-aware
            > authentication methods to identify devices. **802.1X** is
            > another method used for device authentication (implemented
            > by MDM or NAC solutions).

    vii. Service Authentication:

         1.  Many services require authentication. A service account is
             > simply a user account that an administrator created for a
             > service or application instead of a person.

             a.  It's common to create a service account for third-party
                 > tools monitoring email in Microsoft's Exchange
                 > Server. These third-party tools typically need
                 > permission to scan all mailboxes looking for spam,
                 > malware, potential data exfiltration attempts, and
                 > more.

             b.  Service account has a high level of privileges,
                 > administrators configure it with a strong, complex
                 > password that is changed more often than regular
                 > users. However, administrators need to change these
                 > passwords manually. Another option is to configure
                 > the account to be noninteractive, which prevents a
                 > user from logging onto the account using traditional
                 > logon methods.

             c.  Services can be configured to use certificate-based
                 > authentication (issued to the device running the
                 > service and presented by the service when accessing
                 > resources. Web-based services often use API methods
                 > to exchange information between systems. These API
                 > methods are different depending on the web-based
                 > service.

    viii. Mutual Authentication: When a client access a server, both the
          > client and the server provide authentication. Another
          > example is when employees are connecting to a company
          > network while working from home, they typically connect to a
          > VPN server.

<!-- -->

5.  Implementing Identity Mangement (IdM): IdM techniques generally fall
    into two categories:

    a.  Centralized access control: a single entity within a system
        > performs all authorization verification. A small team or
        > individual can manage centralized access control. They can
        > scale up to support more users. However, it creates a **single
        > point of failure**. Microsoft Active Directory is one example.

    b.  Decentralized access control (also known as distributed access
        > control): various entities located throughout a system perform
        > authorization verification. It requires multiple teams or
        > individuals and higher **administrative overhead** (day-to-day
        > cost services without real productivity). Changes made to any
        > individual access control point need to be repeated at every
        > access point. Maintenance becomes difficult.

    c.  SSO: a centralized access control technique. It's convenient for
        > users but it also has security benefits: users don't have to
        > remember multiple usernames and passwords, and users are less
        > likely to write down a single password. SSO also eases
        > administration by reducing the number of accounts required for
        > a subject. However, once an account is compromised, an
        > attacker gains unrestricted access to all of the authorized
        > resources. Most SSO systems include methods to protect user
        > credentials:

        i.  LDAP and Centralized Access Control: a directory service is
            > a centralized database that include information about
            > subjects and objects. Many directory services are based on
            > the Lightweight Directory Access Protocol (LDAP). For
            > example, the Microsoft Active Directory Domain Services
            > (AD DS) is LDAP based. You can think of an LDAP directory
            > as a telephone directory for network services and assets.
            > Users, clients, and processes can search the directory
            > service to find where a desired system or resource
            > resides. Subjects must authenticate to the directory
            > service before performing queries and lookup activities.
            > Even after authentication, the directory service will
            > reveal only certain information to a subject, based on its
            > assigned privileges. Multiple domains and trusts are
            > commonly used in access control systems. A security domain
            > is a collection of subjects and objects that share a
            > common security policy, and individual domains can operate
            > separately from other domains. **Trusts** are established
            > between the domains to create a security bridge and allow
            > users from one domain to access another domain's
            > resources. Trusts can be one-way only, or they can be
            > two-way.

        ii. LDAP and PKIs: A public key infrastructure (PKI) uses LDAP
            > when integrating digital certificates into transmissions.
            > There are many times when clients need to query a
            > certificate authority (CA) for information on a
            > certificate, and LDAP is one of the protocols used. LDAP
            > and centralized access control systems can be used to
            > support SSO capabilities.

        iii. SSO and Federated Identities: Cloud-based applications use
             > federated identity management (FIM) systems, which are a
             > form of SSO. A federated identity links a user's identity
             > in one system with multiple identity management systems.

             1.  FIM extends this beyond a single organization. Multiple
                 > organizations can join a federation or group, where
                 > they agree to share identity information. They can
                 > use this federated identity to access resources in
                 > any other organization within the group.

             2.  A federation can be composed of multiple networks
                 > within a single university campus, numerous college
                 > and university campuses, multiple organizations
                 > sharing resources, or any other group that can agree
                 > on a common federated identity management system.

             3.  Each organization decides what resources to share.
                 > Administrators manage these details behind the
                 > scenes, and the process is usually transparent to
                 > users. The important point is that users don't need
                 > to enter their credentials again.

             4.  A challenge with multiple companies communicating in a
                 > federation is finding a common language. Chapter 14
                 > discusses the methods used to implement federated
                 > identity management systems. These include Security
                 > Assertion Markup Language (SAML), OAuth, and OpenID
                 > Connect (OIDC).

             5.  Cloud-Based Federation: typically uses a third-party
                 > service to share federated identities. As an example,
                 > many corporate online training websites use federated
                 > SSO systems. When the organization coordinates with
                 > the online training company for employee access, they
                 > also coordinate the federated access details. A
                 > common method is to match the user's internal login
                 > ID with a federated identity. Users log on within the
                 > organization using their normal login ID. When the
                 > user accesses the training website with a web
                 > browser, the federated identity management system
                 > uses their login ID to retrieve the matching
                 > federated identity. If it finds a match, it
                 > authorizes the user access to the web pages granted
                 > to the federated identity.

             6.  On-Premise Federation: federated identity management
                 > systems can be hosted on-premises, in the cloud, or
                 > in a combination of the two as a hybrid system.
                 > Imagine Acme merges with Emca. Both companies have
                 > their own networks and SSO systems. However,
                 > management wants employees to be able to access
                 > resources in both networks without logging on twice.
                 > By creating an on-premises federated identity
                 > management system, both companies can share
                 > authentication data. This system allows users to
                 > continue to log on normally, but they will also have
                 > access to the other company's network resources. An
                 > on-premises solution provides the organization with
                 > the most control.

             7.  Hybrid Federation: a combination of a cloud-based
                 > solution and an on-premises solution. Imagine Acme
                 > has a cloud-based federation providing employees with
                 > online training. After the merger with Emca, they
                 > implement an on-premises solution to share identities
                 > with the two companies. This approach doesn't
                 > automatically give employees from Emca access to the
                 > training sites. However, it's possible to integrate
                 > the existing on-premises solution with the training
                 > sites' cloud-based solution. This creates a hybrid
                 > solution for Emca employees and, as with other
                 > federated solutions, provides SSO for Emca employees.

             8.  Just-in-time (JIT): Some federated identity solutions
                 > support JIT provisioning. These solutions
                 > automatically create the relationship between two
                 > entities so that new users can access resources. A
                 > JIT solution creates the connection without any
                 > administrator intervention. With JIT provisioning,
                 > employees log on normally to their employer's
                 > network. The first time the employee accesses the
                 > benefits site, the JIT system exchanges data with the
                 > employer's network and creates the employee's
                 > account. JIT systems commonly use SAML to exchange
                 > the required data. SAML provides entities with a lot
                 > of flexibility to exchange a wide assortment of data.
                 > The process starts with the third party verifying the
                 > user is logged onto a trusted organization's network.
                 > The employer's network then sends data on the
                 > employee, such as the username, first and last name,
                 > email address, and any other information needed by
                 > the third party.

        iv. Credential Management Systems: provide storage space for
            > usernames and passwords. The W3C published the Credential
            > Management Level 1 API as a working draft in January 2019.
            > Many web browsers have adopted the API for credential
            > management. The API provides several benefits that
            > developers can implement **programmatically**:

            1.  Offering to store the user's credentials after logging
                > on

            2.  Showing an account chooser, allowing the user to skip
                > forms

            3.  Automatically logging the user on in subsequent visits,
                > even if the session has expired.

                Some federated identity management use the Credential
                Management API, allowing different web applications to
                implement SSO solutions using a federated identity
                provider (like you can use Google or Facebook account to
                sign in to Zoom).

                Identity as a service, or identity and access as a
                service (IDaaS), is a third-party service that provides
                identity and access management. IDaaS effectively
                provides SSO for the cloud and is especially useful when
                internal clients access cloud-based software as a
                service (SaaS). Users log into their Google account
                once, and it provides them access to multiple Google
                cloud-based applications without requiring users to log
                in again. For example, Office 365 provides Office
                applications as a combination of installed applications
                and SaaS applications. Users have full Office
                applications installed on their user systems, which can
                also connect to cloud storage using OneDrive. This
                allows users to edit and share files from multiple
                devices. When people use Office 365 at home, Microsoft
                provides IDaaS, allowing users to authenticate via the
                cloud to access their data on OneDrive. When employees
                use Office 365 from within an enterprise, administrators
                can integrate the network with a third-party service.
                For example, Centrify provides third-party IDaaS
                services that integrate with Microsoft Active Directory.
                Once configured, users log onto the domain and access
                Office 365 cloud resources without logging on again.

        v.  
