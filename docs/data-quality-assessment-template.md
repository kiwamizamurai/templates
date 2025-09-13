<!--
5W1H: Data Quality Assessment Template

WHAT: Systematic evaluation framework for measuring and improving data quality across datasets and pipelines
WHO: Data engineers, data analysts, data stewards, platform teams managing data infrastructure
WHEN: Regular intervals (quarterly), after major data changes, before critical business decisions, during data onboarding
WHERE: Data catalogs, data governance platforms, quality monitoring dashboards, pipeline monitoring systems  
WHY: Ensure data reliability, enable informed data usage decisions, identify improvement opportunities, build trust in data assets
HOW: Define quality dimensions → Measure automatically → Score systematically → Take improvement actions → Monitor continuously

Usage: Apply to any data asset requiring quality assessment - tables, metrics, pipelines, or entire data domains
Example assets: "User Events Table", "Revenue Metrics Dashboard", "ML Feature Store", "Customer Data Pipeline"
-->

# Data Quality Assessment: [Data Asset Name]

## Document Information
- **Created**: [YYYY-MM-DD]
- **Last Updated**: [YYYY-MM-DD]
- **Assessment Period**: [Date Range]
- **Data Steward**: [Name]
- **Technical Owner**: [Name]
- **Status**: [Active | Under Review | Action Required | Archived]

## Executive Summary
Brief overview of the data asset quality status and key findings.

## Data Asset Overview
### Basic Information
- **Asset Name**: [Table/Dataset/Pipeline name]
- **Asset Type**: [Table, View, Dataset, Pipeline, Dashboard]
- **Domain**: [Business area - Marketing, Finance, Product, etc.]
- **Business Criticality**: [Critical | High | Medium | Low]
- **Data Classification**: [Public | Internal | Confidential | Restricted]

### Asset Description
**Purpose**: [What business need this data serves]
**Primary Use Cases**: [How this data is typically used]
**Key Stakeholders**: [Teams/roles that depend on this data]
**SLA Requirements**: [Freshness, availability, accuracy requirements]

## Data Quality Score Summary
### Overall Score: [X]/100 Points

**Quality Grade**: [Great (90-100) | Good (70-89) | Okay (50-69) | Poor (0-49)]

### Dimensional Scores
| Dimension | Score | Weight | Weighted Score | Status |
|-----------|-------|--------|----------------|--------|
| **Accuracy** | [X]/30 | 30% | [X]/30 | [🟢 Good / 🟡 Needs Improvement / 🔴 Poor] |
| **Reliability (Timeliness)** | [X]/25 | 25% | [X]/25 | [🟢 Good / 🟡 Needs Improvement / 🔴 Poor] |
| **Stewardship** | [X]/25 | 25% | [X]/25 | [🟢 Good / 🟡 Needs Improvement / 🔴 Poor] |
| **Usability** | [X]/20 | 20% | [X]/20 | [🟢 Good / 🟡 Needs Improvement / 🔴 Poor] |

## Quality Dimensions Assessment

### 1. Accuracy Dimension (30 points)
**Definition**: Data correctness, completeness, and validity

#### Scoring Components
| Component | Points Available | Points Earned | Status |
|-----------|------------------|---------------|--------|
| **Data Validation Tests** | 10 | [X] | [Pass/Fail] |
| **Schema Compliance** | 5 | [X] | [Pass/Fail] |
| **Referential Integrity** | 5 | [X] | [Pass/Fail] |
| **Completeness** | 5 | [X] | [Pass/Fail] |
| **Consistency Checks** | 5 | [X] | [Pass/Fail] |

#### Detailed Assessment
**Data Validation Results**:
- **Null Rate**: [X%] (Target: <[X%])
- **Duplicate Rate**: [X%] (Target: <[X%])
- **Format Compliance**: [X%] (Target: >[X%])
- **Range Validation**: [X%] of values within expected ranges

**Issues Identified**:
- [Issue 1]: [Description and impact]
- [Issue 2]: [Description and impact]

