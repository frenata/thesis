Milestones
* with preconfigured data, be able to see basic visualization reports (configure stack)
* be able to load real data (write ETL module)
* configure more advanced reports
* automated ETL for new documents
* deployment to cloud or onsite

Since it is proposed that the current project will operate in according to an Agile methodology, no comprehensive listing of deliverables is possible, since user stories will be gathered both at project opening througout the project lifecycle. However, the following functionaly milestones are proposed to provide some structure to the anticipated timeline.

At each milestone, certain user stories will be implemented in order to add functianility to the product, but a usable product will be presented for stakeholder feedback as early as the first milestone. In addition to serving the iterative method, this will ensure that important design decisions about UI are not ignored until the last minute.

1. Using preconfigured data in the database, expose some basic visualization reports.

This milestone will focus on configuration of the chosen technology stack in the development environment. Since it is anticipated that most of the work of the project will take place in the ETL (extract, transform, load) of data and visualization of data, these will sidestepped by using preconfigured "dummy" data and simple reports. The primary goal of this milestone is to ensure that the chosen technology stack works without major error and that the basics of stakeholders viewing reports is satisfactory.

2. Implement a software utility to perform the ETL procedure on real data.

This milestone will focus on the building of a software tool to read from existing data documents and perform the ETL process on those documents, finally loading them into the database. This is a large task and the bulk of the software development work in the project, and the software utility will almost certainly undergo further iterations of design and functionality. At a minimum, at this milestone the utility must be able to extract all the text of documents for full text search.

Stakeholders should be given the software utility so they can exercise the workflow for adding documents into the database.

3. Configure more advanced visualization reports.

This milestone will focus on answering some of the key questions posed by project animus. For example: what is the ESLR coverage across all lesson plans. Alongside developing more advanced reports, the data schema will need to be refined to represent more detailed information, and the software utility will need to support this refined schema. 

At this time, stakeholders should be able to interact with the generated reports in an attempt to deteremine usability for business and accreditation purposes.

4. Automate the ETL software utility so that new documents can easily be added to the database as they become available.

This milestone will focus on simplifying the user workflow for adding documents to the database. Ideally, user workflow will be reduced to simply specifying a directory to watch for new documents, however this may be of limited feasibility. 

To ensure that the workflow is working correctly, the existing database will be deleted and stakeholders allowed to setup the automated ETL process.

5. Deploy the database and reporting portal.

This milestone will focus on studying, recommending, and implementing a deployment strategy for the organization. Possible deployments are to cloud based storage or an on-site server. Te be studied are questions about cost, data privacy, and availability.

Stakeholders will be apprised of various options and be allowed to use the deployed product.
