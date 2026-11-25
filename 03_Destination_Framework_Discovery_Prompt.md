# Destination Framework Discovery Prompt

Before starting screen migration, perform a comprehensive analysis of
the imported destination framework.

**Do not modify any files.**

Inspect the project and identify:

1.  Programming languages and frontend framework, including exact
    version.
2.  Main application entry point.
3.  Application folder structure.
4.  Routing configuration and route registration approach.
5.  Navigation menu configuration.
6.  Main layouts and page containers.
7.  Header, sidebar and footer components.
8.  Shared UI components.
9.  Form implementation conventions.
10. Table and data-grid implementation.
11. Modal, dialog and popup implementation.
12. Styling framework and global styles.
13. Theme, colours, typography and spacing conventions.
14. API integration and HTTP service patterns.
15. State management approach.
16. Authentication, authorization and route guards.
17. Existing example screens that demonstrate the framework's intended
    design.
18. Build, lint and test commands.

For reusable components, identify their actual file paths and explain
how they should be used.

For navigation, explain exactly how a new screen should be registered
and connected to the existing menu.

Do not guess. Verify findings from actual project files.

Finally, produce a concise `DESTINATION_FRAMEWORK_REFERENCE.md` that can
be used throughout the entire screen migration.

Also identify any project-specific constraints that future screen
migrations must respect.

Do not modify application source files.