**Accuracy Trend**: [Improving/Stable/Degrading over past 30 days]

### 2. Reliability (Timeliness) Dimension (25 points)
**Definition**: Data freshness, availability, and pipeline stability

#### Scoring Components
| Component | Points Available | Points Earned | Status |
|-----------|------------------|---------------|--------|
| **SLA Compliance** | 10 | [X] | [Pass/Fail] |
| **Pipeline Stability** | 8 | [X] | [Pass/Fail] |
| **Data Freshness** | 7 | [X] | [Pass/Fail] |

#### Detailed Assessment
**SLA Performance**:
- **Target Freshness**: [X hours/days]
- **Actual Average**: [X hours/days]
- **SLA Compliance Rate**: [X%] (Target: >[95%])

**Pipeline Reliability**:
- **Success Rate (30 days)**: [X%]
- **Average Failure Recovery Time**: [X hours]
- **Failed Runs This Month**: [X]

**Recent Incidents**:
- [Date]: [Brief description of outage/delay]
- [Date]: [Brief description of outage/delay]

### 3. Stewardship Dimension (25 points)
**Definition**: Data governance, ownership, and operational excellence

#### Scoring Components
| Component | Points Available | Points Earned | Status |
|-----------|------------------|---------------|--------|
| **Clear Ownership** | 8 | [X] | [Pass/Fail] |
| **Documentation Quality** | 7 | [X] | [Pass/Fail] |
| **Governance Compliance** | 5 | [X] | [Pass/Fail] |
| **Monitoring Coverage** | 5 | [X] | [Pass/Fail] |

#### Detailed Assessment
**Ownership**:
- **Data Owner Defined**: [Yes/No]
- **Technical Owner Response Time**: [X hours average]
- **Escalation Path Documented**: [Yes/No]

**Governance**:
- **Data Classification Set**: [Yes/No]
- **Privacy Compliance**: [Compliant/Non-compliant/Not Applicable]
- **Retention Policy Applied**: [Yes/No]
- **Access Controls Reviewed**: [Last review date]

### 4. Usability Dimension (20 points)
**Definition**: Data discoverability, understandability, and ease of use

#### Scoring Components
| Component | Points Available | Points Earned | Status |
|-----------|------------------|---------------|--------|
| **Documentation Completeness** | 8 | [X] | [Pass/Fail] |
| **Column/Field Descriptions** | 6 | [X] | [Pass/Fail] |
| **Usage Examples** | 3 | [X] | [Pass/Fail] |
| **Query Performance** | 3 | [X] | [Pass/Fail] |

#### Detailed Assessment
**Documentation Quality**:
- **Table/Dataset Description**: [Complete/Partial/Missing]
- **Column Descriptions**: [X%] of columns documented
- **Business Logic Explained**: [Yes/No]
- **Sample Queries Provided**: [Yes/No]

**User Experience**:
- **Average Query Response Time**: [X seconds]
- **User Feedback Score**: [X]/5 (if available)
- **Common Usage Patterns Documented**: [Yes/No]

## Historical Trends
### Score Evolution (Last 6 Months)
| Month | Overall Score | Accuracy | Reliability | Stewardship | Usability |
|-------|---------------|----------|-------------|-------------|-----------|
| [Month-5] | [Score] | [Score] | [Score] | [Score] | [Score] |
| [Month-4] | [Score] | [Score] | [Score] | [Score] | [Score] |
| [Month-3] | [Score] | [Score] | [Score] | [Score] | [Score] |
| [Month-2] | [Score] | [Score] | [Score] | [Score] | [Score] |
| [Month-1] | [Score] | [Score] | [Score] | [Score] | [Score] |
| [Current] | [Score] | [Score] | [Score] | [Score] | [Score] |

**Trend Analysis**: [Overall trend and key changes]

## Quality Issues & Impact Analysis
### Critical Issues (Impact: High)
1. **[Issue Title]**
   - **Description**: [Detailed issue description]
   - **Impact**: [Business impact and affected users]
   - **Root Cause**: [If known]
   - **Priority**: [Critical/High/Medium/Low]

