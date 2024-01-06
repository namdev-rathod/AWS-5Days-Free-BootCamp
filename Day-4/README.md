# Day-4
> Agenda

- VPC
    - Day To Day Activities
        - Create & Manage VPC
        - Nat Gateway management
        - VPC Peering
        - VPC Endpoints

- Migration
    - What is the migration?
        - Migrate resources from one location to another location.

    - Why we migrate?
        - Cost
        - Performance
        - Scalability
        - Quick Deployment
        - Quick Infra Provision

    - Where to migrate?
        - On-Premises --> Any Cloud
        - Cloud --> Cloud
        - Cloud --> On-Premises
    - What resources need to migrate?
        - Application (Servers/EC2)
        - Database (MySQL, PostGreSQl, MSSQL)

    - Migration Types

        - Rehost (Lift & Shift)
            - Use Cases
                - No any application changes required 
                - Urgent migration needed
                - legacy application on prem to Cloud
                - when quick migration needed

        - Replatform/Refactor (lift, optimize, shift)
            - make a application related changes for better performance
            - optimize for cloud native features

        - Re-Architect (Redesign)
            - Restructure the application for better performance 
            - To get maximum cloud native benefits
            - Use Microservices or or complete modernization

        - Retire
            - Identify and decomission unnecessary application or services
            - Reduce cost to delete unnecessary infrastructure resources

     - Tools To Use For Migration
        - Server Migration Service
        - AWS Migration Hub
        - AWS Application Discovery Service
        - CloudEndure 
        - Database Migration Service
        - DataSync
        - Snowball(For larger data)

    - Migration Planning
        - Discovery & Planning
        - Before migration collect all the relevent information for source infra, app, database details
        - Plan submission to authorized person like Managers, DM/DH etc
        - Take Client Approvals
        - Create Jira tickets to track migration status
        - Proof of Concept(PoC)
        - Maintain Migration Documentation
        - Keep Rollback Plan
        - Migrate Application & Database
        - Ensure no single data will loose during migration
        - Fine tune application and infrastructure whereever possible for cost saving and better performance
        - Do proper testing and validate data
        - Maintain infra and application security
        - Place monitoring

    - Post Migration Activity
        - Ensure migrated application and database are working fine
        - Ensure application or database performance is not slow
        - Continously monitor application, database performance 
        - Apply cost saving plan for long term resources like EC2, RDS etc
        


                

