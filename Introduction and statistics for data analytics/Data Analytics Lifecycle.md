### 1.2 Data Analytics Lifecycle 
The Data Analytics Lifecycle is designed specifically for Big Data problems and data
science projects. The lifecycle has six phases, and project work can occur in several
phases at once. For most phases in the lifecycle, the movement can be either forward or
backward. This iterative depiction of the lifecycle is intended to more closely portray a
real project, in which aspects of the project move forward and may return to earlier stages
as new information is uncovered and team members learn more about various stages of the
project. This enables participants to move iteratively through the process and drive toward
operationalizing the project work.

#### What are the Key Roles for a Successful Analytics Project?
* **Business User**: Someone who understands the domain area and usually benefits from
the results. Usually a business analyst, line manager, or deep subject matter expert in the project domain
fulfills this role.
* **Project Sponsor**: Provides the impetus and requirements for the project and defines the core business problem. Generally
provides the funding and gauges the degree of value from the final outputs of the working team. This person sets the priorities for the project and clarifies the desired outputs.
* **Project Manager**: Ensures that key milestones and objectives are met on time and at the expected quality.
* **Business Intelligence Analyst**: Provides business domain expertise based on a deep understanding of the data, key performance indicators (KPIs), key metrics, and business intelligence from a reporting perspective. Business Intelligence Analysts generally create dashboards and reports and have knowledge of the data feeds and sources.
* **Database Administrator (DBA)**: Provisions and configures the database environment to support the analytics needs of the working team.These responsibilities may include providing access to key databases or tables and ensuring the appropriate security levels are in place related to the data repositories.
* **Data Engineer**: Leverages deep technical skills to assist with tuning SQL queries for data management and data extraction, and provides support for data ingestion into the analytic sandboxdata engineer executes the actual data extractions and performs substantial data manipulation to facilitate the analytics. The data engineer works closely with the data scientist to help shape data in the right ways for analyses.
* **Data Scientist**: Provides subject matter expertise for analytical techniques, data modeling, and applying valid analytical techniques to given business problems. Ensures overall analytics objectives are met.

#### Explain Data Analytics Lifecycle.
Figure 2.2 Overview of Data Analytics Lifecycle (Data Science and Big Data Analytics: Discovering, Analyzing, Visualizing and Presenting Data. Wiley Publishing(1st. ed.). 2015.)

* **Phase 1—Discovery**: In this phase, the data science team must learn and investigate the problem, develop context and understanding, and learn about the data sources needed and available for the project. In addition, the team formulates initial hypotheses that can later be tested with data.
  - **Learning the Business Domain**: At this early stage in the process, the team needs to determine how much business or
domain knowledge the data scientist needs to develop models in Phases 3 and 4. The earlier the team can make this assessment the better, because the decision helps dictate the resources needed for the project team and ensures the team has the right balance of
domain knowledge and technical expertise. E.g. Someone with a Ph.D. in life sciences would have deep knowledge of a field of study, such as oceanography, biology, or genetics, with some depth of quantitative knowledge.
  - **Resources**: The team needs to assess the resources available to support the project. In this context, resources include technology, tools, systems, data, and people. In addition to the skills and computing resources, it is advisable to take inventory of the
types of data available to the team for the project. Consider if the data available is sufficient to support the project’s goals. The team will need to determine whether it must collect additional data, purchase it from outside sources, or transform existing data.Ensure the project team has the right mix of domain experts, customers, analytic talent,and project management to be effective. Project managers and key stakeholders have better success negotiating for the right resources at this stage rather than later once the project is underway.
  - **Framing the Problem**: Framing is the process of stating the analytics problem to be solved. At this point, it is a best practice to write down the problem statement and share it with the key stakeholders. As part of this activity, it is important to identify the main objectives of the project, identify what needs to be achieved in business terms, and identify what needs to be done to meet the needs. Perhaps equally important is to establish failure criteria. Most people doing projects prefer only to think of the success criteria and what the conditions will look like when the participants are successful. However, this is almost taking a best-case scenario approach, assuming that everything will proceed as planned and the project team will reach its goals. However, no matter how well planned, it is almost impossible to plan for everything that will emerge in a project. The failure criteria will guide the team in understanding when it is best to stop trying or settle for the results that have been gleaned from the data.
  - **Identifying Key Stakeholders**: During these discussions, the team can identify the success criteria, key risks, and
stakeholders, which should include anyone who will benefit from the project or will be significantly impacted by the project. Depending on the
number of stakeholders and participants, the team may consider outlining the type of activity and participation expected from each stakeholder and participant.
  - **Interviewing the Analytics Sponsor**: Project sponsors may have a predetermined solution that may not necessarily realize the desired outcome. In these cases, the team must use its
knowledge and expertise to identify the true underlying problem and appropriate solution. The data science team can take a more objective approach, as the
stakeholders may have developed biases over time, based on their experience. Also, what may have been true in the past may no longer be a valid working assumption. One
possible way to circumvent this issue is for the project sponsor to focus on clearly defining the requirements, while the other members of the data science team focus on the methods
needed to achieve the goals. Common questions that are helpful to ask during the discovery phase when interviewing the project sponsor are:
    - What business problem is the team trying to solve?
    - What is the desired outcome of the project?
    - What data sources are available?
    - What industry issues may impact the analysis?
    - What timelines need to be considered?
    - Who could provide insight into the project?
    - Who has final decision-making authority on the project?
    - How will the focus and scope of the problem change if the following dimensions
      change:
      - Time: Analyzing 1 year or 10 years’ worth of data?
      - People: Assess impact of changes in resources on project timeline.
      - Risk: Conservative to aggressive
      - Resources: None to unlimited (tools, technology, systems)
      - Size and attributes of data: Including internal and external data sources
   - **Developing Initial Hypotheses**: This step involves forming ideas that the team can test with data. These IHs form the
basis of the analytical tests the team will use in later phases and serve as the foundation for the findings in Phase 5. In this way, the team can compare its answers with the outcome of an experiment or test to generate additional possible solutions to problems. 
Another part of this process involves gathering and assessing hypotheses from stakeholders and domain experts who may have their own perspective on what the problem is, what the solution should be, and how to arrive at a solution.

  - **Identifying Potential Data Sources**: As part of the discovery phase, identify the kinds of data the team will need to solve the
problem. Consider the volume, type, and time span of the data needed to test the hypotheses. In addition, performing data exploration
in this phase will help the team determine the amount of data needed, such as the amount of historical data to pull from existing systems and the data structure.
The team should perform five main activities during this step of the discovery phase:
    - Identify data sources
    - Capture aggregate data sources
    - Review the raw data
    - Evaluate the data structures and tools needed
    - Scope the sort of data infrastructure needed for this type of problem
   
> Unlike many traditional stage-gate processes, in which the team can advance only when specific criteria are met, the Data Analytics Lifecycle is intended to accommodate more
ambiguity. This more closely reflects how data science projects work in real-life situations. For each phase of the process, it is recommended to pass certain checkpoints as
a way of gauging whether the team is ready to move to the next phase of the Data Analytics Lifecycle. The team can move to the next phase when it has enough information to draft an analytics
plan and share it for peer review.
