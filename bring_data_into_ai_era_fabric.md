- FinOps requires a lot of sources in Azure (any cloud)

## Leveraging FinOps Data
### Challenges
#### Analyze data at scale
- How can I manage growing data volume
- How can I simplify data analysis
- HOw can I integrate multiple data sources
#### Derive insights
- How can I make the 

# Fabric
- `Note From Jackson`
    - They don't specify, but Fabric's technology for allowing real-time access to data sources without actually copying data is called `data virtualization`. It could be interesting to try our hand at this technique ourselves.
- Office for your orgs data
## Capabilities

## Intelligent data foundation

## Demo / Case Study / How-To
1. Set up exports in Focus (naturally) and frequency
2. Configure Dataset in one place
3. Set up storage destination
    - Azure data lake
    - Choose file format (csv, parquet)
    - Compression y/n
    - File override
        - Makes sure there are no duplicate exports
4. Backfill Historical Data
    - Select any export job and pick whatever start - end dates you want
5. Fabric integration
    - Setup a Lakehouse
        - Placeholder to bring all of your data together
6. Connect ADLS datasets to Lakehouse
    - Bring data from any source using shortcuts
    - No data movement pipelines
    - Result is one copy across all data sources
    - Connect organization hierarchy for access control
7. PowerBI
    - AI-driven report creation is possible
    - Data Activator for monitoring and alerts
        - Allows you to monitor data streams
        - Can setup alerts for specific data points
            - Email, Teams, Power-Automate 
    - Power Automate for workflows
8. Use copilot to extract insights
    - Can gain insights at any level (org, teams, etc.)

## Compute engines for big-data analysis
- `Spark job (wtf is spark)`