# Architecture

Proposed separation: MCP transport and tool schemas; Python dispatch and session management; LabVIEW automation adapter; G-based VI Scripting helpers; validation and reporting.

Keep graphical object references in their owning session. Validate paths, operation parameters and connection state. Prefer explicit save and execution operations. Do not execute arbitrary VIs or modify production instruments without operator authorization.

Client configuration and actual tool names remain pending source inspection.
