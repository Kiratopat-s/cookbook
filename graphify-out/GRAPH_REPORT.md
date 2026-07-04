# Graph Report - cookbook  (2026-07-04)

## Corpus Check
- 2 files · ~978 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 9 nodes · 7 edges · 2 communities
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `ef5c3810`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- [[_COMMUNITY_Site Instructions|Site Instructions]]
- [[_COMMUNITY_Publishing Index|Publishing Index]]

## God Nodes (most connected - your core abstractions)
1. `Project Instructions` - 4 edges
2. `DevSecOps Cookbook Knowledge` - 3 edges
3. `Site Shape` - 1 edges
4. `Content Conventions` - 1 edges
5. `Quality Bar` - 1 edges
6. `Structure` - 1 edges
7. `Publishing` - 1 edges

## Surprising Connections (you probably didn't know these)
- None detected - all connections are within the same source files.

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Static Self-Contained GitHub Pages Model** — agents_static_github_pages_site, agents_standalone_html_pages, agents_no_build_system_or_shared_runtime, readme_static_github_pages_cookbook, readme_self_contained_html_pages, readme_no_build_step_required, index_standalone_html_page, index_inline_page_specific_css [INFERRED 0.95]
- **DevSecOps Cookbook Topic Scope** — agents_devsecops_topic_scope, readme_devsecops_topic_scope, index_cookbook_topics, index_cli_usage, index_security_scanning, index_ci_cd, index_kubernetes, index_cloud_identity [INFERRED 0.85]
- **Recipe Documentation Pattern** — agents_devsecops_recipe_page_structure, agents_copy_pasteable_commands, agents_safety_notes, index_tool_recipes, index_workflow_playbooks, index_command_patterns [INFERRED 0.85]

## Communities (2 total, 0 thin omitted)

### Community 1 - "Site Instructions"
Cohesion: 0.40
Nodes (4): Content Conventions, Project Instructions, Quality Bar, Site Shape

### Community 5 - "Publishing Index"
Cohesion: 0.50
Nodes (3): DevSecOps Cookbook Knowledge, Publishing, Structure

## Knowledge Gaps
- **5 isolated node(s):** `Site Shape`, `Content Conventions`, `Quality Bar`, `Structure`, `Publishing`
  These have ≤1 connection - possible missing edges or undocumented components.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What connects `Site Shape`, `Content Conventions`, `Quality Bar` to the rest of the system?**
  _5 weakly-connected nodes found - possible documentation gaps or missing edges._