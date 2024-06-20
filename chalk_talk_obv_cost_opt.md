## Agenda
- Exercise in obvious spend (what does obvious mean)
- Break into groups
- Ice Breaker
- Non obvious optimizations

### Obvious spend optimizations
- Commited use discount plans (reservations)
    - Breaking plans into smaller chunks
- Turning off compute on nights and weekends
- Removing unused instances
- Orphaned resources (detached, etc.)
- Intelligent tiers

### Non-Obvious spend opt
- Engineers unaware they use multiple tools for the same thing
- Redundant logging
- Adopting ARM 
- Type of logging
- Awareness of pricing changes
- Innefective auto-scaling configurations
- Turning off special features in dev/qa environments
- Language choice in function apps (Go can potentially be much cheaper than Python)
- Write/Read optimization?

### Group non-obvious optimizations
- Reduce Log Analytics collection (huge cost savings)
- Change Log retention
- Store archival logs in archival storage accounts
    - Log analytics -> ETL -> STD Storage Account
- Deletion of empty app service plan

- Topinomics?

- Terraform tagging on deploy - start/stop
- Shut down shit that isn't tagged!
- opt out tagging for ephemerality

- snapshot schedules

- ranking value of storage
    - Tags maybe?
- productizing data sources
    - actually serving this data to who needs to see it

### Large group best of
- Consolidating licensing
- Truncating storage
- Gamification
    - Public shaming
    - Sustainability gamification
        - 'Our resources have a lower carbon footprint than yours!'
- Unused capacity reservations
- Large scale shutdown in dev - aggressive approach