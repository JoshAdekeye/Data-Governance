# Ataccama ONE Documentation References

This directory contains documentation references for integrating Ataccama ONE with Git version control and collaboration workflows.

## Git Integration

Ataccama ONE Desktop provides built-in EGit integration for versioning data quality projects directly in GitHub repositories.

### Official Documentation

- **[Git Integration (Official)](https://docs.ataccama.com/one-desktop/latest/projects/git.html)**  
  Complete guide for adding repositories, committing changes, and pushing from ONE Desktop to enable versioning in GitHub.

- **[Collaboration & Version Control Overview](https://docs.ataccama.com/one-desktop/latest/projects/collaboration-and-version-control.html)**  
  Broader collaboration models covering Git vs SVN workflows and team development patterns.

### Community Resources

- **[ONE Desktop Git Integration (Community)](https://community.ataccama.com/master-data-management-reference-data-management-92/one-desktop-git-intergration-382)**  
  Field tips and gotchas beyond the official documentation, shared by practitioners.

- **[Integrating Git with Orchestration Server](https://community.ataccama.com/data-quality-catalog-94/integrating-git-with-orchestration-server-1230)**  
  Deployment guidance for self-managed environments and production workflows.

## Best Practices

- Use ONE Desktop's built-in Git integration rather than external Git tools
- Structure DQ projects with clear folder hierarchies for easy collaboration
- Leverage branch strategies for environment promotion (dev → test → prod)
- Document data quality rules and profiling configurations within project READMEs

## Project Structure

Ataccama ONE projects typically include:
- Data quality plans and rules
- Profiling configurations
- Matching and consolidation logic
- Custom transformations and algorithms
- Metadata and lineage definitions

*Note: Ataccama ONE source code is proprietary. This documentation focuses on Git integration patterns and collaboration workflows.* 