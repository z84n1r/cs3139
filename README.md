java c
INFOSYS 220 ASSIGNMENT   2
REQUIREMENT   MODELLING
Semester   2   2024   Individual Assignment
ASSIGNMENT GUIDELINES
OBJECTIVE
To demonstrate your understanding of UML modelling and functional requirements as part   of the   deliverables in a   System   Proposal.
SUBMISSIONSubmit a single .pdf file for all tasks and   the   original   use   case   diagram   file   or   URL   (e.g.   filename.mdl   file or link from draw.io) to Canvas before the assignment due date and time.   No printed   submission   is   required.
ASSIGNMENT TASKS
BACKGROUNDYour business case   has   been accepted, and the   project   is   moving forward   into the next   phase   of the   SDLC.   In the   first   phase, you   conducted   preliminary   investigations,   performed   a   series   of facts   and   findings, and deployed techniques for elicitation. The requirements listed below document business   requirements,   processes,   assumptions,   and   constraints.   Complete   this   assignment   using   the   given   requirement   sets   and   complete   the   tasks   as   listed.   You   are   a   business   analyst   for   this   project   and   are tasked to   prepare the   ‘Requirement   Package’   .Below   are   the   notes   taken   while   fact-finding   during   the   planning   phase.   These   are   organised   to   capture    the    generic requirements    that    will apply for any combination of partnerships    formed   between   ECS   and   one   or   more   businesses   from   the   listed   industries   using   Webbie   webportal   with   customisation to suit each given partnership. Please provide a new system name for your   submission.
It   has   been finalised that there are 4   key   modules to   be   incorporated for    with   the following:
1.       End    User    Module:    Front-end    user    designed    to    streamline    user-related   functions   for   user   engagement.   In this case, the end   user   is   not   part of   the   business.
2.       Business       Module:       authoring       section         (chosen         industry/business;       this         is       functions       for   businesses to handle all the   basic services for their business-as-usual operations. E.g. content   authoring,   knowledge   base   management.
3.       Management    Module:   administration   and   support   section    (ECS);   ECS   primarily   undertakes   this   module   as   a   product   owner   with   their   staff   to   handle   operations   and   management   of   the web   portal   modules.
4.       Application   and   Delivery   Module:   Business   applications   (External   businesses/systems);   this   involves    any    other    external    businesses      or      systems      that      integrate      with   the      web      portal.   eMissions,   ESL,   Payroll system,   CRM,   Pharmaceutical Schedule, Te   Puna.
Analyse the given   information to fulfil the tasks   assigned within   the   analysis   phase   (in   no   particular   order):
a.         Role-based access control (RBAC) is adopted for   Webbie. This   is a   policy-neutral   access   control   mechanism    defined    around    roles      and      privileges.    The      components      of      RBAC,      such      as      role   permissions,   user-role   and   role-role   relations,   make   it   simple to   perform   user   assignments.   In   web   portal systems,   role-based   access control   (RBAC) or   role-based security   is   an   approach to   restricting   system   access   to   authorized   users.    RBAC    is    managed    by    ECS   staff   and   this    user   membership function   is apart of the standard setup with   ongoing support   built   in   for   the   web   portal.


b.       Sign-up    is   the    authentication   and    identification   component   of   the   web    portal.   The   sign-up   feature   allows   new   users   to   create   an   account   and   gain   access   to   the   system’s   services.   It   provides a secure, user-friendly process to ensure a smooth   onboarding   experience.   Customer   loyalty points system is a component available to be   incorporated   if   needed.   Options to   loyalty   rewards   programme during their first sign-up   or   later.
c.          Multi-tiered   Access   Control    List   (ACL)   is   required   to   host   the   multiple   types   of   membership
chart for Webbie.   Key   roles   are   members, visitors, staff   (ECS),   business owners and   testers:
i.                   End-user: Guest or   Registered   members
ii.                Staff: All   staff with   dedicated   roles   (e.g.   systems   admin,   IT   support,   data   analysts)   
iii.                   Business/Corporate   Owner:   Product owner,   Lead, Champion
iv.                   External Contractor: Testers   in development and   live   environment         
d.       Webbie   has standard services that      the   partnership   can   customise.   These   include:
i.                  Content Authoring,
ii.                   User   sign-up,
iii.                  AI Chatbot for   QA,
iv.                   Daily   posts,   Live events,
v.                   Marketplace with   POS
vi.                   Knowledge   Library and   Reporting,
vii.                  Search engine.
Additional   services   can   be   added   as   an   ad-hoc   request,   including   full   stack   development   and   testing.
e.       Content authoring builds   into the   knowledge   library.   E.g. AI   Chatbot   QA   is   one   of the   services   that   is   shared   between   User   and   Business   users. This   is   a   service   that   allows   members to   ask   questions that will   be answered   by   business owners   and   allocated to   relevant topics.
f.          ECS   used   large language   models   (LLMs) with their   proprietary data, fine-tuning the   model with   their private data and using the customized   LLM asa   knowledge   base. This is   supported   by   ECS   staff for all web   portal services with   AI   capabilities.
g.       Webbie   is the   platform   and   will   allow   full   customisation   of   businesses   or   industries   to   design   user    journey to   match the business       requirement.    Targeting a one system    that      fits       all   businesses/industries   to   allow   ease   of   use   without   compromising   the   user   experience   (UX).   System administration will   be available to grant   access for   all   users.
h.       Business owners   are given   different   access   roles.   Business   owners   can   request   new   services to   be added to each   module. All additional services with   new functions will need to   be developed   and tested   before   it   is   launched for the   business   partnership. Testing   is   high   priority   and   User   Acceptance Testing   (UAT)   is   the   final   phase   in   the   software testing   process   where the   actual   users test the system to ensure it can handle required tasks according to specifications. Testers   will run unit testing    to    confirm    its    functionality. Testers will perform. tests to ensure    the   business requirements and specifications provided during the request for new service are   met.   The   need   to   validate   that   the   new   function   works   as   expected   in   real-world   scenarios   and   conditions   is a   priority.


i.          Content for Webbie   is   created   in   the   corporate   module.   Business   owner   will   add   new   content,   update   and   remove   content   as   required.   All   content   will   be   stored   in   the   content   repository   within the   Corporate   module. Scalable database and   security settings will   be   deployed.
j.          Search    function    is    one    of   the    highlights   of   Webbie.   Search    can    be   done    using   free   text   or   keyword using predefined categories. Search service can be customised to suit the content and   industry/business.
k.       Webbie allows guest access on basic services.   Members will   have additional functions available   according   to   its   membership   type.   (*you   can   list   of appropriate   services   to   suit   your   chosen   industry)
l.          Live   events   and   webinars   are   one   of   the   services   in   Webbie.   These   services   are   only   available   for   registered   members.   Members will enrol   into these   events to   participate.
m.    Staff from ECS will manage the application and development module. This includes adding new   services   and   providing   new   updates.   ECS   will   continue   creating   new   services   to   keep   Webbie   up to date. Staff from   ECS also   maintain the   data   warehouse   and   content   server.
n.       Webbie   is   available   on   standard   web   browsers,   portable tablet   and   smartphones.   Webbie+   is   the app   available on Android   and   iOS   devices.
o.       Customization: members can personalise their dashboard   on   Webbie   and Webbie+. This   is one   of   the   UX   feature   of   the   web   portal.   Personalisation   can   be   by   selecting   from   the   library   of   themes, options of colours as   well   as   design your   own   logos   and   patterns.
p.       Membership:   Signing    up   will   need   a   valid   email   address   and/or   a   phone    number.   Activation   code   will   be   sent   to   validate   email.   Option   to   sign   up   loyalty   is   made   available   at   registration   or   to   join    later.    System    administrator    is    a    role    under    staff    that    will    manage    membership,   allocation of   platforms
q.       AI   Chatbot for   QA   platform   is   a   service   available to   all   members to   post   questions   by topics.   Business owners will be assigned to answer questi代 写INFOSYS 220 ASSIGNMENT 2 REQUIREMENT MODELLING Semester 2 2024
代做程序编程语言ons posted. QA feature has a choice of   two:   performed   by enabling the AI Chatbot or via   real-time video   conference/call.
r.          A   unique   request   number will   be   issued for   each   new   service   request from   a   business   owner.   All   requests will   be   reviewed,   and   if   approved   will   be   developed   and tested.      Business   owners   can   request   new services to   be commissioned. A   notification with   unique   request   number will   be emailed with   a   comment.
s.          ECS   has   contracted   test   analysts from   Comet   Inc.   for   all the testing   work   for   Webbie.   Testers   are   secondedto   ECS   as   are   in   charged   of   all testing   work   required for   all   services   within   each   platform. before the   launch date or go-live. Testing is   rank   high   priority for quality   assurance   of   all   services.
t.          Development       of      all      services      in      Webbie      will      have      a      test      and      a      live      environment.      Test   environment   is   a   shadow   and    mirrors   every    live   environment.   This   is   also    used   as   a   quick   backup to   allow any   replication to   be carried out   if   needed.
u.       Tester   will test   and   each   test   will   need   a   report   generated   to   show   the    results.   Scheduling   of   tests   by testers   needs to   be approved   by the   business   owner   before   it   can   proceed.       Each test   will generate   report when   it   is   run or completed.
v.         Content   uploaded   by   members will   be verified   before   it   is successfully   published.w.      Content is restricted to 2Gb per upload for members. Corporate members will have a 5Gb   limit.x.          Loyalty points cannot   be purchased   nor transferred   between   members.   Points will expire after 12   months.y.       Some   services   are   available   to   all   members   including   guests   while   some   are   only   available   to   registered    members. Online chatting is a service available to member and visitors. Only   members can upload and download files. Visitor can only use   the chat      feature   for   text.
Important: Avoid modelling signup or login for   user   as these   are   not   regarded   as   key function   of   a web   portal   but a requirement for authentication   and   identification   of   users.
You   should   use the   assignment   template   provided   for this   assignment. You   can   download   the template from Canvas.


TASKS
1.       Requirements   Definition   Report   (28   marks)
You   are   required to   prepare   a   requirements definition   report   by:
a.         Re-writing   the   system    requirements   (above)   to   meet   the    requirements   definition   format.
b.       Re-organise      the       re-written      system       requirements      into    functional       (FR)      and      non-   functional   requirements   (NFR).
2.         User Story   (12   marks)
Using the format   of   a   user   story,   pick   2   out   of   3   (of the   actor   options   below)   and   prepare   a   set   of   user stories   (i.e. at   least 3 for   each   actor   selected):
a.         Member
b.         Business owner,   and
c.          ECS   staff.
“As   a   ,   I   want/need   to so   that   /in   order   to”
NOTE: you are expected to create   at   least   3   separate   user   stories for   EACH   of   the   2   chosen   actors.
3.         Use Case   Model   (50   marks)
a.         Draw a   Use   Case   Model from your   Requirements   Definition   Report.
●          Model functional   requirements   (FR) only.
●         Only   model   use   cases with   actors.
b.       Insert your use case   model   into the   correct   section   in the template. Your   model   must   be clearly legible – please also include a link to the original UCM   if   created   on   Draw.io
4.       Use   Case   Documentation   (30   marks)
a.       Write the use case   documentation for one main use case from your model from Task
3. Your documentation   is expected to   be detailed   and well   thought-out.
5.       Activity   Diagrams   (30   marks)
a.         Draw   an   activity   diagram to   demonstrate the   process   for   the   use   case   documented   in Task   4.
●          If your use case includes many branching activities, focus on the main activity.
b.       Insert   your   activity   diagram   into   the   correct   section    in   the   template.   Your   diagram   must   be clearly   legible.
Notes:
●          Mark   penalties will   be   incurred for failure to   meet submission   requirements.


THE   BIGGER   PICTUREAssignment   1   is the first   of   several   assignments   based   on the   given   case   scenario. The   overall task   is to   prepare   a   business   case   of   a   portal   and   present   it   in favour   of your   portal to   be   accepted   and   initiated. This   is   a   part   of the   planning   phase. This   assignment will   allow you   to   experience   the   key   activities   required   to   achieve   preliminary   investigations   required.   To   simplify   the   task   (by   limiting   the   scope),   we   have   asked   each   student   to   prioritise, justify   and   choose from   the   given   areas   and   come up with a specialisation that satisfies the needs of that area. Your project scope should include   the   given   requirements   to   provide   the   information   necessary   to   plan,   analyse,   and   design   a   full-   featured system. This occurs   in the Group Assignment.Assignment 2: This simulate of   part of the analysis   phase.   You   will   explore   an   area   of   the   project   by   modelling   relevant users’ requirements and   relevant   processes. The   use of modelling tools   will   help   you   better   understand what type of solution   is   needed to satisfy   the   business   problem.Group Assignment   Proposal: You will form. groups of 5 with   people from the   same   lab to   work   on   a   proposal   for   a   solution   (system)   for   the   targeted   scope   from   the   given   Case   Scenario.   You   can   combine   your   Assignment   1   and   2   ideas   and   decide   which   of   the   group   members’   ideas   would   be   most   interesting   to   continue   working   on.   You   will   submit   your   system’s   proposal   and    plans   for   approval   before continuing.Group   Assignment   Final   Deliverable:   You   will   design   and   produce   a   prototype   for   the   proposed   solution. You will   be   required to   complete   reports,   models,   and   diagrams to   develop, validate,   and   document your solution’s   prototype.
Presentation:    You    will      present    your      solution      to      your      classmates      and      several      staff       members.   Presentations take   place   in week   11   in your   lab during your   lab time.
CHANGE   HISTORY
2024-07-18:   First   draft      2024-07-31:   Final draft   2024-08-2:   Proofing
2024-08-5:   Released
GLOSSARY:
1.       Te   Puna   is a digital   repository and   management   system   that   stores   and   provides   access   to   a   wide   range of cultural and   heritage   information and   resources.   etc.
2.       Pharmaceutical   Schedule    is   the   pharmaceutical    list   in   New   Zealand.   This   list,   managed   by   PHARMAC   (the   Pharmaceutical   Management   Agency),   details   the   medicines   and   medical   devices that are subsidized   by the   New Zealand government
3.       eMissions    is    the   system    used   by   the    Ministry   for   the    Environment   in    New   Zealand.   This   system   manages and   reports greenhouse gas emissions and   other   environmental   data.
4.       Education    Sector    Logon      (ESL)      is    the      system      used      by    the      Ministry    of      Education      in      New   Zealand.    This    system    provides      secure      access      to      various      online      education      services      and   applications   used   by schools, teachers, and other educational   institutions.
MARK ALLOCATION AND GUIDE
Task
Marking criterion
Mark allocated
1.
Requirements
Definition   Report
●          Requirements    definition    report      is    well    written   and   provided
   
28
2.
User   Stories
●          User stories   are   prepared well and   correctly
12
3.
Use   Case   Model
Consistency with the given scope.
●          No   extra   UC(s) /   actors / elements   present   For   each   main   use case:
●         Actor(s)   presented
●          Use case(s)   presented
●         Correct   relationships   used
   
   
   
25
   
Technical   correctness,e.g.
●         System   boundary   present
●         System well   named
●         Correct   UML   2.0   notation   used
●         Generalisation   used correctly
●          Legible   Model   presented
   
   
   
25
4.
Use   Case
Documentation
Overall       quality       considering       if       a       decent,       thoughtful   attempt   has   been   made.
   
●          Header section   (no errors or   inconsistencies)
●          Detail/thoughtfulness of steps
●          Flow   and   logic
   
   
   
30
5.
Activity   Diagram
Overall technical correctness
●         Consistent with   use case documentation
●          Modelling      rules    followed,         e.g.      correct      use      of   notation
●          Legible   Diagram   presented
   
   
30
Mark   penalties will   be   incurred for failure to   meet submission   requirements.

         
加QQ：99515681  WX：codinghelp
