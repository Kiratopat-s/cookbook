# Graph Report - .  (2026-07-04)

## Corpus Check
- Corpus is ~978 words - fits in a single context window. You may not need a graph.

## Summary
- 43 nodes · 55 edges · 7 communities
- Extraction: 75% EXTRACTED · 25% INFERRED · 0% AMBIGUOUS · INFERRED: 14 edges (avg confidence: 0.87)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_DevSecOps Topics|DevSecOps Topics]]
- [[_COMMUNITY_Site Instructions|Site Instructions]]
- [[_COMMUNITY_Standalone Site Experience|Standalone Site Experience]]
- [[_COMMUNITY_CLI Tool Examples|CLI Tool Examples]]
- [[_COMMUNITY_Recipe Patterns|Recipe Patterns]]
- [[_COMMUNITY_Publishing Index|Publishing Index]]
- [[_COMMUNITY_Page Styling|Page Styling]]

## God Nodes (most connected - your core abstractions)
1. `Project Instructions` - 12 edges
2. `DevSecOps Cookbook` - 9 edges
3. `Cookbook Topics` - 8 edges
4. `DevSecOps Cookbook Knowledge` - 7 edges
5. `Example DevSecOps Commands` - 4 edges
6. `Cookbook Entries` - 4 edges
7. `Static GitHub Pages Site` - 3 edges
8. `Standalone HTML Pages` - 3 edges
9. `DevSecOps Recipe Page Structure` - 3 edges
10. `DevSecOps Topic Scope` - 3 edges

## Surprising Connections (you probably didn't know these)
- `Static GitHub Pages Site` --semantically_similar_to--> `Static GitHub Pages Cookbook`  [INFERRED] [semantically similar]
  AGENTS.md → README.md
- `DevSecOps Cookbook` --semantically_similar_to--> `DevSecOps Cookbook Knowledge`  [INFERRED] [semantically similar]
  index.html → README.md
- `Standalone HTML Pages` --semantically_similar_to--> `Self-Contained HTML Pages`  [INFERRED] [semantically similar]
  AGENTS.md → README.md
- `index.html Table Of Contents` --semantically_similar_to--> `index.html Cookbook Index`  [INFERRED] [semantically similar]
  AGENTS.md → README.md
- `Copy-Pasteable Commands` --semantically_similar_to--> `Command Patterns`  [INFERRED] [semantically similar]
  AGENTS.md → index.html

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Static Self-Contained GitHub Pages Model** — agents_static_github_pages_site, agents_standalone_html_pages, agents_no_build_system_or_shared_runtime, readme_static_github_pages_cookbook, readme_self_contained_html_pages, readme_no_build_step_required, index_standalone_html_page, index_inline_page_specific_css [INFERRED 0.95]
- **DevSecOps Cookbook Topic Scope** — agents_devsecops_topic_scope, readme_devsecops_topic_scope, index_cookbook_topics, index_cli_usage, index_security_scanning, index_ci_cd, index_kubernetes, index_cloud_identity [INFERRED 0.85]
- **Recipe Documentation Pattern** — agents_devsecops_recipe_page_structure, agents_copy_pasteable_commands, agents_safety_notes, index_tool_recipes, index_workflow_playbooks, index_command_patterns [INFERRED 0.85]

## Communities (7 total, 0 thin omitted)

### Community 0 - "DevSecOps Topics"
Cohesion: 0.29
Nodes (8): DevSecOps Topic Scope, CI/CD, CLI Usage, Cloud Identity, Cookbook Topics, Kubernetes, Security Scanning, DevSecOps Topic Scope

### Community 1 - "Site Instructions"
Cohesion: 0.33
Nodes (7): DevSecOps Cookbook Knowledge Site, Lowercase Kebab-Case Filenames, No Build System Or Shared Runtime, Project Instructions, Relative Links, Safety Notes, Static GitHub Pages Site

### Community 2 - "Standalone Site Experience"
Cohesion: 0.29
Nodes (7): Standalone HTML Pages, DevSecOps Cookbook, DevSecOps Field Notes, Practical Recipe Library, Responsive Accessible Layout, Standalone HTML Page, Self-Contained HTML Pages

### Community 3 - "CLI Tool Examples"
Cohesion: 0.29
Nodes (7): Example DevSecOps Commands, Gitleaks, Gitleaks Secret Search Before Commit, kubectl, kubectl Cluster Context Check, Trivy, Trivy Container Scan Recipe

### Community 4 - "Recipe Patterns"
Cohesion: 0.40
Nodes (6): Copy-Pasteable Commands, DevSecOps Recipe Page Structure, Command Patterns, Cookbook Entries, Tool Recipes, Workflow Playbooks

### Community 5 - "Publishing Index"
Cohesion: 0.50
Nodes (5): index.html Table Of Contents, DevSecOps Cookbook Knowledge, index.html Cookbook Index, No Build Step Required, Static GitHub Pages Cookbook

### Community 6 - "Page Styling"
Cohesion: 0.67
Nodes (3): Plain Semantic HTML, Inline Page-Specific CSS, Page-Specific Styling

## Knowledge Gaps
- **15 isolated node(s):** `DevSecOps Cookbook Knowledge Site`, `Relative Links`, `Lowercase Kebab-Case Filenames`, `Safety Notes`, `DevSecOps Field Notes` (+10 more)
  These have ≤1 connection - possible missing edges or undocumented components.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `DevSecOps Cookbook` connect `Standalone Site Experience` to `DevSecOps Topics`, `CLI Tool Examples`, `Recipe Patterns`, `Publishing Index`, `Page Styling`?**
  _High betweenness centrality (0.526) - this node is a cross-community bridge._
- **Why does `Project Instructions` connect `Site Instructions` to `DevSecOps Topics`, `Standalone Site Experience`, `Recipe Patterns`, `Publishing Index`, `Page Styling`?**
  _High betweenness centrality (0.344) - this node is a cross-community bridge._
- **Why does `Cookbook Topics` connect `DevSecOps Topics` to `Standalone Site Experience`?**
  _High betweenness centrality (0.275) - this node is a cross-community bridge._
- **Are the 2 inferred relationships involving `Cookbook Topics` (e.g. with `DevSecOps Topic Scope` and `DevSecOps Topic Scope`) actually correct?**
  _`Cookbook Topics` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `DevSecOps Cookbook Knowledge Site`, `Relative Links`, `Lowercase Kebab-Case Filenames` to the rest of the system?**
  _15 weakly-connected nodes found - possible documentation gaps or missing edges._