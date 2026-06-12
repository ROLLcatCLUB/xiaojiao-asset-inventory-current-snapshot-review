# Xiaojiao Asset Inventory Current Snapshot

Date: 2026-06-13

Snapshot code:

```text
XIAOJIAO_ASSET_INVENTORY_CURRENT_SNAPSHOT
```

Purpose:

```text
asset inventory + architecture placement
```

This is not a rejection audit and not a final product seal.

It classifies existing assets by where they belong in the current Xiaojiao architecture:

```text
USE_NOW
USE_LATER
REFERENCE_ONLY
DO_NOT_USE_AS_DEFAULT
```

## Core Judgment

The previous work was not wasted.

What changed is not the intelligent foundation, but the old assumption that Xiaojiao should have one single ideal workbench page.

Current stable judgment:

```text
Xiaojiao is not one page.
Xiaojiao is a state-driven intelligence foundation plus a progressive work surface system.
```

## USE_NOW

These assets remain core and should continue to guide the system.

### 1001 State-Driven Intelligence Foundation

```text
1001A-G
```

Architecture:

```text
Intent Parser
-> Intent Clarification Card
-> Work State Manager
-> Work View Composer
-> Suggestion Engine
-> Generation Context Trimming
-> Preference Candidate
-> Observation Metrics
-> End-to-end dry-run
```

Use now:

```text
Work State schema
Composer renderDirective
Suggestion schema
Intent schema
Clarification Card schema
Context Pack schema
Preference Candidate policy
Observation Metrics
```

### 1000F-I Model Candidate Safety Chain

Architecture:

```text
Work State + Resource Context
-> Context Pack Policy
-> Model Candidate Envelope
-> Simulated Candidate Result
-> Work Object Patch
-> Teacher Review Gate
```

Use now:

```text
Resource Context Registry
Context Pack Policy
Model Candidate Envelope
Expected Output Schema
Work Object Patch
Teacher Review Gate
```

Rule:

```text
Do not return to user input -> direct model -> direct display.
```

### 1002A-B Progressive Work Surface Foundation

Use now:

```text
surface_mode
business_pack_layout_preset
resource_library as support_layer
resource_drawer
resource_picker
grid_studio only for complex tasks
teacher_control_surface as future classroom line
public_display_surface as future classroom line
```

## USE_LATER

These are valid but should be opened as later dedicated lines.

```text
classroom_teaching_studio_pack
student_evaluation_pack
resource_curation_pack
public_lesson_pack
classroom_runtime_pack
```

Suggested later lines:

```text
1003_CLASSROOM_TEACHING_STUDIO
1004_STUDENT_EVALUATION_AND_LEARNING_ANALYSIS
resource_curation_line
classroom_runtime_line
```

## REFERENCE_ONLY

These assets may provide local ideas, but should not define the default structure.

### Early Single-Page Dynamic Workbench Prototypes

Reference pieces:

```text
top status bar
attached Xiaojiao notes
suggestion / work record drawer
on-demand input
soft light visual tone
```

### Dark Cockpit Version

Reference use only:

```text
demo style
admin view
night mode
future data cockpit
```

### 1002C-H Big Package

Treat as candidate assets until reviewed:

```text
1002C low fidelity surfaces -> structural reference
1002D schema -> likely reusable
1002E classroom teaching studio concept -> likely enters 1003
1002F teacher control / public display -> 1003 reference
1002G student evaluation board -> 1004 reference
1002H integrated baseline -> inventory basis, not final route by itself
```

## DO_NOT_USE_AS_DEFAULT

Do not use these as the default Xiaojiao product route now:

```text
fixed three-column UI
fixed left context list
always-on right AI panel
bottom-right forced AI float button
all businesses enter grid_studio
teaching_plan_pack as studio
resource_library_pack as studio
directly embedded GitHub workbench
real provider call
real resource library integration
real frontend runtime modification
```

## Business Pack Placement

| Business Pack | Current Placement | Studio |
| --- | --- | --- |
| `teaching_plan_pack` | guided_flow | no |
| `lesson_design_pack` | focus_surface, optional grid_studio | optional |
| `classroom_teaching_studio_pack` | grid_studio + teacher_control_surface + public_display_surface | yes |
| `student_evaluation_pack` | analysis_board | yes, board type |
| `resource_library_pack` | support_layer + drawer + picker | no |
| `resource_curation_pack` | grid_studio | yes |
| `public_lesson_pack` | future grid_studio candidate | later |
| `classroom_runtime_pack` | future runtime line | later |

## Current Architecture Placement

```text
Xiaojiao System
|
+-- 1001 State-Driven Intelligence Foundation
|   +-- Intent Parser
|   +-- Clarification Card
|   +-- Work State Manager
|   +-- Work View Composer
|   +-- Suggestion Engine
|   +-- Preference Candidate
|   +-- Observation Metrics
|
+-- 1000F-I Model Candidate Safety Chain
|   +-- Resource Context
|   +-- Context Pack Policy
|   +-- Model Candidate Envelope
|   +-- Candidate Result
|   +-- Work Object Patch
|   +-- Teacher Review Gate
|
+-- 1002 Progressive Work Surface Foundation
|   +-- light_entry
|   +-- guided_flow
|   +-- focus_surface
|   +-- grid_studio
|   +-- analysis_board
|   +-- teacher_control_surface
|   +-- public_display_surface
|   +-- resource_drawer
|   +-- resource_picker
|
+-- 1003 Classroom Teaching Studio
|   +-- teaching_scene_bundle
|   +-- teacher_control_surface
|   +-- public_display_surface
|   +-- display_blocks
|   +-- classroom_tools
|   +-- student_task / interaction
|
+-- 1004 Student Evaluation and Learning Analysis
|   +-- student_work_gallery
|   +-- evaluation_dimensions
|   +-- class_distribution
|   +-- typical_cases
|   +-- AI comment candidate
|   +-- teacher review
|
+-- Resource Layer
    +-- resource_library
    +-- resource_drawer
    +-- resource_picker
    +-- resource_curation
    +-- resource_context_for_model_candidate
```

## Next Handling

Do not discard assets.

Do not seal everything as final route.

Use this working rule:

```text
foundation assets stay
UI shape gets reclassified
business packs route by complexity
complex classroom and analysis tasks open dedicated later lines
```