### Medium Issues (Impact: Medium)
1. **[Issue Title]**
   - **Description**: [Brief description]
   - **Impact**: [Business impact]
   - **Priority**: [Priority level]

### Minor Issues (Impact: Low)
1. **[Issue Title]**
   - **Description**: [Brief description]
   - **Impact**: [Minor impact]
   - **Priority**: [Priority level]

## Improvement Action Plan
### Immediate Actions (Next 30 days)
| Action | Owner | Due Date | Expected Impact | Priority |
|--------|-------|----------|-----------------|----------|
| [Specific action] | [Name] | [Date] | [Quality dimension improvement] | [High/Med/Low] |
| [Specific action] | [Name] | [Date] | [Quality dimension improvement] | [High/Med/Low] |

### Short-term Improvements (Next 90 days)
| Action | Owner | Due Date | Expected Impact | Priority |
|--------|-------|----------|-----------------|----------|
| [Specific action] | [Name] | [Date] | [Quality dimension improvement] | [High/Med/Low] |
| [Specific action] | [Name] | [Date] | [Quality dimension improvement] | [High/Med/Low] |

### Long-term Initiatives (Next 6 months)
| Action | Owner | Due Date | Expected Impact | Priority |
|--------|-------|----------|-----------------|----------|
| [Specific action] | [Name] | [Date] | [Quality dimension improvement] | [High/Med/Low] |
| [Specific action] | [Name] | [Date] | [Quality dimension improvement] | [High/Med/Low] |

## Usage Analytics
### Consumer Analysis
- **Number of Active Users (30 days)**: [X users]
- **Query Volume (30 days)**: [X queries]
- **Top Use Cases**: 
  1. [Use case 1]: [X% of usage]
  2. [Use case 2]: [X% of usage]
  3. [Use case 3]: [X% of usage]

### Downstream Dependencies
- **Direct Dependencies**: [X systems/tables]
- **Critical Dependencies**: [List systems that would break if this data fails]
- **Business Reporting Impact**: [Executive dashboards, automated reports affected]

## Quality Monitoring
### Automated Monitoring
- **Quality Tests in Place**: [X tests]
- **Alert Coverage**: [X% of critical quality checks]
- **Monitoring Frequency**: [Real-time/Daily/Weekly]

### Manual Checks
- **Data Profiling Frequency**: [Monthly/Quarterly]
- **Business Logic Validation**: [How often and by whom]
- **User Feedback Collection**: [Process for collecting feedback]

## Recommendations
### For Data Producers
1. **[Recommendation 1]**: [Specific action to improve quality]
2. **[Recommendation 2]**: [Specific action to improve quality]
3. **[Recommendation 3]**: [Specific action to improve quality]

### For Data Consumers
1. **[Recommendation 1]**: [How to use this data appropriately given its quality]
2. **[Recommendation 2]**: [What to watch out for]
3. **[Recommendation 3]**: [When to seek alternatives]

### For Platform Teams
1. **[Recommendation 1]**: [Infrastructure or tooling improvements]
2. **[Recommendation 2]**: [Process improvements]

## Next Assessment
- **Scheduled Review Date**: [Date]
- **Trigger Events for Early Assessment**: [Conditions that warrant earlier review]
- **Assessment Owner**: [Name]

---

## Approvals & Sign-offs
| Role | Name | Review Date | Signature |
|------|------|-------------|-----------|
| Data Steward | [Name] | [Date] | [Approval] |
| Technical Owner | [Name] | [Date] | [Approval] |
| Business Stakeholder | [Name] | [Date] | [Approval] |

## Change History
| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | [Date] | [Name] | Initial quality assessment |
| 1.1 | [Date] | [Name] | [Description of changes] |

---
**Note**: This assessment follows data quality frameworks inspired by Airbnb's DQ Score and industry best practices for comprehensive data quality measurement.