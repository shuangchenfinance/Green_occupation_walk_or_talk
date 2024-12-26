# List of occupations on susbtantive green transition practices and communication of green images

This dataset is created by Shuang Chen in her following paper.

Chen, Shuang, Green Investors and Green Transition Efforts: Talk the Talk or Walk the Walk? (October 21, 2022). Available at SSRN: https://ssrn.com/abstract=4254894 or http://dx.doi.org/10.2139/ssrn.4254894

The 204 occupations in this dataset are defined as green occupations by the U.S. National Center for O*NET Development as occupations whose work and worker requirements are potentially affected by the greening of economic activities and technologies. There are three different types of impact that greening of the economy can bring to occupations. The 204 occupations are grouped correspondingly: 

(1) Green Increased Demand Occupations. The impact of sustainable economic activities and technologies is an increase in employment demand for an existing occupation. However, this impact does not entail significant changes in the work and worker requirements of the occupation. The work context may change, but the tasks themselves do not. 

(2) Green Enhanced Skills Occupations. The impact of sustainable economic activities and technologies results in a significant change in the work and worker requirements of an existing occupation. The essential purposes of the occupation remain the same, but tasks, skills, knowledge, and external elements, such as credentials, have been altered.

(3) Green New and Emerging Occupations. The impact of sustainable economic activities and technologies is sufficient to create the need for unique work and worker requirements, which results in the generation of a new occupation. This new occupation could be entirely novel or "born” from an existing occupation.

The National Center for O*NET Development provides the 204 green occupations' O*NET-SOC 2010 codes. You can use the Crosswalk from the 2010 code to the 2019 code provided by the O*NET Resource Center to obtain their O*NET-SOC 2019 codes.

Variable name	and Definition:

Efforts:	Type of green transition efforts this occupation contributes to. The value can be Walk or Talk. 

Always:	Dummy variable indicating whether workers employed in this occupation are always related to the environment or depend on context. If they are always related to the environment, the value is 1, otherwise, the value is 0.

ONET Title:	O*NET Title of the occupation in the ONET-SOC 2010 version.

ONET code:	O*NET Code of the occupation in the ONET-SOC 2010 version.

How were Walk and Talk separated?

Although walk-relevant and talk-relevant occupations closely interact and ultimately contribute to the green transition together, they specialize in tasks with distinct characteristics. The important distinction is that talk-relevant occupations do not directly generate environmental impact. Their influence is indirect, typically by supporting the walk-relevant occupations. For example, a public relations specialist managing a pollution scandal does not improve the environment unless other parts of the firm take action. Thus, if most tasks in a green occupation do not directly result in environmental change, it is classified as talk-relevant. Otherwise, it is considered walk-relevant.

For green enhanced skills occupations or green new and emerging occupations, the National Center for O*NET Development provides a list of green tasks involved in each occupation. Green tasks are specific work activities that are impacted by environmentally friendly technologies and practices, aimed at reducing environmental harm, promoting sustainability, or adapting to the evolving green economy. I assess whether most green tasks within an occupation can directly impact the environment. In total, there are 1398 green tasks, covering the entire green transition process. I categorize these tasks into four broad themes: preparation of environment-related metrics, analysis and communication, implementation, and governance of implementation.

Green tasks in the area of "preparation of environment-related metrics" or "analysis for/and communication" do not directly affect the environment, such as emissions metrics auditing, compliance reports, and the marketing of green products. Green tasks in the area of "implementation" or "governance of implementation" directly affect the environment, such as operating bioenergy machines and monitoring their operation. For occupations with less than 50\% of green tasks directly influencing the environment, I consider them talk-relevant occupations. For example, all 16 green tasks involved in the occupation "green marketers" do not directly generate environmental impacts, making it a talk-relevant occupation. 

For green increased-demand occupations, because work tasks remain the same regardless of whether they are employed in a sustainable or traditional economy, they do not have green tasks. However, O*NET OnLine (www.onetonline.org, a database of O*NET occupations sponsored by the US Department of Labor) provides detailed tasks involved in each occupation. I use tasks on O*NET OnLine to evaluate whether most tasks in a green increased demand occupation can directly affect the environment. Only one green increased demand occupation, customer service representatives, is classified as a talk-relevant occupation.

Among the 204 green occupations, some are always environmentally friendly in any context, such as chief sustainability officers and wind energy project managers. The environmental orientation of other occupations depends on the context, such as logistics managers and public relations specialists. Logistics managers can have a positive or negative environmental impact depending on how they work. 

For occupations that are always eco-friendly, if the occupation is walk- (or talk-) relevant, job postings in this occupation are classified as walk- (or talk-) relevant job postings. For occupations whose environmental orientation is context-dependent, job postings in these occupations require further evaluation of the context's environmental orientation.
